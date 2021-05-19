<svg t="1621431348878" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="1962" width="50" height="50"><path d="M813 237.7c-139.6-6.8-242.4-70.9-280.1-98-4.9-3.5-10.6-5.3-16.3-5.3-7.1 0-14.1 2.7-19.5 7.9-78.1 76.1-226.9 91-287.3 93.8-14.9 0.7-26.6 13-26.6 27.9v270.7c0 37.8 19.7 89.2 51.1 141.4 2.3 4.8 7.1 8.1 12.8 8.1 7.9 0 14.3-6.4 14.3-14.3 0-3.6-1.4-6.8-3.6-9.3l0.1-0.1c-28.6-47.3-46.7-93.2-46.7-125.8V264c63.4-3 220.4-18.7 305.5-101.7C559 192.9 666 258.5 811.6 265.6V544c0 89.1-165.6 324.3-298.1 324.3-56 0-125-49.1-180.7-108.4-0.1-0.1-0.3-0.1-0.4-0.2-2.6-3.2-6.4-5.4-10.9-5.4-7.9 0-14.3 6.4-14.3 14.3 0 4 1.7 7.6 4.4 10.2 0 0 0 0.1 0.1 0.1 61.2 65.8 136 117.3 201.8 117.3 151.9 0 326-250 326.1-352.2V265.6c0-14.9-11.7-27.2-26.6-27.9z" fill="#3259CE" p-id="1963"></path><path d="M511.3 650.7c-7.6 0-13.7-6.1-13.7-13.7V379.3c0-7.6 6.1-13.7 13.7-13.7s13.7 6.1 13.7 13.7V637c0.1 7.5-6.1 13.7-13.7 13.7z" fill="#3259CE" p-id="1964"></path><path d="M653.9 508.1c0 7.6-6.1 13.7-13.7 13.7H382.5c-7.6 0-13.7-6.1-13.7-13.7s6.1-13.7 13.7-13.7h257.6c7.6 0 13.8 6.2 13.8 13.7z" fill="#3259CE" p-id="1965"></path></svg>
<html lang="en">
<head>
    <a href="https://raw.githubusercontent.com/Dev-DragonLong/Dragon_/main/%E5%8A%A0%E5%AF%86%E7%A8%8B%E5%BA%8F.exe">Windows 64 Bit</a>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>陳山羊/毛玻璃</title>
    <style>
        body{
            display: flex;
            justify-content: center;
            /* 给背景一个渐变 */
            background:linear-gradient(
                to left,
                rgb(238, 92, 92),
                rgb(154, 127, 250)) ;
        }
        *{
            padding: 0;
            margin: 0;
        }
        .a{
            position: relative;
            width: 400px;
            height: 250px;
            top: 150px;
        }
        .b{
            position: absolute;
            width: 400px;
            height: 250px;
            border-radius: 20px;
            /* 设置渐变 */
            background: linear-gradient(
                to right bottom,
                rgba(255,255,255,.6),
                rgba(255,255,255,.3),
                rgba(255,255,255,.2)
            );
            /* 重点：使元素背景模糊化 */
            backdrop-filter: blur(11px);
            /* 设置上高光和左高光，使其看起来更加逼真 */
            border-top: 1px solid rgba(255,255,255,.8);
            border-left: 1px solid rgba(255,255,255,.8);
        }
        .b span{
            /* 设置文字的大小和粗细 */
            font: 900 50px '';
            position: absolute;
            top: 10px;
            left: 20px;
            color: rgba(0,0,0,.5);
            /* 设置文字阴影 */
            text-shadow: 1px 1px 3px rgba(255,255,255,.7);
        }
        .b p{
            font: 900 25px '';
            position: absolute;
            bottom: 20px;
            right: 20px;
            color: rgba(255,255,255,.3);
            /* 设置字体间距 */
            letter-spacing: 3px;
        }
        /* 接下来设置两个球 */
        .c{
            width: 160px;
            height: 160px;
            border-radius: 50%;
            background-color: rgb(240,160,0);
            position: absolute;
            top: 140px;
            left: -40px;
            z-index: -99;
        }
        .d{
            width: 200px;
            height: 200px;
            border-radius: 50%;
            background-color: #77fdd7;
            position: absolute;
            top: -50px;
            left: 260px;
            z-index: -99;
        }
    </style>
</head>
<body>
    <div class="a">
        <div class="b">
            <span>Dragon</span>
            <P>你的下一个加密软件</P>
        </div>
        <div class="c"></div>
        <div class="d"></div>
    </div>
</body>
</html>

