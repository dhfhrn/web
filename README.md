<!DOCTYPE html>
<html>
    <head>
        <title> FORM 입력 예제 </title>
        <meta name="Copyright" content="임순범 외 저자">
    </head>
<body>
    <h3> 다양한 입력 폼</h3>
    <form method="get" action="application.js">
        성명: <input type="text" name="person"/><br>
        성별:<input type="radio" name="sex" value="male"/> 남성
            <input type="radio" name="sex" value="female"/> 여성
        직업:<select name="job" size="1">
                <option>학생</option> <option>회사원</option>
                <option>공무원</option> <option> 기타</option>
            </select>
        <p>
        구입희망분야(복수선택 가능)<br>
        -분야: <input type="checkbox" name="books" value="computer"/> 컴퓨터
            <input type="checkbox" name="books" value="economy"/> 경제
            <input type="checkbox" name="books" value="common"/> 상식<br>
        비고: <br>
        <textarea name="comments" rows="4" cols="40"/></textarea>
        </p>
        <hr>
            <input type="submit" value="신청"/>
            <input type="reset" value="취소"/>
    </form>
</body>
</html>

<!DOCTYPE html>
<html>
    <head>
        <title> 텍스트 입력 예제 </title>
        <meta name="Copyright" content="임순범 외 저자">
    </head>
    <body>
        <h3> 문자열, 암호 입력 및 텍스트 영역</h3>
        <form method="post" action="form_app.js">
            아이디: &nbsp; <input type="text" name="id" value="...ID입력..."> <br>
            비밀번호: <input type="password" name="pwd"
        <p>요청사항: <br>
            <textarea name="comment" cols="40" rows="5"> 전달하실 내용을 적으세요:
            </textarea>
        </form>
    </body>
</html>

<!DOCTYPE html>
<html>
    <head>
        <title> FORM 입력 예제 </title>
        <meta name="Copyright" content="임순범 외 저자">
    </head>
<body>
    <h3>다양한 입력 폼</h3>
    <form method="get" action="application.js">
        회원여부: <input type="radio" name="member" value="checked"/>회원
        <input type="radio" name="member" value="no"/>비회원<br>
        성별: <input type="radio" name="sex" value="female"/>남성
        <input type="radio" name="sex" value="female"/>여성

    </form>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
    <title> 버튼 예제 </title>
    <meta name="Copyright" content="임순범 외 저자">
</head>
<body>
    <h3>버튼 입력</h3>
    <form method="get" action="form_app.js">
        <p>취미(중복선택):
            <input type="checkbox" name="hobby" value="read"/>독서
            <input type="checkbox" name="hobby" value="movie" checked/>영화
            <input type="checkbox" name="hobby" value="music"/>음악
            <input type="checkbox" name="hobby" value="sports"/>스포츠
        </p>
        직업:
        <select name="job" size="4" multiple>
            <option value="student" selected>학생</option>
            <option value="company">회사원</option>
            <option value="teacher">교사</option>
            <option value="sales">자영업</option>
            <option value="others">기타</option>
        </select>

        <hr>
        <input type="submit" value="전송하기"/> &nbsp;
        <input type="reset" value="초기화"/> &nbsp;
        <input type="button" value="확인하기" onclick="alert('입력값 확인')"/> &nbsp;
        <input type="image" src="submit.gif" alt="전송 버튼"/> &nbsp;
    </form>
</body>
</html>

<!DOCTYPE html>
<html>
    <head>
        <title> 파일 입력 예제 </title>
        <meta name="Copyright" content="임순범 외 저자">
    </head>
    <body>
        <h3>기타 입력: 파일 및 숨김</h3>
        <form method="get" action="form_app.js">
            <input type="hidden" name="userIP" value="1234">
            파일 업로드하기
            <br>
            <p><input type="file" name="myfile"/> </p>
            <hr>
            <input type="submit" value="전송"/>
            <input type="reset" value="취소"/>
        </form>
    </body>
</html>

<!DOCTYPE html>
<html>
    <head>
        <title> 텍스트 라벨 예제 </title>
        <meta name="Copyright" content="임순범 외 저자">
    </head>
    <body>
        <p>텍스트 라벨을 클릭해도 됩니다.<p>
        <form method="get" action="form_app.js">
            성별: &nbsp;
            <label for="male">남성</label>
            <input type="radio" name="sex" id="male" value="male">
            <label for="female">여성</label>
            <input type="radio" name="sex" id="female" value="female">
            <br>
            <hr>
            <input type="submit" value="전송"/>
            <input type="reset" value="취소"/>
        </form>
    </body>
</html>

<!DOCTYPE html>
<html>
    <head>
        <title> 그룹핑 예제 </title>
        <meta name="Copyright" content="임순범 외 저자">
    </head>
    <body>
        <h3>도서 검색</h3>
        <form method="post" action="form_app.js">
            <fieldset>
                <legend>로그인</legend>
                <label for="user_id">아이디: </label>
                <input type="text" name="id" size="20" id="user_id"> <br>
                <label for="user_pw">비밀번호: </label>
                <input type="password" name="pw" size="20" id="user_pw">
            </fieldset>
            <br>
            <fieldset>
                <legend>통합 검색</legend>
                <label for="book_name">도서명: </label>
                <input type="text" name="book_search" size="50" id="book_name">
                <br>검색범위:
                <input type="radio" name="s_type" value="keyword" id="keyword">
                <label for="keyword">키워드</label>
                <input type="radio" name="s_type" value="content" id="content">
                <label for="content">본문 내용</label>
                <br>자료유형:
                <input type="checkbox" name="d_type" value="all">전체
                <input type="checkbox" name="d_type" value="book">단행본
                <input type="checkbox" name="d_type" value="paper">학술지
                <input type="checkbox" name="d_type" value="non_book">비도서<br>
            </fieldset>
            <br>
            <button type="submit">검색</button>
            <button type="reset">지우기</button>
        </form>
    </body>
</html>

<!DOCTYPE html>
<html>
    <head>
        <title> 텍스트 라벨 예제 </title>
        <meta name="Copyright" content="임순범 외 저자">
    </head>
    <body>
        <form>
            <p>Email: <input type="email"/><br>
            <p><input type="submit" value="전송"/>
            <p>URL: <input type="url" value="http://"/><br>
            <p><input type="submit" value="전송"/>
            <p>Tel: <input type="tel" placeholder="00*-000*-0000"
                pattern="[0-9]{2,3}-[0,9]{3,4}-[0,9]{4}" /><br>
            <p><input type="submit" value="전송" />
            <p>Search: <input type="search" placeholder="Search..."/> <br>
            <p><input type="submit" value="전송" />
        </form>
    </body>
</html>

<!DOCTYPE html>
<html>
    <head>
        <title> 날짜 입력 예제 </title>
        <meta name="Copyright" content="임순범 외 저자">
    </head>
    <body>
        <form method="get" action="form_app.js">
            <table width="500">
            <tr>
                <td>date (연-월-일)</td>
                <td>month (연도-월)</td>
                <td>week (연도-주)</td>
            </tr><tr>
                <td><input type="date"> </td>
                <td><input type="month"> </td>
                <td><input type="week"> </td>
            </tr>
            </table>
        </form>
    </body>
</html>
