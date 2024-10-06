<!DOCTYPE html>
<html class="h-100">
<head>
    <title>Home | Lexie Midtun</title>
    <link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
    <link rel="stylesheet" href="/assets/styles/font-awesome-4.7.0/css/font-awesome.css">
    
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-0evHe/X+R7YkIZDRvuzKMRqM+OrBnVFBL6DOitfPri4tjfHxaWutUpFmBp4vmVor" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.4.0/font/bootstrap-icons.css">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.bundle.min.js" integrity="sha384-pprn3073KE6tl6bjs2QrFaJGz5/SUsLqktiwsUTF55Jfv3qYSDhgCecCxMW52nD2" crossorigin="anonymous"></script>
</head>

<body class="d-flex flex-column h-100">

<header id="header">
    <script>
        $(function() {
            $("#header").load("/assets/html/header.html");
        });
    </script>
</header>

<nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
        <a class="navbar-brand" href="#">Lexie Midtun</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
                <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="index.html">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="projects/index.html">Projects</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<main class="flex-shrink-1">
    <div class="container" style="max-width:1000px;">
        <div class="row">

            <div class="col-md-2 col-sm-3 col-xs-3 mt-4">
                <img class="rounded shadow img-fluid" src="/assets/img_people/profile.png" data-holder-rendered="true">
            </div>

            <div class="col-md-10 col-sm-9 col-xs-6 mt-2 pt-3">
                <h1>Lexie Midtun</h1>
                <p class="lead">
                    Computer Science and Cybersecurity Student<br>
                    Arizona State University
                </p>
            </div>
            
        </div>

        <hr>

        <h2>About</h2>
        <p>
            I am a Computer Science and Cybersecurity student at Arizona State University. My interests include cryptology and enhancing cybersecurity measures to keep up with technological advancements.
        </p>

        <h5>External links</h5> 
        <ul>
            <li><a href='https://www.linkedin.com/in/your-linkedin' class='link-danger' target='_blank'>LinkedIn</a></li>
            <li><a href='https://github.com/your-github' class='link-danger' target='_blank'>GitHub</a></li>
            <li><a href='https://twitter.com/your-twitter' class='link-danger' target='_blank'>Twitter</a></li>
        </ul>

        <hr>
        <h2>Recent News</h2>
        <p class="mx-2">Content about your recent accomplishments or updates can go here.</p>

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
