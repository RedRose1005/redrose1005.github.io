<!DOCTYPE html>
<html lang="en" class="h-100">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home | Lexie Midtun</title>
    <link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.4.0/font/bootstrap-icons.css">
    <link rel="stylesheet" href="/assets/styles/font-awesome-4.7.0/css/font-awesome.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.bundle.min.js"></script>
</head>

<body class="d-flex flex-column h-100">

<header id="header">
    <script>
        $(function() {
            $("#header").load("/assets/html/header.html");
        });
    </script>
</header>

<main class="flex-shrink-1">
    <div class="container" style="max-width:1000px;">
        <div class="row">

            <div class="col-md-2 col-sm-3 col-xs-3 mt-4">
                <img class="rounded shadow img-fluid" src="/assets/img_people/profile.png" alt="Lexie Midtun">
            </div>

            <div class="col-md-10 col-sm-9 col-xs-6 mt-2 pt-3">
                <h1>Lexie Midtun</h1>
                <p class="lead">
                    Aspiring Cybersecurity Professional<br>
                    Computer Science & Cybersecurity Student<br>
                    Arizona State University
                </p>
            </div>
            
        </div>

        <hr>

        <h2>About Me</h2>
        <p>
            I am currently studying computer science and cybersecurity at Arizona State University. I have a strong interest in cryptology and aim to work in cybersecurity for the government. My academic pursuits also extend to mathematics and criminal justice.
        </p>

        <h2>Projects</h2>
        <ul>
            <li><a href="/projects/project1/" class="link-danger">Project 1: Description of your project</a></li>
            <li><a href="/projects/project2/" class="link-danger">Project 2: Description of your project</a></li>
            <li><a href="/projects/project3/" class="link-danger">Project 3: Description of your project</a></li>
            <!-- Add more projects as needed -->
        </ul>

        <h2>Recent News</h2>
        <div class="mb-5">
            <h5>October 2024</h5>
            <p class="mx-2">Excited to start new research opportunities in cybersecurity!</p>

            <h5>September 2024</h5>
            <p class="mx-2">Joined the campus cybersecurity club to enhance my skills and network.</p>

            <!-- Add more news as needed -->
        </div>

        <h2>Contact</h2>
        <p>If you'd like to get in touch, feel free to reach out via <a href="mailto:your-email@example.com" class="link-danger">email</a>.</p>

    </div> <!-- end container -->
</main>

<footer class="footer mt-auto py-3 bg-light border border-top" id="footer">
    <script>
        $(function() {
            $("#footer").load("/assets/html/footer.html");
        });
    </script>
</footer>

</body>
</html>
