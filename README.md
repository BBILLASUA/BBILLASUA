<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Galería de Imágenes</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="gallery">
        <img src="imagen1.jpg" alt="Imagen 1" class="thumbnail" onclick="openModal();currentSlide(1)">
        <img src="imagen2.jpg" alt="Imagen 2" class="thumbnail" onclick="openModal();currentSlide(2)">
        <img src="imagen3.jpg" alt="Imagen 3" class="thumbnail" onclick="openModal();currentSlide(3)">
        <!-- Agrega más imágenes según sea necesario -->
    </div>

    <!-- Modal/Lightbox -->
    <div id="myModal" class="modal">
        <span class="close cursor" onclick="closeModal()">&times;</span>
        <div class="modal-content">
            <div class="mySlides">
                <img src="imagen1.jpg" alt="Imagen 1" class="modal-image">
            </div>
            <div class="mySlides">
                <img src="imagen2.jpg" alt="Imagen 2" class="modal-image">
            </div>
            <div class="mySlides">
                <img src="imagen3.jpg" alt="Imagen 3" class="modal-image">
            </div>
            <!-- Agrega más imágenes según sea necesario -->

            <!-- Controles de navegación -->
            <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
            <a class="next" onclick="plusSlides(1)">&#10095;</a>
        </div>
    </div>

    <script src="scripts.js"></script>
</body>
</html>
