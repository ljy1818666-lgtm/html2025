<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>quiz-2</title>
    <style>
        .con{
            width: 500px;
            border: 1px solid black;
            padding: 20px 40px;
            margin: 0 auto;
        }
        fieldset{
            margin-bottom: 15px;
        }
        ul{
            list-style: none;
        }
    </style>
</head>
<body>
    <div class="con">
        <h1>프런트엔드 개발자 지원서</h1>
        <p>HTML, CSS, 자바스크립트의 기술을 이해하고 실무 경험이 있는 분을 찾습니다.</p>
        <hr>
        <form action="">
                <legend><b>개인 정보</b></legend>
                <ul>
                    <li>
                        <label for="name">이름
                        <input type="text" name="name" id="name" placeholder="공백 없이 입력하세요">
                        </label>
                    </li>
                    <li>
                        <label for="phone">연락처
                        <input type="tel" name="phone" id="phone">
                        </label>
                    </li>
                </ul>
                <legend><b>지원 분야</b></legend>
                <ul>
                    <li>
                        <input type="radio" name="pub" id="pub">
                        <label for="pub">웹 퍼블리싱</label>
                    </li>
                    <li>
                        <input type="radio" name="app" id="app">
                        <label for="app">웹 애플리케이션 개발</label>
                    </li>
                    <li>
                        <input type="radio" name="co" id="co">
                        <label for="co">개발 환경 개선</label>
                    </li>
                </ul>
                <legend><b>지원 동기</b></legend> <br>
                <textarea name="memo" id="memo" cols="60" rows="5" placeholder="본사 지원 동기를 간략히 써 주세요."></textarea><br>
            <input type="submit" value="접수하기">
            <input type="reset" value="다시 쓰기">
        </form>
    </div>
</body>
</html>
