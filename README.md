<!doctype html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="Generator" content="EditPlus®">
    <meta name="Author" content="">
    <meta name="Keywords" content="">
    <meta name="Description" content="">
    <title>Document</title>
    <style>
        div{
            background-color: #000;
            width: 100px;
            height: 100px;
            margin: 0 auto;
        }
    </style>
</head>
<body>
    <div id="wrap"></div>
    <script>
        var wrap=document.getElementById("wrap");
        var ua = navigator.userAgent.toLowerCase();
        if (ua.match(/MicroMessenger/i) == "micromessenger") {
            wrap.style.display="none";
        }else{
        }
    </script>
</body>
</html>
