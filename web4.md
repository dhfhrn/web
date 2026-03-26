
<!DOCTYPE html>
<html>
    <body>
        <h3>도서 목록 페이지로 이동</h3>
        <p> 분야를 클릭하면 해당 도서 목록의 페이지로 이동합니다</br>
            전공 분야 위에 마우스를 올리면 해당 전공학과의 이름을 볼 수 있습니다.</p>
        <ul>
            <li> <a herf="https://www.wsu.ac.kr/main/index.jsp"title="컴퓨터 공학과"> 컴퓨터</a> </li>
            <li> <a href="link_internal.html" title="IT 공학과"> IT공학과</a></li>
            <li>전자공학</li>
            <li>인간공학</li>
        </ul>
    </body>
</html>

    <ol>
        <li>최윤철, 임순범, 한탁돈 공저, <a href="#book001"> 컴퓨터와 IT 기술의 이해</a></li>
        <li>D. Morley, C. Parker, <a href="#book002">Understanding Computers 15th Ed.</a></li>
        <li>G. Shelly, M. Vermaat, Discovering Computers</li>
    </ol></br>

    <h3>참고도서 소개</h2>
    <ol>
        <a id="book001"></a><li>컴퓨터와 IT기술의 이해</li>
        <table border="1"><tr><td>
            <ul> <li> 저자: 최윤철, 임순범, 한탇공 공저</li>
                <li> 출판사: 셍능출판사</li>
                <li>책소개: 급변하는 IT기술의 발전을 이해하고 다양한 사회영역과...</li>
            </ul>
        </td></tr></table>

        <a id="book002"></a><li>Understanding Computers, 15th Ed</li>
        <table border="1"><tr><td>
            <ul> <li>저자: D. Morley C. Parker</li>
                    <li>출판사: Cengage Learning</li>
                    <li>책소개: Thoroughly Updated for Latest Advances in Multimedia ...생략...</li>
            </ul>
        </td></tr></table>
    </ol>

    <figure>
        <table><tr>
        <td><img src="IT_intro.ipg" alt="책 표지" width="75"></td>
            <td>IT기술의 이해<br>최윤철, 임순범<br>생능출판사</td>
        </tr></table>
            <figcaption>[그림 1] 책 소개</figcaption>
    </figure>

<html>
<head>
    <title> 이미지 삽입하기 </title>
    <meta name="Copyright" content="임순범 외 저자">
</head>
<body>
    <h3> 참고도서 목록 </h3>
    <table border="1">
        <tr>
            <th>책제목</th> <th>저자</th> <th>출판사</th>
        </tr>
        <tr>
            <td>
                <figure>
                    <a href="사이트 주소">
                    <img sro="사진.ipg" alt="책표지" width="66" height="90"><br>
                    <figcaption>멀티미디어 배움터</figcaption></a>
                </figure>
            </td>
            <td> 최윤철, 임순범 공저</td>
            <td> 생능출판사 </td>
        </tr>
        <tr>
            <td>
                <figure>
                    <a href="사이트 주소">
                    <img src="사진.ipg" alt="책표지" width="66" height="90"><br>
                    <figcaption> 스티브 잡스</figcaption></a>
                </figure>
            </td>
            <td> 월터 아이슨 저</td>
            <td> 민음사 </td>
        </tr>
    </table>
</body>
</html>

<html>
<head>
    <title> 오디오 삽입하기 </title>
    <meta name="Copyright" content="임순범 외 저자">
</head>
<body>
    <audio controls src=".mp3" loop="3" autoplay></audio>
</body>
</html>

(.mp3파일이 3회 자동재생)

<html>
<head>
    <title> 비디오 삽입하기</title>
    <meta name="Copyright" content="임순범 외 저자">
</head>
<body>
    <video controls autoplay width="360" height="240" src=".mp4">
        비디오를 재생할 수 없습니다.
    </video>
</body>
</html>

<html>
<head><title>iframe사용 예제</title></head>
<body>
    <h3>과목별 참고도서 목록</h3>
    <ol>
        <li>멀티미디어 이해</li>
        <ul>
            <li><a href="주소" target="inreo">
                최윤현, 임순범 공저, 멀티미디어배움터 2.0</a></li>
            <li>T. V</li>
            <li></li>
        </ul>
        <li>인터넷 개론</li>
        <ul>
            <li>최윤현, 임순범 공저 인터넷배움터 2.0</li>
            <li><a href="주소" target="intro">
            </a>최윤현, 한탁돈, 임순범, 컴퓨터와 IT 기술의 이해</li>
        </ul>
    </ol>
    <dt>
        <dt>지정도서</dt>
        <dt>도서관에 여러권 비치되어 있으며 항상 열람 가능</dt>
    </dt>
    <p>
        <iframe src="" name="intro" width="420" height="400"></iframe>
    </p>
</body>
</html>
