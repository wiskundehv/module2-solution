<html>

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device=width, initial-scale=1">
    <title>Solution Responsive Layout week2</title>
    <style>
        h1 {
            text-align: center;
            margin-bottom: 50px;
            font-size: 50px;
        }

        .container1 {
            margin-top: 50px;
            margin-right: 5px;
            position: relative;

        }

        .container2 {
            margin-top: 50px;
            margin-right: 5px;
            position: relative;
            left: 2px;




        }

        .container3 {
            margin-top: 50px;
            margin-right: 5px;
            position: relative;
            left: 4px;


        }

        .box1 {
            border: 2px solid black;
            width: 33%;
            background: gray;
            color: ivory;
            overflow: none;
            float: left;
            box-sizing: border-box;

        }

        .box11 {
            border: 2px solid red;
            box-sizing: border-box;
            background: burlywood;
            color: black;
            font-size: 20px;
            font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
            overflow: none;
            width: 100px;
            text-align: center;
            padding: 5px;
            float: right;
            margin-top: 0px;
            position: relative;
        }

        .content1 {
            position: relative;
            margin-top: 50px;
            padding: 5px;
            font-size: 18px;

        }

        .box2 {
            border: 2px solid black;
            width: 33%;
            background: gray;
            color: ivory;
            overflow: none;
            float: left;
            box-sizing: border-box;

        }

        .box22 {

            border: 2px solid red;
            box-sizing: border-box;
            background: burlywood;
            color: black;
            font-size: 20px;
            font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
            overflow: none;
            width: 100px;
            text-align: center;
            padding: 5px;
            float: right;
            margin-top: 0px;
            position: relative;
        }

        .content2 {
            position: relative;
            margin-top: 50px;
            padding: 5px;
            font-size: 18px;

        }

        .box3 {
            border: 2px solid black;
            width: 33%;
            background: gray;
            color: ivory;
            overflow: none;
            float: left;
            box-sizing: border-box;


        }

        .box33 {

            border: 2px solid red;
            box-sizing: border-box;
            background: burlywood;
            color: black;
            font-size: 20px;
            font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
            overflow: none;
            width: 100px;
            text-align: center;
            padding: 5px;
            float: right;
            margin-top: 0px;
            position: relative;
        }

        .content3 {
            position: relative;
            margin-top: 50px;
            padding: 5px;
            font-size: 18px;

        }


        @media(min-width:992px) {
            .box1 {
                width: 33%;
            }

            .box2 {
                width: 33%;

            }

            .box3 {
                width: 33%;
            }


        }



        @media(min-width:768px) and (max-width:991px) {
            .box1 {
                width: 50%;
            }

            .box2 {
                width: 50%;
            }

            .box3 {
                width: 100%;
                margin-right: 0px;
                margin-top: 20px;
            }


        }


        @media(max-width:767px) {
            .box1 {
                width: 100%;
                margin-top: 20px;
            }

            .box2 {
                width: 100%;
                margin-top: 20px;
            }

            .box3 {
                width: 100%;
                margin-top: 20px;
                left: 20px;
            }

        }
    </style>

</head>

<body>
    <h1> Our Menu</h1>
    <div class="container1">
        <div class="box1">
            <p class="box11">Chicken</p>
            <p class="content1">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Fugiat vitae quisquam quasi
                soluta sequi illum consectetur, quos id maiores quae explicabo repellat hic asperiores amet dignissimos
                quia placeat alias consequatur?</p>
        </div>
    </div>
    <div class="container2">
        <div class="box2">
            <p class="box22">Beef</p>
            <p class="content2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Illo corrupti similique atque
                suscipit sunt assumenda laudantium temporibus ad eum at odio nemo earum tempora illum, consequuntur
                harum ipsa quos aliquid?</p>


        </div>
    </div>

    <div class="container3">
        <div class="box3">
            <p class="box33">Sushi</p>
            <p class="content3">Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Quae officia animi velit necessitatibus dicta est cumque placeat eaque vitae, hic provident expedita
                dolor, nobis aliquid autem aliquam voluptates accusamus eum.</p>
        </div>
    </div>
</body>

</html>
