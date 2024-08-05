# NGHS Girls Who Code Chapter Website
Some info for editing and making changes to the site.

## Adding New Webpages
To add new HTML webpages to the site, use this template and update the navbar and/or footer.html as needed:
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
    <nav class="navbar">
        <div class="container">
            <div class="logo">
                <a href="index.html">
                    <img src="images/gwcweblogo.png" alt="logo" width="35%">
                </a>
            </div>
            <div class="main-menu">
                <ul>
                    <li>
                        <a href="about.html">ABOUT US</a>
                        <ul>
                            <li>
                                <a href="about.html">ABOUT GWC</a>
                            </li>
                            <li>
                                <a href="exec.html">EXEC BOARD</a>
                            </li>
                        </ul>
                    </li>
                    <li>
                        <a href="schedule.html">SCHEDULE</a>
                    </li>
                    <li>
                        <a href="opportunities.html">OPPORTUNITIES</a>
                    </li>
                    <li>
                        <a href="points.html">POINTS</a>
                    </li>
                    <li>
                        <a href="join.html">JOIN</a>
                    </li>
                </ul>
            </div>
            <!-- Hamburger Menu -->
            <button class="hamburger-button">
                <div class="hamburger-line"></div>
                <div class="hamburger-line"></div>
                <div class="hamburger-line"></div>
            </button>
            <div class="mobile-menu">
                <ul>
                    <li>
                        <a href="about.html">ABOUT GWC</a>
                    </li>
                    <li>
                        <a href="exec.html">EXEC BOARD</a>
                    </li>
                    </li>
                    <li>
                        <a href="schedule.html">SCHEDULE</a>
                    </li>
                    <li>
                        <a href="opportunities.html">OPPORTUNITIES</a>
                    </li>
                    <li>
                        <a href="points.html">POINTS</a>
                    </li>
                    <li>
                        <a href="join.html">JOIN</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Webpage Content -->
    <section class="new-section">
        <div class="container-sm peach">
            <div class="new-section-content">
                <h1 class="new-section-heading text-heading">
                    New Section
                </h1>
                <div class="new-section-text">
                    New section text.
                </div>
                <!-- Add more divs for page content or images as needed -->
            </div>
        </div>
    </section>

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
