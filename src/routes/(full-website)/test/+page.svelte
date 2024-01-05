<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Card Game</title>
</head>
<body>
    <h1>Welcome to the Image Card Game</h1>
    <button onclick="getRandomCard()">Give me a card</button>
    <div id="image-container"></div>

    <script>
        function getRandomCard() {
    fetch('/Users/eliserodriguez/Desktop/Projects/Chisme_Loteria/chisme/image-list.json')
        .then(imageList => {
            if (imageList.length === 0) {
                throw new Error('No images found');
            }
            const randomIndex = Math.floor(Math.random() * imageList.length);
            const randomImage = imageList[randomIndex];
            const imagePath = `/Users/eliserodriguez/Desktop/Projects/Chisme_Loteria/chisme/${randomImage}`;
            const imageContainer = document.getElementById('image-container');
            
            // Use an <img> tag to display the image
            imageContainer.innerHTML = `<img src="${imagePath}" alt="${imagePath}"/>`;
        })
        .then(response => {
            if (!response.ok) {
                throw new Error('Failed to fetch image list');
            }
            return response.json();
        })
        .catch(error => console.error('Error:', error));
        }
    </script>
</body>
</html>