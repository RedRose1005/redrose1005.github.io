<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="path/to/bootstrap.css"> <!-- Adjust the path to Bootstrap CSS -->
    <link rel="stylesheet" href="path/to/fontawesome.css"> <!-- Adjust the path to FontAwesome CSS -->
    <link rel="stylesheet" href="style.css"> <!-- Your custom CSS -->
    <title>Lexie Midtun - Home</title>
</head>
<body>

    <!-- Include the header -->
    <div id="header">
        <!-- You can use server-side includes or JavaScript to include header.html here -->
        <!-- Example using JavaScript: -->
        <script>
            fetch('/assets/html/header.html')
                .then(response => response.text())
                .then(data => {
                    document.getElementById('header').innerHTML = data;
                });
        </script>
    </div>

    <div class="container" style="max-width: 1000px">
        <h1>Welcome to My Site!</h1>
        <p>This is the home page. Here you can learn more about me and my projects.</p>
        <!-- Add more content for the home page as needed -->
    </div>

    <script src="path/to/bootstrap.bundle.js"></script> <!-- Adjust the path to Bootstrap JS -->
</body>
</html>
