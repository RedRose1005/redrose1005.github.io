<!DOCTYPE html>
<html class="h-100">
<head>
    <title>Home | Lexie Midtun</title>
    <link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-0evHe/X+R7YkIZDRvuzKMRqM+OrBnVFBL6DOitfPri4tjfHxaWutUpFmBp4vmVor" crossorigin="anonymous">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
</head>

<body class="d-flex flex-column h-100">
<header id="header"></header> <!-- No script here -->

<script>
    $(function() {
        $("#header").load("/assets/html/header.html");
    });
</script>

<main class="flex-shrink-1">
    <!-- Main content -->
</main>

<footer class="footer mt-auto py-3 bg-light border border-top" id="footer"></footer>

<script>
    $(function() {
        $("#footer").load("/assets/html/footer.html");
    });
</script>
</body>
</html>
