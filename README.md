# 정혈대 여기있대

# 팀명<나양나nayangna팀>

- 구성원
    
    나유진(2012611) - 팀장
    
    양은수(2010429)
    

### ‼️산출물 주소 (여기있*대*)

깃허브 주소 : [](https://github.com/Sookmyung-Software-Hackathon/Team10_naYangna)https://github.com/Sookmyung-Software-Hackathon/Team10_naYangna 

배포 주소 : [https://nayangna.netlify.app/#/](https://nayangna.netlify.app/#/)

### ‼️분야

웹


## ❣️서비스 개요

---

우리가 일상생활에서 쉽게 ***연대***할 수 있는 일이 무엇이 있는가에 집중하였다. 사사로운 일이지만 ‘아 누군가 이 사실을 나에게 알려줬더라면 좋았을 텐데..’에서 시작한 아이디어이다.

누구나 한 번 쯤은 예기치 못하게 정혈 기간이 시작이 된 적이 있을 것이다. 교내 곳곳에는 중앙비대위의 사업으로 무상 정혈대함이 비치되어 있다. 

하지만 정혈대가 ***어디***에 있는지, 현재 ***몇 개***가 남아있는지를 확신할 수가 없다. 

본 서비스를 사용하면 이제 헛걸음은 그만!

**여기있*대***는 학우들이 편안히 비치함을 이용할 수 있도록 도와준다.

## ❣️서비스 목적

---

- 갑작스레 맞이하게 된 그날.. 급히 정혈대가 필요한 당신에게 어디에 얼만큼 정혈대가 있는지 손쉽고 가장 빠르게  알 수 있는 방법을 제공한다.
    - 교내에 비치된 정혈대의 위치를 안내한다.
    - 위치마다 게시판을 두어 현재 몇 개의 정혈대가 남아있는지 실시간으로 공유한다.
- 비치된 정혈대가 모두 소비 됐을 때 보충이 필요함을 빠르게 알릴 수 있다.
- 모두가 가지고 있는 바로 그 마음, 정혈대가 없는 사람을 봤을 때 도와주고 싶은 마음을 본 서비스로 표현할 수 있다.

## ❣️핵심 기술 및 주요 기능

---

**핵심 기술** : React, Firebase

주요 기능 

- 지도 상의 핀을 선택하면 해당 건물에 있는 비치함의 **세부위치**와 정혈대의 **개수**가 표시된다.
- 홈 화면에서 현재 정혈대가 **존재**하는 교내 건물들을 한눈에 확인할 수 있다.
- 건물을 선택하면 현재 위치한 정혈대의 **개수**와 마지막으로 업데이트 된 **날짜**를 확인할 수 있다.
- 댓글이나 업데이트 버튼을 통해 정혈대의 개수를 **실시간**으로 수정할 수 있다.
- **댓글**을 작성하여 실시간으로 현재 상황을 공유하며 **소통**할 수 있다.

## ❣️기대 효과

---

무상 정혈대함의 대부분의 이용자가 본 서비스 **여기있*대***를 사용하게 된다면 현재 남아있는 정혈대의 개수의 정확도가 높아지기 때문에 정혈대가 필요할 때 쉽고 빠르게 위치를 안내 받고 사용할 수 있을 것이다.

## ‼️페이지 구성(시나리오)

---

**로그인** 

- 구글 소셜로그인

**홈**

- 지도 위의 12개의 핀
- 핀을 선택 시 해당 건물의 정혈대의 세부위치 & 정혈대의 개수 확인 가능
- 건물 옆에 현재 정혈대의 유무가 표시됨
- 건물의 이름을 누르면 해당 건물의 게시판으로 이동
- ‘비치된 생리대가 없다면?’ 버튼을 누르면 도움을 요청할 수 있는 페이지로 링크

**게시판**

- 다시 홈으로 이동 가능
- 업데이트 버튼을 누르면 정혈대(대형/중형) 개수를 입력하여 수정 가능 → 실시간으로 반영
- 댓글 작성하기 버튼을 누르면 선택사항으로 개수를 입력할 수 있고 자유롭게 댓글 작성 가능
- 실시간으로 댓글이 업데이트 됨
