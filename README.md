# ch02_html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>앵커 활용</title>
</head>
<body>
    <h3> a 태그를 클릭하면 해당 id를 가진 태그 위치로 이동해요</h3>
    <hr>
    <ul>
        <li><a href="#h3-1">h3-1</li>
            <li><a href="#h3-2"><h3-2></li>
                <li><a href="#h3-3"><h3-3></li>
    </ul>
    
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <tittle>a tag</tittle>
   </head>
   <body>
       <h3>하이퍼 링크를 위한 a tag
        <hr>
        <ul>
            <li>
                <a href="https://www.naver.com"target="_blank">네이버로 이동</a>
            </li>
            <li>
                <a href="https://www.google.com">구글로 이동</a>
            </li>
            <li>
                <a href="img/NXDTM6RH5VQNT6EJSRVCFOMPCY.avif" download="download">
                    <img src="img/수달.htm"width="200px" alt="">
                </a>
            </li>
        </ul>
       </h3>
   </body>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>video 태그서용</title>
</head>
<body>
    <h3> AI관련 뉴스</h3>
    <hr>
    <!-- aoutoplay 자동실행 (웹 정책으로 자동샐행은 음소거 상태에서)-->
    <!--loop는 무한반복(없을경우는 1번실행)-->
    <video src="ai.mp4" width="200px" autoplay loop muted ></video>
    
</body>
</html>
