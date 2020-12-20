<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>2020Christmas</title>

    <link rel="shortcut icon"
        href="https://postfiles.pstatic.net/MjAyMDEyMjBfMzAg/MDAxNjA4NDA0NTg2NDky.kV8x9y8Kx_3C8r0SXHuPl6Rdspx5KmeS0UATMjcP9H4g.8ubHbcb-PPLR2KxWLTonsKA13ifXiopQA1uEBHoAmuAg.JPEG.tosio_lava/IMG_7386.jpg?type=w773">

    <meta property="og:image"
        content="https://www.christmastreeassociation.org/wp-content/uploads/2016/06/multiple-christmas-trees-in-one-household-800x400.jpg">
    <meta property="og:title" content="Merry Christmas!">
    <meta property="og:description" content="christmas card from Hannah">

    <script src="https://s3.ap-northeast-2.amazonaws.com/materials.spartacodingclub.kr/xmas/snow.js"></script>

    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Nanum+Pen+Script&display=swap" rel="stylesheet">

    <style>
        * {
            font-family: 'Nanum Pen Script', cursive;
        }

        body {
            background-image: url('https://cdn.pixabay.com/photo/2017/01/05/11/24/christmas-tree-1954838__480.jpg');
            background-size: cover;
        }

        .envelope {
            width: 330px;
            height: 206px;

            background-image: url('https://postfiles.pstatic.net/MjAyMDEyMjBfMTYg/MDAxNjA4NDI0NzAzODUz.lNP9tNp80jD_gjCmf4IpBpmtsBC_gY06da1nlerskTkg.fwmm9FbIfpXS-JbZmaJi-u-O3vgcqX1ssnaforHmCVMg.JPEG.tosio_lava/IMG_7397.JPG?type=w773');
            background-size: cover;
            background-position: center;

            margin: 200px auto 0px auto;

            box-shadow: 0px 0px 10px 0px rgb(155, 111, 82);
            border-radius: 10px;

            cursor: pointer;
        }

        .envelope-msg {
            color: white;
            text-align: center;
            font-size: 40px;
        }

        .letter-close {
            display: block;
        }

        .letter-open {
            display: none;
        }

        .picture {
            background-color: white;
            width: 200px;
            height: 200px;

            background-image: url('https://media3.giphy.com/media/9zZKj6eRPrHDFL02mw/giphy.gif?cid=ecf05e47axpb5ke2v9lt72l1ur8nkyndf8sbdemp8jnmxtdb&rid=giphy.gif');
            background-size: cover;
            background-position: center;

            margin: 80px auto 0px auto;

            border-radius: 100px;

            border: 5px solid white;
            box-shadow: 0px 0px 10px 0px white;
        }

        h1 {
            color: white;
            text-align: center;

            margin-top: 25px;
            margin-bottom: 25px;
        }

        .messagebox {
            background-color: ivory;

            width: 400px;
            margin: auto;

            color: rgb(114, 63, 40);
            padding: 25px;
            font-size: 20px;
            line-height: 25px;

            box-shadow: 0px 0px 10px 0px white;

        }

        .from {
            text-align: right;
            margin-bottom: 0px;
        }

        @media screen and (max-width: 760px) {
            .messagebox {
                width: 300px;
                padding: 20px;
                line-height: 20px;
            }

            .picture {
                background-color: white;
                width: 150px;
                height: 150px;
                margin: 50px auto 0px auto;
            }

            h1 {
                font-size: 28px;
            }

            .envelope {
                width: 250px;
                height: 155px;
                margin: 150px auto 0px auto;
            }
        }
    </style>

    <script>

        function open_letter() {
            document.getElementsByClassName("letter-close")[0].style.display = 'none'
            document.getElementsByClassName("letter-open")[0].style.display = 'block'
        }

        function go_rtan() {
            alert('You got me! Merry Chirstmas!')
            window.location.href = 'https://youtu.be/yXQViqx6GMY'
        }

    </script>

</head>

<body>
    <div class="letter-close">
        <div class="envelope" onclick="open_letter()"></div>
        <h2 class="envelope-msg">Open it Please♡</h2>
    </div>

    <div class="letter-open">
        <div class="picture" onclick="go_rtan()"></div>

        <h1>Happy Christmas!</h1>

        <div class="messagebox">
            Hello My love <br />
            This is Hannah <br />
            Thank you for being with me this year, I know we've been through lots of hard thime, but still my 2020 was
            awsome with you. <br />
            And I want you to know that. <br />
            I am learning this for you so maybe we can make something together! <br />
            Merry christmas and Love you! <br />
            <p class="from">2020.12.19 <br /> From. Hannah</p>
        </div>
    </div>


</body>
</html>
