# Sample-site_MicroDegree_homepage
https://icon2.cleanpng.com/20180817/vog/8968d0640f2c4053333ce7334314ef83.webp
================================================================================================

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Microdegree - AWS Demo</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background: linear-gradient(135deg, #0f172a, #1e3a8a);
            color: white;
            min-height: 100vh;
        }

        header {
            padding: 20px;
            text-align: center;
            background: rgba(0, 0, 0, 0.25);
        }

        header h1 {
            margin: 0;
            font-size: 32px;
        }

        .moving-text {
            width: 100%;
            overflow: hidden;
            white-space: nowrap;
            margin-top: 30px;
        }

        .moving-text span {
            display: inline-block;
            font-size: 42px;
            font-weight: bold;
            animation: moveRight 8s linear infinite;
        }

        @keyframes moveRight {
            0% {
                transform: translateX(-100%);
            }

            100% {
                transform: translateX(100vw);
            }

            .container {
            max-width: 900px;
            margin: 50px auto;
            padding: 20px;
            text-align: center;
        }

        .card {
            background: rgba(255, 255, 255, 0.12);
            border-radius: 20px;
            padding: 35px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
            backdrop-filter: blur(10px);
        }

        .aws-image {
            width: 280px;
            max-width: 80%;
            margin: 20px auto;
            border-radius: 15px;
            display: block;
        }

        .status {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            border-radius: 25px;
            background: #22c55e;
            color: white;
            font-weight: bold;
        }

        footer {
            margin-top: 40px;
            padding: 20px;
            text-align: center;
            opacity: 0.8;
        }
    </style>
</head>

<body>

<header>
    <h1>Amazon EC2 Ubuntu Web Server</h1>
</header>

<div class="moving-text">

    <span>Welcome to Microdegree 🚀</span>
</div>

<div class="container">

    <div class="card">

        <h2>AWS Apache Web Server Demo</h2>

        <p>
            This website was automatically deployed using
            <strong>EC2 User Data</strong>.
        </p>

        <!-- AWS image -->
        <img
            class="aws-image"
            src="https://icon2.cleanpng.com/20180817/vog/8968d0640f2c4053333ce7334314ef83.webp"
            alt="Amazon Web Services"
        >

        <h2>Ubuntu + Apache + AWS</h2>

        <p>
            Apache Web Server is running successfully.
        </p>

        <div class="status">
            ✓ Server Online
        </div>

    </div>

</div>

<footer>
    Microdegree AWS Demo | EC2 User Data
</footer>

</body>
</html>
