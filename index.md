<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <title>Home - Lexie Midtun's Website</title>

  <!-- Inline CSS to style the navigation bar -->
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
      background-color: #333; /* Dark background for the navigation bar */
      padding: 10px 0;
      position: fixed; /* Make the nav bar stick at the top */
      width: 100%; /* Make the nav bar stretch across the entire page width */
      top: 0; /* Stick to the top of the viewport */
      left: 0;
      z-index: 1000; /* Make sure it's above other content */
    }

    nav ul {
      list-style: none; /* Remove bullet points */
      padding: 0;
      margin: 0;
      display: flex; /* Flexbox to align items horizontally */
      justify-content: flex-start; /* Align nav items to the left */
      margin-left: 20px; /* Small left margin for better aesthetics */
    }

    nav ul li {
      margin-right: 20px; /* Space between each nav item */
    }

    nav a {
      color: white; /* White text for the navigation links */
      text-decoration: none; /* Remove underline */
      font-size: 18px;
    }

    nav a:hover {
      text-decoration: underline; /* Add underline on hover */
    }

    /* Main Content Area */
    main {
      padding-top: 80px; /* Make sure the content doesn't hide behind the fixed nav bar */
      text-align: center; /* Center the main content */
    }

    /* Footer Styling (Optional) */
    footer {
      background-color: #333;
      color: white;
      padding: 10px 0;
      text-align: center;
      position: fixed;
      bottom: 0;
      width: 100%;
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

  <!-- Footer (Optional) -->
  <footer>
    <p>&copy; 2024 Lexie Midtun</p>
    <a href="https://github.com/lexiemidtun" target="_blank" style="color: white;">GitHub</a> |
    <a href="https://www.linkedin.com/in/lexiemidtun/" target="_blank" style="color: white;">LinkedIn</a>
  </footer>

</body>
</html>
