# Calaf-Land
Calaf Land - سایت شخصی کالاف من 😱⚔️
<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="theme-color" content="#050914">

    <title>CalafLand | کالاف لند</title>

    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: Tahoma, Arial, sans-serif;
            background: #050914;
            color: white;
            line-height: 1.8;
        }

        header {
            background: #081329;
            padding: 18px;
            text-align: center;
            border-bottom: 2px solid #00d9ff;
        }

        .logo {
            font-size: 30px;
            font-weight: bold;
            color: #00e5ff;
            text-shadow: 0 0 15px #008cff;
        }

        nav {
            margin-top: 12px;
        }

        nav a {
            display: inline-block;
            color: white;
            text-decoration: none;
            margin: 5px 8px;
            font-size: 14px;
        }

        nav a:hover {
            color: #00e5ff;
        }

        .hero {
            text-align: center;
            padding: 65px 20px;
            background:
                radial-gradient(
                    circle at top,
                    #123d75 0%,
                    #050914 75%
                );
        }

        .hero h1 {
            font-size: 48px;
            color: #00e5ff;
            text-shadow: 0 0 25px #008cff;
            margin-bottom: 15px;
        }

        .hero p {
            color: #d2e7ff;
            font-size: 17px;
            margin-bottom: 25px;
        }

        .button {
            display: inline-block;
            padding: 12px 22px;
            margin: 5px;
            border-radius: 12px;
            background: linear-gradient(
                100deg,
                #007bff,
                #8b35ff
            );
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        .section {
            padding: 40px 18px;
            max-width: 1100px;
            margin: auto;
        }

        .section h2 {
            text-align: center;
            color: #00e5ff;
            font-size: 27px;
            margin-bottom: 25px;
        }

        .welcome {
            text-align: center;
            background: #0c1930;
            border: 1px solid #164b7d;
            border-radius: 20px;
            padding: 25px;
            margin: 20px auto;
            max-width: 800px;
        }

        .welcome h2 {
            margin-bottom: 15px;
        }

        #introText {
            font-size: 17px;
            color: #d7eaff;
            min-height: 55px;
            margin-bottom: 15px;
        }

        button {
            background: #00e5ff;
            color: #04101d;
            border: none;
            border-radius: 10px;
            padding: 12px 20px;
            font-family: inherit;
            font-weight: bold;
            cursor: pointer;
        }

        .cards {
            display: grid;
            grid-template-columns:
                repeat(auto-fit, minmax(220px, 1fr));
            gap: 18px;
        }

        .card {
            background: #0c1930;
            border: 1px solid #203d65;
            border-radius: 18px;
            padding: 22px;
            text-align: center;
            transition: 0.25s;
        }

        .card:hover {
            transform: translateY(-5px);
            border-color: #00e5ff;
            box-shadow: 0 0 20px #007bff30;
        }

        .card .icon {
            font-size: 38px;
        }

        .card h3 {
            color: #75eaff;
            margin: 10px 0;
        }

        .card p {
            color: #c0d0e8;
            font-size: 14px;
        }

        .video-link {
            display: inline-block;
            margin-top: 15px;
            color: #00e5ff;
            text-decoration: none;
            font-weight: bold;
        }

        .note {
            text-align: center;
            color: #91a6c5;
            font-size: 13px;
            margin-top: 18
