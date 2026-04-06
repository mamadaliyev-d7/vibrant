<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>vibrant</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,200..1000;1,200..1000&family=Playwrite+IE:wght@100..400&family=Roboto:ital,wght@0,100..900;1,100..900&display=swap"
        rel="stylesheet">
    <link rel="icon" type="image/png" sizes="32x32" href="./images/logo.jpg">
    <link rel="icon" type="image/png" sizes="16x16" href="./images/logo.jpg">

    <style>
        * {

            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Nunito", sans-serif;
        }

        body {
            background-color: white;
        }

        main {
            display: flex;
            flex-direction: column;
            gap: 50px;
            background-image: url("./images/main.jpg");
            background-size: cover;

        }

        header {
            display: flex;
            justify-content: space-around;
            height: 50px;
            align-items: center;
            background-color: #8de7695b;
            color: white;
            text-shadow: 0px 0px 5px #000000d6;

        }

        p {
            display: inline-block;
            margin-left: 5px;

        }

        .container {
            display: flex;
            flex-direction: column;
            justify-content: space-around;
            gap: 30px;
            align-items: center;
            width: 500px;
            margin: 50px auto;
            color: white;


        }

        .container button {
            height: 50px;
            width: 120px;
            cursor: pointer;
            font-size: 15px;
            border-radius: 10px;
            border: none;
            background-color: #955cffc9;
            color: white;
            transition: 1.2s;
        }

        .container button:hover {
            background-color: #955cff;
            transform: scale(1.1);
            box-shadow: 0px 0px 10px #955cff;
        }

        .statistics {
            display: flex;
            margin: 10px 200px;
            flex-direction: column;
            background-color: rgba(0, 0, 0, 0.747);
            border-radius: 10px;
            padding: 20px 30px;
            color: white;
            align-items: center;


        }

        .nav {
            display: flex;
            gap: 20px;
            margin-left: 50px;
        }

        .main-card {
            display: flex;
            gap: 20px;
            width: 900px;
            margin: 20px auto;

        }

        .card-second1 {
            display: flex;
            background-color: rgba(0, 0, 0, 0.699);
            flex-direction: column;
            width: 600px;
            padding: 20px 20px;
            gap: 20px;
            border-radius: 10px;
            color: white;

        }

        .card-second {
            display: flex;
            background-color: rgba(89, 201, 54, 0.41);
            flex-direction: column;
            justify-content: space-around;
            width: 300px;
            padding: 20px 20px;
            border-radius: 10px;
            color: white;
            box-shadow: 0px 0px 10px rgba(89, 201, 54, 0.41);

        }

        /* MAIN 2  */
        .main2 {
            display: flex;

            gap: 50px;
            margin: 0px 200px;
            margin-top: 100px;
            align-items: center;
            justify-content: space-between;
        }

        .main2-left {
            display: flex;
            flex-direction: column;
            gap: 20px;
            width: 500px;
            /* color: white; */
        }

        .main2-right img {
            width: 500px;
        }

        /* MAIN 3 */
        .main3 {
            display: flex;
            gap: 50px;
            margin: 0px 200px;
            margin-top: 100px;
            align-items: center;
            justify-content: space-between;
        }

        .main3-left {
            display: flex;
            flex-direction: column;
            gap: 20px;
            width: 500px;
        }

        .main3-right img {
            width: 500px;
        }

        /* MAIN 4 */
        .main4 {
            display: flex;
            gap: 50px;
            margin: 0px 200px;
            margin-top: 100px;
            align-items: center;
            justify-content: space-between;
            background-image: url(./images/main4\ background.jpg);
            background-size: cover;
            border-radius: 10px;
            padding: 20px 30px;
            margin-top: 20px;
            height: 500px;
        }

        .main4-left {
            display: flex;
            flex-direction: column;
            gap: 20px;
            width: 500px;
            color: white;

        }

        .main4-right img {
            width: 500px;
            margin-bottom: -20px;
            margin-right: -30px;
            box-shadow: 0px 0px 10px #955cff;
            border-top-left-radius: 10px;
            border-bottom-left-radius: 10px;



        }

        .main4-left button {
            height: 50px;
            width: 120px;
            cursor: pointer;
            font-size: 15px;
            border-radius: 10px;
            border: none;
            background-color: #955cffc9;
            color: white;
            transition: 1.2s;
        }

        .main4-left button:hover {
            background-color: #955cff;
            transform: translatey(-5px);
            box-shadow: 0px 0px 10px #955cff;
        }

        /* GET READY  */
        .get-ready {
            display: flex;
            flex-direction: column;
            margin: 100px 200px;
            align-items: center;
        }

        .get-ready-container {
            display: flex;
            gap: 20px;
            margin-top: 30px;
            gap: 30px;
            width: 800px;
            justify-content: space-around;
        }

        .get-ready-card1 {
            display: flex;
            flex-direction: column;
            gap: 20px;
            width: 300px;
            padding: 20px 20px;
            border-radius: 10px;
            color: black;
            box-shadow: 0px 0px 10px #000000;
            align-items: center;
        }

        .get-ready-card1 button {
            height: 50px;
            width: 120px;
            cursor: pointer;
            font-size: 15px;
            border-radius: 10px;
            border: none;
            background-color: #955cffc9;
            color: white;
            transition: 1.2s;
        }

        .get-ready-card1 button:hover {
            background-color: #955cff;
            transform: translatey(-5px);
            box-shadow: 0px 0px 10px #955cff;
            text-shadow: 0px 0px 5px #000000d6;
        }

        .get-ready-card2 {
            display: flex;
            flex-direction: column;
            gap: 20px;
            width: 300px;
            padding: 20px 20px;
            border-radius: 10px;
            color: black;
            box-shadow: 0px 0px 10px #000000;
            align-items: center;
            background-image: url(./images/get\ ready\ background\ image.jpg);
            background-size: cover;
            color: white;

        }

        .get-ready-card2 button {
            height: 50px;
            width: 120px;
            cursor: pointer;
            font-size: 15px;
            border-radius: 10px;
            border: none;
            background-color: #955cffc9;
            color: white;
            transition: 1.2s;
        }

        .get-ready-card2 button:hover {
            background-color: #955cff;
            transform: translatey(-5px);
            box-shadow: 0px 0px 10px #955cff;
            text-shadow: 0px 0px 5px #000000d6;
        }

        .get-ready-card1 li,
        .get-ready-card2 li {
            list-style: none;
            text-align: left;
        }

        /* FOOTER  */
        footer {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 20px;
            background-color: black;
            color: white;
            padding-bottom: 20px;


        }

        footer img {
            width: 121px;
            margin: 20px auto;
        }

        .footer-text-area {
            display: flex;
            gap: 10px;

        }

        footer button {
            height: 40px;
            width: 80px;
            cursor: pointer;
            font-size: 15px;
            border-radius: 10px;
            border: none;
            background-color: #955cffc9;
            color: white;
            transition: 1.2s;
        }

        footer button:hover {
            background-color: #955cff;
            transform: scale(1.1);
            box-shadow: 0px 0px 10px #955cff;
            text-shadow: 0px 0px 5px #000000d6;
        }

        @media (max-width: 600px) {

            header {
                flex-direction: column;
                height: auto;
                padding: 10px;
                gap: 10px;
            }

            .container {
                width: 100%;
                padding: 0 15px;
                text-align: center;
            }

            .container h1 {
                font-size: 22px;
            }

            .statistics {
                margin: 10px;
                padding: 15px;
            }

            .nav {
                flex-wrap: wrap;
                justify-content: center;
                margin-left: 0;
            }

            .main-card {
                width: 100%;
            }

            .main2,
            .main3,
            .main4 {
                margin: 30px 10px;
            }

            .main4 {
                height: auto;
                padding: 20px;
            }

            .get-ready-container {
                width: 100%;
            }

            .get-ready-card1,
            .get-ready-card2 {
                width: 100%;
            }

            footer img {
                width: 80px;
            }

            .footer-text-area {
                flex-direction: column;
                width: 100%;
                padding: 0 10px;
            }

            textarea {
                width: 100%;
            }
        }
        @media (max-width: 1024px) {

    .statistics {
        margin: 20px;
    }

    .main-card {
        flex-direction: column;
        width: 100%;
        align-items: center;
    }

    .card-second1,
    .card-second {
        width: 100%;
    }

    .main2,
    .main3,
    .main4 {
        flex-direction: column;
        margin: 50px 20px;
        text-align: center;
    }

    .main2-left,
    .main3-left,
    .main4-left {
        width: 100%;
    }

    .main2-right img,
    .main3-right img,
    .main4-right img {
        width: 100%;
    }

    .get-ready {
        margin: 50px 20px;
    }

    .get-ready-container {
        flex-direction: column;
        width: 100%;
        align-items: center;
    }
}
    </style>
</head>

<body>
    <header><img src="./images/Frame.svg" alt="Logo">
        <div class="left-header">
            <p>Home</p>
            <p>FAQ</p>
            <p>Blog</p>
        </div>
    </header>
    <main>
        <div class="container">
            <h1>Open your first crypto wallet, right now!</h1>
            <p>Vibrant is the best software platform to easily capture user feed back for your brand and products.</p>
            <button>Buy Template</button>
        </div>
        <div class="statistics">
            <div class="nav">
                <h3>Dashboard</h3>
                <h3>Transactions</h3>
                <h3>Cards</h3>
                <h3>Settings</h3>
            </div>
            <div class="statistics-main">
                <h1>Today's Overview</h1>
                <div class="main-card">
                    <div class="card-second1">
                        <p>Total balance</p>
                        <h1>$13,289.00</h1>
                        <p>Last Update: 11 April 2022 01:00 PM</p>
                    </div>
                    <div class="card-second">
                        <p>Total Income</p>
                        <h1>$2,350.00</h1>
                        <p>+2.80%</p>
                    </div>
                    <div class="card-second">
                        <p>Total Outcome</p>
                        <h1>$5,600.00</h1>
                        <p>-1.30%</p>
                    </div>
                </div>
            </div>
        </div>
    </main>
    <div class="main2">
        <div class="main2-left">
            <h1>Check out your monthly summary with a glance.</h1>
            <p>Vivamus facilisis, neque sit amet venenatis euismod, neque viverra velit, sit amet vehicula sapien
                elit eget tortor.</p>
        </div>
        <div class="main2-right"><img src="./images/main2image.png" alt="Second Main Image"></div>

    </div>
    <div class="main3">
        <div class="main3-left">
            <h1>Group bills? No problem,<br>you can split it.</h1>
            <p>Vivamus facilisis, neque sit amet venenatis euismod, est neque viverra velit, sit amet vehicula sapien
                elit eget tortor.</p>
        </div>
        <div class="main3-right"><img src="./images/main3image.jpg" alt="Third Main Image"></div>
    </div>
    <div class="main4">
        <div class="main4-left">
            <h1>Download the app <br>and start today!</h1>
            <button> Buy Template</button>
            <p>*No credit card requires</p>
        </div>
        <div class="main4-right"><img src="./images/main4image.png" alt="image"></div>


    </div>
    <!-- GET READY ?  -->
    <div class="get-ready">
        <h1>Ready to get started ?</h1>
        <p>Choose a plan fits to your needs</p>
        <div class="get-ready-container">
            <div class="get-ready-card1">
                <h2>Personal</h2>
                <p>Best for brands that need designs on an ongoing basis.</p>
                <h1>$2.99</h1>
                <button>Try for free</button>
                <td>
                    <li>Request unlimited designs</li>
                    <li>Deliverables as you need</li>
                    <li>No limit on revisions</li>
                </td>
            </div>
            <div class="get-ready-card2">
                <h2>Business</h2>
                <p>Best for businesses that need more advanced features.</p>
                <h1>$9.99</h1>
                <button>Try for free</button>
                <td>
                    <li>Request unlimited designs</li>
                    <li>Deliverables as you need</li>
                    <li>No limit on revisions</li>
                    <li>No code needed</li>
                    <li>Individual help center</li>
                    <li>Your personal mentor</li>

                </td>
            </div>
        </div>
    </div>
    <!-- FOOTER  -->
    <footer>
        <img src="./images/Frame.svg" alt="">
        <p>Vibrant is a Framer template made for SaaS companies.</p>
        <div class="footer-text-area"><textarea name="" placeholder="Type" id=""></textarea><button> Send</button></div>
        <p>Made by d7</p>


    </footer>

</body>

</html>
