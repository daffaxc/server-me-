<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>my galerry</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .gallery-item {
            margin: 10px;
            border: 1px solid #ccc;
            border-radius: 10px;
            overflow: hidden;
            background-color: #fff;
            width: 300px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .gallery-item img {
            width: 100%;
            height: auto;
        }
        .gallery-item h3 {
            padding: 10px;
            text-align: center;
            font-size: 1.2em;
            color: #333;
        }
    </style>
</head>
<body>

<h1>MY GALLERY</h1>
<div class="gallery">
    <div class="gallery-item">
        <img src="image1.jpg" alt="Image 1">
        <h3>Title 1</h3>
    </div>
    <div class="gallery-item">
        <img src="image2.jpg" alt="Image 2">
        <h3>Title 2</h3>
    </div>
    <div class="gallery-item">
        <img src="image3.jpg" alt="Image 3">
        <h3>Title 3</h3>
    </div>
    <div class="gallery-item">
        <img src="WhatsApp Image 2025-01-31 at 13.32.56.jpeg" alt="Image 4">
        <h3>skizo</h3>
    </div>
    <div class="gallery-item">
        <img src="WhatsApp Image 2025-02-03 at 08.53.08_27eefb1e.jpg" alt="Image 5">
        <h3>skizo</h3>
    </div>
</div>

</body>
</html>
