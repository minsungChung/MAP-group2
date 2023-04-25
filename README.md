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
![image](https://user-images.githubusercontent.com/116792686/234219203-6002fd3d-7dc0-42d5-aed0-cb10b656ea80.png)
### Detail
- meta 정보 : title, h1, meta description 등을 추가하여 SEO를 고려함
- 색 : rgba()를 사용해 투명도를 조절, 한 태그에 span 태그를 사용하여 일부만 색을 변경, 글씨가 두꺼워야하는 곳은 font-weight: bold를 사용
- 배치 : body의 width를 제한해 element들이 그 안으로 들어오게 설정, div 태그를 사용해 구역을 나눠 필요한 부분만 flex display 적용, table 태그를 사용하여 element들을 배치
- 포인터 : 누를 수 있는 element에 커서를 가져다대면 cursor:pointer를 사용하여 커서가 손가락 모양으로 변하게 설정, 글씨들은 색이 변하거나 밑줄이 그어지게 함(text-decoration: underline)
- 링크 : 유튜브 버튼을 클릭하면 배달의 민족 유튜브로 넘어감(button type="button" onClick="window.open('링크')") -> 다른 탭에 열리게 함
### Difficulty
- element들을 구조화시킬 때 어떤 태그를 사용해서 구조화해야할지 어려웠음(왼쪽 바를 figure태그를 사용해 나눴는데 맞는지 모르겠음)
- 완전하게 효율적인 코드가 아닌듯함(inline style을 많이 사용함)
- element들의 크기를 맞추기가 어려웠음
---
## 배달의 민족 페이스북
---
## 배달의 민족 인스타그램
![image](https://user-images.githubusercontent.com/116792686/234239414-a607cc11-2e4e-4467-bc6e-aff2a76b138c.png)
### 기획의도
배달의민족 인스타그램 페이지를 구현하려고 했으나 데스크톱으로 접속이 불가하여 부득이하게
마스코트인 독고배달의 인스타그램을 상상해 보면서 구현했습니다.
### Detail
- shortcut icon을 사용하여 웹브라우저 탭에 이미지를 추가
- z-index를 사용하여 HTML 문서 상에서 먼저 나온 element를 나중에 나온 element보다 앞으로 나오게 함
- border-radius를 사용하여 프로필 이미지를 둥글게 처리
- transform: translateY(-2px)를 사용하여 커서를 댔을 때 눌리는 느낌을 줌
### 느낀 점
처음 해보는 작업이어서 많이 어려웠지만 팀원분들이 적극적으로 도와주셔서 구현할 수 있었습니다.

