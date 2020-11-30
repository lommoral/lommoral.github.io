<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>LMMV PORTFOLIO</title>

    <!-- Latest compiled and minified CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">

    <!-- jQuery library -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

    <!-- Latest compiled JavaScript -->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>

    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Roboto+Condensed:ital,wght@0,300;0,400;0,700;1,300;1,400;1,700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="portfolio-styles.css">
    
</head>
<body>
    <header class="container-fluid">
        <h1>PORTFOLIO | Lourdes Morales Villaverde</h1>
        <p>
            Junior Software / Front-end Web Developer 
        </p>
        <p>
            Email: <a href="mailto:lmmoralesvill@gmail.com">lmmoralesvill@gmail.com</a>
        </p>
        <p>
            <a href="https://www.linkedin.com/in/lommoral/" target="_blank">
                LinkedIn
                <span class="glyphicon glyphicon-new-window"></span>
            </a>
        </p>
    </header>

    <div class="role container-fluid">
        <h2>Web Developer.</h2>
        <p class="company">
            <a href="https://www.sigaccess.org/" target="_blank">ACM’s Special Interest Group on Accessible Computing</a>.
        </p>
        <p class="range">Jan 2017 - Oct 2018.</p>
        <p class="duties">
            <ul>
                <li>
                    Cowrote guide and developed form to assist conferences in creating their own Accessibility FAQ page.
                </li>
                <li>
                    Tools: HTML, CSS and JavaScript.
                </li>
            </ul>
        </p>

        <button type="button" class="btn btn-primary btn-block" data-toggle="collapse" data-target="#guide">
            <span class="glyphicon glyphicon-collapse-down"></span>
            Guide to Creating a Conference Accessibility FAQ Page
        </button>
        <div id="guide" class="collapse">
            <iframe
                src="https://www.sigaccess.org/welcome-to-sigaccess/resources/creating-a-conference-accessibility-faq-page/"
                title="Guide" height="350px" width="99%">
            </iframe>
        </div>

        <button type="button" class="btn btn-primary btn-block" data-toggle="collapse" data-target="#generator">
            <span class="glyphicon glyphicon-collapse-down"></span>
            Accessibility FAQ Page Generator
        </button>
        <div id="generator" class="collapse">
            <div style="width:100%;height:350px;overflow:hidden;">
                <iframe 
                    src="https://www.sigaccess.org/accessibility-faq-page-generator-2/" 
                    title="Generator" height="350px" width="99%">
                </iframe>
            </div>
        </div>
    </div>

    <div class="role container-fluid">
        <h2>Web Chair.</h2>
        <p class="company">
            <a href="https://www.sigaccess.org/assets/" target="_blank">
                Int ACM SIGACCESS Conference on Computers and Accessibility</a>.
        </p>
        <p class="range">
             Sep 2015 - Oct 2018.
        </p>
        <p class="duties">
            <ul>
                <li>
                    Developed interactive, responsive and accessible conference websites.
                </li>
                <li>
                    Tools: HTML, CSS, JavaScript and jQuery.
                </li>
            </ul>
        </p>
        <button type="button" class="btn btn-dark btn-block" data-toggle="collapse" data-target="#assets18">
            <span class="glyphicon glyphicon-collapse-down"></span>
            ASSETS 2018
        </button>
        <div id="assets18" class="collapse">
            <div style="width:100%;height:350px;overflow:hidden;">
                <iframe src="https://assets18.sigaccess.org/" title="ASSETS 2018" height="350px" width="99%"></iframe>
            </div>
        </div>

        <button type="button" class="btn btn-dark btn-block" data-toggle="collapse" data-target="#assets17">
            <span class="glyphicon glyphicon-collapse-down"></span>
            ASSETS 2017
        </button>
        <div id="assets17" class="collapse">
            <div style="width:100%;height:350px;overflow:hidden;">
                <iframe src="https://assets17.sigaccess.org/" title="ASSETS 2017" height="350px" width="99%"></iframe>
            </div>
        </div>

        <button type="button" class="btn btn-block btn-lg btn-dark" data-toggle="collapse" data-target="#assets16">
            <span class="glyphicon glyphicon-collapse-down"></span>
            ASSETS 2016
        </button>
        <div id="assets16" class="collapse">
            <div style="width:100%;height:350px;overflow:hidden;">
                <iframe src="https://assets16.sigaccess.org/" title="ASSETS 2016" height="350px" width="99%"></iframe>
            </div>
        </div>
    </div>

    <div class="role container-fluid">
        <h2>Graduate Student Researcher.</h2>
        <p class="company">
            <a href="https://www.ucsc.edu/">
                University of California, Santa Cruz</a>.
        </p>
        <p class="range">
             Sep 2012 - Jul 2019.
        </p>
        <h3>
            Online Learning System for People with Developmental Disabilities.
        </h3>
        <p>
            <ul>
                <li>
                    Lead development of high-fidelity prototype web application.
                </li>
                <li>
                    Implemented server-side of high-fidelity prototype web application.
                </li>
                <li>
                    Tools: HTML, CSS, JavaScript, jQuery, PHP and MySQL.
                </li>
            </ul>
            <a href="https://imagine.soe.ucsc.edu/" class="btn btn-success" role="button" target="_blank">
                Prototype <span class="glyphicon glyphicon-new-window"></span>
            </a>
        </p>
    </div>
    
    <footer class="container-fluid text-center">
        <a href="LMMV_RESUME_112020.pdf" target="_blank" class="btn btn-link btn-lg btn-block" role="button">
            Resume [PDF] 
            <span class="glyphicon glyphicon-new-window"></span>
        </a>
    </footer>

</body>
</html>