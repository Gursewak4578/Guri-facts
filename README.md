<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GURI Facts</title>
    <style>
        /* Your CSS styles here */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8c291; /* Background color */
            color: #333; /* Text color */
            line-height: 1.6;
        }
        header {
            background-color: #FF5733; /* Header background color */
            color: #fff; /* Header text color */
            padding: 20px;
            text-align: center;
            text-transform: uppercase; /* Convert text to uppercase */
        }
        .container {
            width: 90%; /* Adjust as needed */
            max-width: 800px;
            margin: auto;
            padding: 20px;
        }
        .buttons {
            text-align: center;
            margin-top: 20px;
        }
        .button {
            display: inline-block;
            padding: 12px 24px;
            background-color: #FFC300; /* Button background color */
            color: #fff; /* Button text color */
            text-decoration: none;
            border-radius: 25px;
            margin: 10px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .button:hover {
            background-color: #FF5733; /* Button hover background color */
        }
        .feedback-button {
            background-color: #4CAF50; /* Feedback button background color */
        }
        section {
            margin-top: 30px;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            transition: box-shadow 0.3s ease;
        }
        section:hover {
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
        }
        h2 {
            color: #FF5733;
            text-align: center;
            margin-bottom: 20px;
        }
        iframe {
            width: 100%;
            height: 400px;
            border: none;
            border-radius: 10px;
        }
        p {
            font-size: 18px;
            line-height: 1.5;
        }
        textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
            resize: vertical;
        }
        .feedback-text {
            text-align: center;
            color: #4CAF50;
            font-weight: bold;
            margin-top: 20px;
        }
        .feedback-text a {
            color: #4CAF50;
            text-decoration: underline;
            transition: color 0.3s ease;
        }
        .feedback-text a:hover {
            color: #3366FF;
        }
        .logo {
            text-align: center;
            margin-bottom: 20px;
        }
        .logo img {
            max-width: 100%;
            height: auto;
        }
        .photo {
            text-align: center;
            margin-bottom: 20px;
        }
        .photo img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
<header>
    <div class="logo">
        <img src="file:///C:/Users/sawkg/OneDrive/Pictures/logo%20.png" alt="GURI Facts Logo">
    </div>
    <h1>GURI Facts</h1>
</header>

<div class="container">
    <div class="buttons">
        <a href="#videos" class="button" onclick="showVideos()">Watch Videos</a>
        <a href="#facts" class="button" onclick="showFacts()">Read Facts</a>
    </div>

    <section id="videos" style="display: none;">
        <h2>Videos</h2>
        <iframe width="100%" height="315" src="" frameborder="0" allowfullscreen></iframe>
    </section>

    <section id="facts" style="display: none;">
        <h2>Facts</h2>
        <p>Here are some amazing facts:</p>
        <p></p>
        <p></p>
    </section>

    <div class="feedback-text">
        <p>GIVE YOUR FEEDBACK at <a href="mailto:g39415207@gmail.com">g39415207@gmail.com</a></p>
    </div>

    



<script>
    function showVideos() {
        document.getElementById("videos").style.display = "block";
        document.getElementById("facts").style.display = "none";
    }

    function showFacts() {
        document.getElementById("videos").style.display = "none";
        document.getElementById("facts").style.display = "block";
    }

    window.onload = function() {
        alert("Welcome to Amazing Facts!");
    };

    window.onbeforeunload = function() {
        return "Are you sure you want to leave this page?";
    };
</script>

</body>
</html>
