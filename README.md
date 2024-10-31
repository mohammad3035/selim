
<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ডেস্কটপ সাইট</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .navbar {
            background-color: #333;
            overflow: hidden;
        }
        .navbar a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        .navbar a:hover {
            background-color: #ddd;
            color: black;
        }
    </style>
    <script>
        if (window.innerWidth < 768) {
            window.location.href = "http://example.com"; // এখানে আপনার ডেস্কটপ সাইটের URL দিন
        }
    </script>
</head>
<body>

<div class="navbar">
    <a href="#home">হোম</a>
    <a href="#about">আমাদের সম্পর্কে</a>
    <a href="#services">সেবা</a>
    <a href="#contact">যোগাযোগ</a>
</div>

<h1>স্বাগতম!</h1>
<p>এটি একটি ডেস্কটপ সাইটের উদাহরণ।</p>

</body>
</html>
