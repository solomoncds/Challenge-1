
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jessica Randall</title>
</head>
<body style="font-family: url('./assets/fonts/static/Inter-Bold.ttf');">
    <div class="maincontent">
        <div class="photo">
            <img src="assets/images/avatar-jessica.jpeg" alt="Img Must Exist" >
        </div>

        <div class="main-intro">
            <h1>Jessica Randall</h1>
            <h2>London, United Kingdom</h2>
        </div>

        <div class="main-bio">
            <p>"Front-end Developer and avid reader."</p>
        </div>

        <div class="skillsets">
            <p>Git-Hub</p>
            <p>Front-End Mentor</p>
            <p>Linked-in</p>
            <p>Twitter</p>
            <p>Instagram</p>
        </div>
    </div>


 <style>
    
    *{margin: 0;}
    html,body{width: 100vw;height: 100vh;overflow-x: hidden; background-color: #000; display: flex; justify-content: center; align-items: center; 
    }

    .maincontent{
        display: flex;
        flex-direction: column;
        gap: 18px;
        align-items: center;
        margin-top: 30px;
        background-color: #1b1b1b;
        border-radius: 20px;
        width: 350px;
        height: 560px;
        padding: 20px;
        box-shadow: 2px 12px 13px  #411102;
    }

    img{
        border-radius: 50%;
        width: 110px;
        height: auto;
    }

    .main-intro h1{
        color: #fff;
        font-size: 26px;
        text-align: center;
    }

    .main-intro h2{
        color: #a8d63d;
        font-size: 14px;
        text-align: center;
        padding: 10px;
    }

    .main-bio{
        color: #969595;
        font-family: Inter;
        text-align: center;
    }

    .skillsets{
        display: flex;
        flex-direction: column;
        gap: 8px;
    }

    .skillsets p{
        background-color: #303030;
        color: #d6d6d6;
        font-size: 16px;
        border-radius: 5px;
        width: 300px;
        height: 30px;
        text-align: center;
        align-content: center;
        padding: 3px;
        transition: 0.3s ease;
        cursor: pointer;
    }

    .skillsets p:hover{
        background-color: #a8d63d;
        color: #000;
        transform: scale(1.02);

    }

    @media(max-width: 480px){
        .maincontent{
            width: 300px;
            height: 550px;
            gap: 10px;
        }

        img{
            width: 75px;
            height: auto;
        }

        .main-intro h1{
            font-size: 20px;
        }

        .main-intro h2{
            font-size: 11px;
            padding-bottom: 2px;
        }

        .main-bio{
            font-size: 13px;
        }

        .skillsets{
            gap: 6px;
        }

        .skillsets p{
            font-size: 15px;
            width: 250px;
            height: 35px;
            padding: 2px;
        }
    }
 </style>
</body>
</html>
