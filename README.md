# MAP(Make a Page!)
**made by Group2 (김용민, 양선주, 정민성, 조윤나)**
## 구현하려고 한 것 (데스트탑 기준)

https://www.baemin.com/

1. 배달의 민족 메인페이지
2. 배달의 민족 네이버 블로그
3. 배달의 민족 페이스북
4. 배달의 민족 인스타그램
---
## 배달의 민족 메인페이지
---
## 배달의 민족 네이버 블로그
### Detail
- 색 : rgba()를 사용해 투명도를 조절, 한 태그에 <span> 태그를 사용하여 일부만 색을 변경, 글씨가 두꺼워야하는 곳은 font-weight: bold를 사용
- 배치 : <body>의 width를 제한해 element들이 그 안으로 들어오게 설정, <div> 태그를 사용해 구역을 나눠 필요한 부분만 flex display 적용, <table> 태그를 사용하여 element들을 배치
- 포인터 : 누를 수 있는 element에 커서를 가져다대면 cursor:pointer를 사용하여 커서가 손가락 모양으로 변하게 설정, 글씨들은 색이 변하거나 밑줄이 그어지게 함(text-decoration: underline)
- 링크 : 유튜브 버튼을 클릭하면 배달의 민족 유튜브로 넘어감(<button type="button" onClick="window.open('링크')">) -> 다른 탭에 열리게 함
