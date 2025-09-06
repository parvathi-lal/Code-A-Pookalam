<!DOCTYPE html>
<html>
<head>
    <style>
        body{
            display: flex;
            justify-content: center;
            align-items: center;
            height: 1000px;
            margin: 0;
            background: transparent;
        }
        .circle
        {
            width: 800px;
            height: 800px;
            border: 50px solid orange;
            background: green;
            border-radius: 50%; 
            position: absolute;
        }
        .inner
        {
            width: 500px;
            height: 500px;
            border: 50px solid blue;
            background: red;
            border-radius: 50%;
            position: relative;

        }
        .outer
        {
            width: 200px;
            height: 200px;
            border: 50px solid green;
            background: transparent;
            border-radius: 50%;
            position: absolute; 
        }
    </style>
</head>
<body>
    <div class="circle"></div>
    <div class="inner"></div>
    <div class="outer"></div>
</body>
</html>