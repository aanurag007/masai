<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        #b1{
            width: 100%;
            height: 70vh;
            background-color: green;
        }
        #b1>div:nth-of-type(1){
            width: 40%;
            height: 80%;
            background-color: white;
            position: relative;
            top: 50px;
            left: 55%;
        }
        #b1>div:nth-of-type(2){
            width: 100px;
            height: 100px;
            background-color: purple;
            position: relative;
            left: 100px;
            bottom: 100px;
        }
        #b1>div:nth-child(1)>div:nth-child(1){
            width: 100px;
            height: 100px;
            background-color: red;
            position: absolute;
            top: 100px;
            left: 60%;
        }
        #b1>div:nth-child(1)>div:nth-child(2){
            width: 100px;
            height: 100px;
            background-color: yellow;
            position: absolute;
            top: 200px;
            left: 60%;
        }
    </style>
</head>
<body>
    <div id="b1">
        <div>
            <div></div>
            <div></div>
        </div>
        <div></div>
    </div>
</body>
</html>
