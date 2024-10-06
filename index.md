<!DOCTYPE html>
<html class="h-100">
<head>
    <title>Home | Lexie Midtun</title>
    <link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-0evHe/X+R7YkIZDRvuzKMRqM+OrBnVFBL6DOitfPri4tjfHxaWutUpFmBp4vmVor" crossorigin="anonymous">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
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

<main class="flex-shrink-1">
    <div class="container" style="max-width:1000px;">
        <div class="row">
            <div class="col-md-2 col-sm-3 col-xs-3 mt-4">
                <img class="rounded shadow img-fluid" src="/assets/img_people/profile.png" data-holder-rendered="true" alt="Profile Picture">
            </div>
            <div class="col-md-10 col-sm-9 col-xs-6 mt-2 pt-3">
                <h1>Lexie Midtun</h1>
                <p class="lead">
                    Computer Science and Cybersecurity Student<br>
                    Arizona State University<br>
                </p>
            </div>
        </div>

        <hr>

        <h2>Quick Links</h2>
        <ul>
            <li><a href="/projects/" class="link-danger">Explore my projects.</a></li>
            <li><a href="/resume/" class="link-danger">View my resume.</a></li>
            <li><a href="mailto:lexiemidtun@example.com" class="link-danger">Contact Me</a></li>
        </ul>

        <h2>About Me</h2>
        <p>
            I am a dedicated computer science and cybersecurity student at Arizona State University, with a focus on cryptology and data security. My goal is to work in government cybersecurity, utilizing my skills to protect critical information systems.
        </p>

        <h2>Recent News</h2>
        <div class="mb-5">
            <h5>October 2024</h5>
            <p class="mx-2">I have applied for the SMART Scholarship program through the Department of Defense to further my studies in cybersecurity.</p>
            <h5>September 2024</h5>
            <p class="mx-2">Started a research project on the impacts of technology on cybersecurity measures.</p>
        </div>
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
