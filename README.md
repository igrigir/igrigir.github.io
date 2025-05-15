<!DOCTYPE html>
<html lang="hr">
<head>
    <meta charset="UTF-8">
    <title>Igor Josić - Portfolio</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f6f8;
            margin: 0;
            padding: 0;
            color: #333;
        }
        .container {
            max-width: 800px;
            margin: 40px auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            display: block;
            margin: 0 auto 20px;
            border: 2px solid #ccc;
        }
        h1 {
            text-align: center;
            margin-bottom: 10px;
        }
        .info {
            font-size: 18px;
            line-height: 1.6;
            margin-bottom: 20px;
        }
        .contact {
            font-size: 16px;
            background-color: #f0f0f0;
            padding: 10px;
            border-left: 4px solid #007BFF;
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="moja-slika.jpg" alt="Igor Josić" class="profile-img">
        <h1>Igor Josić</h1>
        <div class="info">
            <p>Bavim se programiranjem u: <strong>C#, ASP.NET, PHP, SQL, VB.NET</strong>.</p>
            <p>Zanimam se za <strong>elektroniku</strong> i <strong>mehaniku</strong>, a u slobodno vrijeme volim provozati <strong>biciklom</strong>.</p>
        </div>
        <div class="contact">
            <p><strong>Kontakt broj:</strong> 065 323 591</p>
            <p><strong>Email:</strong> <a href="mailto:igor-josic@hotmail.com">igor-josic@hotmail.com</a></p>
        </div>
    </div>
</body>
</html>
