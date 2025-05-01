<!DOCTYPE html>
<html lang="ko">
    <head>
        <meta charset="utp-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>CSS 실습</title>
        <style>
            .box {
                height: 45px;
                border: 3px solid blue;
                box-sizing: border-box;
                display: flex;
                align-items: center;
                font-size: 20px;
            }
            h1 {color:green}
            .highlight{color:red}
            #special{color:yellow!important}
            .content {
                width: 50%;
                font-size: 1.5em;
                margin: 20px
            }
        </style>
    </head>
    <body>
        <h1 class="highlight">박스 모델 실습</h1>
        <h2 id="special">우선순위 실습</h2>
        <div class="box content">
            &nbsp이곳은 박스 모델이 적용된 콘텐츠입니다.
        </div>
    </body>
</html>
