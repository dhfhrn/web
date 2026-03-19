# web

<!DOCTYPE html>
<html>
    <head>
        <title>HTML 기본 구조</title>
        <meta charset="UTF-8">
        <meta authors="임순범 박희민">
    </head>
    </body>

    <p>특수문자는 &amp;이름; 형식으로 표기<br>
    &nbsp;- 예, 공백 &lt; &gt; &quot; &amp; (특수문자 이름: nbsp, lt, gt, quot, amp)<br>
    &nbsp;- 예, &#169; &#x00a2; &#x00a3; &#x00a5; (특수문자 코드: #169; #x00a2; #x00a3; #x00a5;)</p>
                <!-- 설명문은 이렇게 작성-->
    </body>
<html>

<h1>&lt;H1&gt; 헤드라인 제목 1호</h1>
<h2>&lt;H2&gt; 헤드라인 제목 2호</h2>
<h3>&lt;H3&gt; 헤드라인 제목 3호</h3>
<h4>&lt;H4&gt; 헤드라인 제목 4호</h4>
<h5>&lt;H5&gt; 헤드라인 제목 5호</h5>
<h6>&lt;H6&gt; 헤드라인 제목 6호</h6>
<p>단락은 &lt;p&gt; 요소로 표현한다.</p>
<p>&lt;p&gt;요소는 &nbsp; 단락이 끝나면 구분을 위하여 줄간격을 띄우지만, <br>
단순 줄바꿈인 &lt;br&gt; 요소는&nbsp;줄간격을 띄우지 않는다.</p>

<h3>가로줄(Horizontal Line) &lt;hr&gt; 요소</h3>
<p>&nbsp;가로줄은 &lt;hr&gt;요소를 이용</p>
<hr />&nbsp;자동으로 줄 바뀐다
<h3>형식 유지 &lt;pre&gt; 요소</h3>
<pre>&nbsp; p r e 요 소 는 공백문자를 
    입력한      그대로
            화면에      출력한다.</pre>
<h3>단락인용 &lt;blockquote&gt;&nbsp;요소</h3>
<blockquote>
    <p>다른 글의 내용을 인용하여 적을 때 사용한다. <br>
       인용된 내용은 화면에서 들여쓰기를 한다.</p>
</blockquote>

<h2>다양한 텍스트 표현</h2>
<p>텍스트의 성격을 지정해 주는 em요소로 <em>강조(em)</em>,<strong>강한 강조(strong)</strong><mark>하이라이트(mark)</mark>,<small>작은글자(small)</small>,<sub>아래첨자(sub)</sub>,<sup>위첨자(sup)</sup>를 표현할 수 있다.</p>
<p><strong>저자</strong>: 최윤설, 한탁돈, 임순범</p>
<p><em>컴퓨터와 IT기술의 이해</em>는 <mark>IT기술의 전반</mark>에 대해 포괄적으로 이해하고, 특히<small>우리사회의 각 영역에서의</small> 활용과 미치는 영향을 이해하기 위해 <strong>매우 적절한 교재가 될 것이다.</strong></p>

<h2>과목별 참고도서 목록</h2>
<ul>
    <li>IT기술의 이해 </li>
    <ol>
        <li>최윤철, 임승범, 한탁돈, 공저, 컴퓨터와 IT 기술의 이해</li>
        <li>D. Morley, C. parker, Understanding Computers
        15th Ed.</li>
        <li>G. shelly, M. Vermaat, Discovering Computers</li>
    </ol>
    <li>웹프로그래밍</li>
    <ol>
        <li>최윤철, 임승범, 한탁돈, 공저, HTML5 웹프로그래밍 입문</li>
        <li>최윤철, 임순범 공저, 소셜미디어 시대의 인터넷활용</li>
        <li>B. McLaughlin, What Is HTML5?</li>
    </ol>
</ul>
<h2>지정도서</h2>
<dl>
    <dt>지정도서 서비스란?</dt>
    <dd>수업에 필요한 주교재 및 참고문헌 등의 필수도서를 도서관 1층
        대출/지정도서실에서 별도로 비치하여 관리하는 제도</dd>
    <dt>신청기간</dt>
    <dd>매년 1월과 6월 둘째 주 학교 홈페이지에 공지</dd>
</dl>

<h3>기본적인 표의 표현</h3>
<table border="1">
    <tr>
        <th>책제목</th> <th>저자</th> <th>출판사</th>
    </tr>
    <tr>
        <td>HTML5 웹푸로그래밍 입문</td> <td>임순범, 박희민</td> <td>생능</td>
    </tr>
    <tr>
        <td>소셜미디어 시대의 인터넷활용</td> <td>B. McLaughlin</td> <td>O'Reilly</td>
    </tr>
</table>
