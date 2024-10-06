<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <title>Home - Lexie Midtun's Website</title>

  <!-- Inline CSS to style the navigation bar and footer -->
  <style>
    /* General Page Styling */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }

    h1 {
      color: #333;
    }

    p {
      color: #666;
      font-size: 18px;
      margin: 10px 0;
    }

    /* Navigation Bar Styling */
    nav {
      background-color: #E9EBEE; /* Light gray background for the navigation bar */
      padding: 10px 0;
      position: fixed; /* Make the nav bar stick at the top */
      width: 100%; /* Full width of the page */
      top: 0;
      left: 0;
      z-index: 1000; /* Ensure it is above other content */
    }

    nav ul {
      list-style: none;
      padding: 0;
      margin: 0;
      display: flex;
      justify-content: flex-end; /* Align items to the right */
      margin-right: 20px; /* Add space on the right side */
    }

    nav ul li {
      margin-right: 20px; /* Space between navigation items */
    }

    nav a {
      color: #333; /* Darker text for better contrast */
      text-decoration: none;
      font-size: 18px;
    }

    nav a:hover {
      text-decoration: underline; /* Underline effect on hover */
    }

    /* Main Content Area */
    main {
      padding-top: 80px; /* Avoid content being hidden under the fixed nav bar */
      text-align: center;
    }

    /* Footer Styling */
    footer {
      background-color: #E9EBEE; /* Light gray with a blue tint */
      color: #333; /* Darker text color for contrast */
      padding: 10px 0; /* Padding for top and bottom */
      text-align: center; /* Center the text */
      position: fixed; /* Keep the footer fixed at the bottom */
      bottom: 0; /* Align it to the bottom of the page */
      left: 0; /* Align it to the left edge */
      width: 100%; /* Make sure it stretches across the full width */
      box-sizing: border-box; /* Ensures padding does not affect width */
    }

    footer a {
      color: #333; /* Match footer link color with the dark text */
      text-decoration: none;
    }

    footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <!-- Navigation Bar -->
  <nav>
    <ul>
      <li><a href="/">Home</a></li>
      <li><a href="/projects/">Projects</a></li>
    </ul>
  </nav>

  <!-- Main Content -->
  <main>
    <h1>Welcome to My Home Page</h1>
    <p>This is the homepage of my website. Feel free to explore!</p>
  </main>

  <!-- Footer -->
  <footer>
    <p>&copy; 2024 Lexie Midtun</p>
    <a href="https://github.com/lexiemidtun" target="_blank">GitHub</a> |
    <a href="https://www.linkedin.com/in/lexiemidtun/" target="_blank">LinkedIn</a>
  </footer>

</body>
</html>
