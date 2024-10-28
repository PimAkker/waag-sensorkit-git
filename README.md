This was a project from my internship at the Waag. I designed and partially manufactured the mechanical components for this low-cost air quality sensor for the project [hollandse luchten](https://hollandse-luchten.org/). During my internship, I went from design to the production of 200 units. 
![alt text](image_21.png)

The project was a collaboration between the Waag, RIVM, and the province of Noord-Holland. The goal was to create a network of air quality sensors that would be placed near TATA steel. The data collected by the sensors would be used to create a map of the air quality in the city. The sensors were designed to be low-cost and easy to assemble so that they could be deployed in large numbers.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Layout</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .image-box {
            flex: 1 1 calc(50% - 20px);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            overflow: hidden;
            text-align: center;
        }
        .image-box img {
            width: 100%;
            height: auto;
            display: block;
        }
        .caption {
            padding: 10px;
            background-color: #f8f8f8;
            border-top: 1px solid #ddd;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="image-box">
            <img src="image_16.png" alt="real world example">
            <div class="caption">Real World Example</div>
        </div>
        <div class="image-box">
            <img src="image_17.png" alt="3d render shortened version">
            <div class="caption">3D Render Shortened Version</div>
        </div>
        <div class="image-box">
            <img src="image_18.png" alt="3d render extended version">
            <div class="caption">3D Render Extended Version</div>
        </div>
        <div class="image-box">
            <img src="image_20.png" alt="Inside real world">
            <div class="caption">Inside Real World</div>
        </div>
    </div>
</body>
</html>
