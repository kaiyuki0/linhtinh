# linhtinh

<!DOCTYPE html>
<html lang="en,vn">
<head>
    <meta charset="utf-8">
    <title>tic_tac</title>
    <style type="text/css">
        *{
            margin: 0;
            padding: 0;
            border: 0;
            text-decoration: 0;
            box-sizing: border-box;
        }

        a{
            text-decoration: none;
            color:#b2bec3;
        }

        a:hover{
            color: #adad90;
        }


        body{
            background-image: url(https://www.apple.com/ac/structured-data/images/open_graph_logo.png?201809210816);
            background-size: cover;
            background-position: center; 
            background-attachment: fixed;
        }
        /*ul*/
        ul#menu{
            margin-top: 30px;
            margin-bottom: 20px;
            text-align: center;
        }

        ul#menu li {
            display: inline-block;
            padding: 10px 20px;
            text-transform: uppercase;
        }

        #menu img{
             margin: 0px 15px -20px;

        }
        #menu img:hover{
            opacity: 0;
        }
        /*div*/
        div#clock{
            width: 337px;
            height: 400px;
            background: url(https://cdn.iphoneincanada.ca/wp-content/uploads/2015/04/IMickey-Mouse-Face-Apple-Watch.jpg)center no-repeat;
            background-size: 609px;
            border-radius: 65px;
            border: 1px solid black;
            margin: 401px 505px;
            position: relative;
        }

        div#clock div{
            position: absolute;
            margin: 50% 0;
        }
        /*div hours*/
        div#clock div#hours {
                width: 79px;
    height: 9px;
    margin-left: 131px;
    /* border: 1px solid red; */
    border-left: 52px solid red;
    transform: rotate(90deg);
        }

        div#clock:hover div#hours {
            transform: rotate(36000deg);
            transition: transform 360000s linear;
        }
        /*div minute*/
        div#clock div#minute {
            width: 197px;
            height: 7px;
            margin-left: 72px;
        /* border: 1px solid blue; */
            border-left: 111px solid blue;
            transform: rotate(90deg);
        }


        div#clock:hover div#minute {
            transform: rotate(3600deg);
            transition: transform 600s linear;
        }
        /*div seconds*/
        div#clock div#seconds {
            width: 196px;
            height: 4px;
            margin-left: 72px;
            border-left: 112px solid yellow;
          /*border: 1px solid yellow;*/
            transform: rotate(90deg);
        }


        div#clock:hover div#seconds {
            transform: rotate(36000000deg);
            transition: transform 600000s linear;
        }
    </style>
</head>
<body>
        <ul id="menu">
        <li><a href="#">Mac</a></li>
        <li><a href="#">Ipad</a></li>
            <a><img src="https://www.apple.com/ac/structured-data/images/open_graph_logo.png?201809210816" width="100px"/></a>
        <li><a href="#">Iphone</a></li>
        <li><a href="#">Watch</a></li>
        </ul>
    <div id="clock">
        <div id="hours"></div>
        <div id="minute"></div>
        <div id="seconds"></div>
    </div>

</body>
</html>
