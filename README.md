# HTML과 CSS기초
## HTML

1. 기본구조
```html
<!DOCTYPE html>
<html lang="ko-KR">
  <head>
    <meta charset="UTF-8">
    <TItle>문서 제목</TItle>
    <body>
      HTML의 기본 구조 관련 명령어에 대해 학습 했습니다.
</body>
</head>
</html>
```
---
2. 제목관련 요소


```html
 <h1>대제목</h1>
 <h2>중제목</h2>
 <h3>소제목</h3>

```
> h1 요소부터 h6 요소까지 총 6 단계를 사용할 수 있으며, 중간에 단계를 건너 뛰어서 제목을 제공하여서는 안된다.

---
3. 텍스트 관련 요소
   
* 굵게/기울임꼴 (b, i)
* 강한 강조와 강조 (strong, em)
* 줄바꿈 및 수평선(br, hr)
* 인용 (blockquote, q)
* 약어와 머릿글자 (abbr)
* 주소 (address)
* 특수문자 (예 - 공백문자)

---
4. 목록 관련 요소
  
* 비순서형 목록(ul, li)
* 순서형 목록(ol, li)
* 정의형 목록(dl, dt, dd)

---
5. 하이퍼링크와 이미지

```html
<ul>
    <li><a href="http://samsungchildedu.multicampus.com/">멀티캠퍼스</a></li>
    <li><a href="https://www.facebook.com/multicampusHRD/" title="멀티캠퍼스" target="_blank">페이스북</a></li>
    <li><a href="./04.list.html"">목록 요소</a></li>
    <li><a href="#heading2">이미지 제목으로 이동</a></li>
  </ul>
<p>
  <img src="./assets/logo.gif" alt="From A To Zucchini" width="458" height="348">
  </p>

```
* [멀티캠퍼스](http://samsungchildedu.multicampus.com/)
* ![From A to Zucchini](./html/assets/logo.gif)

---
6. 테이블

* 테이블 영역 (table)
* 테이블 행 (tr)
* 제목 셀(th)
   + scope="col" (열 제목)
   + scope="row" (행 제목)
* 내용 셀(td)
   + 행 병합 (rowspan)
   + 열 병합 (colspan)

```html
<table border="1">

    <tr>
      <th scope="col">구분</th>
      <th scope="col">토요일</th>
      <th scope="col">일요일</th>
      </tr>
      <tr>
        <th scope="row">티켓 판매</th>
                <td>120</td>
        <td>135</td>
        </tr>
        <th scope="row">총 매출</th>
        <td>$600</td>
        <td>$675</td>
        </th>
  </table>

```
---
7. 폼 관련 요소

* 폼 그룹 (form)
   + action (서버 URL)
   + methos (GET 또는 POST)

* 연관성 있는 서식의 묶음 (Fieldset)
* 서식의 묶음의 성격을 명시 (legend)
* 폼 서식(컨트롤) (input, select , textarea)
* 전송 버튼 (button)