# web1

<!DOCTYPE html>
<html>
<head>
    <title>layout01</title>
    <style>
    
        .wrap{
            width: 1092px;
            margin: 0 auto;
        }
        .first{
            margin-bottom: 17px;
        }
        .first:after{
            content: '';
            display: block;
            clear: both;
        }
        .first div{
            float: left;
            margin-right: 17px;
        }
        .first div:last-child{
            margin-right: 0;
        }
        .box{
            width: 260px;
            height:260px;
            background-color: cyan;
        }
        
        .box_v{
            width: 538px;
            height: 260px;
            background-color: cyan;
        }
        *************************
        .second{}
        .second:after{
            content: '';
            display: block;
            clear: both;
        }
        .second>div{
            float: left;
            margin-right: 17px;
        }
        .second .box_h{
            margin-right: 0;
            width: 260px;
            height: 538px;
            background-color: cyan;
        }
        
        .second div div:first-child{
            margin-bottom: 17px;
        }
    </style>
</head>
    
<body>
    <div class="wrap">
        <div class="first">
            <div class="box_v"></div>
            <div class="box"></div>
            <div class="box"></div>
        </div>
        <div class="second">
            <div class="sec_in">
                <div class="box"></div>
                <div class="box"></div>
            </div>
            <div class="sec_in">
                <div class="box"></div>
                <div class="box"></div>
            </div>
            <div class="sec_in">
                <div class="box"></div>
                <div class="box"></div>
            </div>
            <div class="box_h"></div>
        </div>
    </div>
</body>
</html>
