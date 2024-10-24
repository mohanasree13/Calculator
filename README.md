# Calculator Html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Gallery</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="gallery">
        <div class="gallery-grid">
            <img src="image1.jpg" alt="Image 1" onclick="openModal(this.src)">
            <img src="image2.jpg" alt="Image 2" onclick="openModal(this.src)">
            <img src="image3.jpg" alt="Image 3" onclick="openModal(this.src)">
            <img src="image4.jpg" alt="Image 4" onclick="openModal(this.src)">
            <img src="image5.jpg" alt="Image 5" onclick="openModal(this.src)">
            <img src="image6.jpg" alt="Image 6" onclick="openModal(this.src)">
        </div>
    </div>

    <div class="modal" id="modal" onclick="closeModal()">
        <span class="close" onclick="closeModal()">&times;</span>
        <img class="modal-content" id="modal-img">
    </div>

    <script src="script.js"></script>
</body>
</html>
