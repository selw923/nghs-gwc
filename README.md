# Adding Webpages

If you want to add new HTML webpages to the site, use this template and update navbar.html and/or footer.html:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title><!-- Webpage Title --></title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg==" crossorigin="anonymous" referrerpolicy="no-referrer">
    <link rel="shortcut icon" href="images/favicon.png">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
</head>
</head>
<body>
    <!-- Navbar -->
    <div id="nav-placeholder"></div>
    <script>
        $.get("html/navbar.html", function(data){
            $("#nav-placeholder").replaceWith(data);
        });
    </script>

    <!-- Webpage content -->

    <!-- Footer -->
    <div id="foot-placeholder"></div>
    <script>
    $.get("html/footer.html", function(data){
        $("#foot-placeholder").replaceWith(data);
    });
    </script>

    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
    integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
    crossorigin="anonymous"></script>
    <script src="js/main.js"></script>
</body>
</html>
```