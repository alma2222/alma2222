<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to My Webpage</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Webpage</h1>
    </header>

    <main>
        <!-- Added the image with the provided URL -->
        <img src="https://webworksagency.com/wp-content/uploads/2015/07/introducing-web-technologies.jpg" alt="Web Technologies">
        <p>This is a sample paragraph of text to demonstrate the structure of a basic webpage.</p>
        <a href="https://www.example.com" target="_blank">Visit Example Website</a>
    </main>

    <footer>
        <p>&copy; <span id="2025"></span> Jood</p>
    </footer>

    <script>
        // Set the current year dynamically in the footer
        document.getElementById("current-year").textContent = new Date().getFullYear();
    </script>
</body>
</html>
