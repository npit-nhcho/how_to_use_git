## 🙌 안녕하세요. NinePlus IT 조남현 선임 연구원입니다

- Github 사용이 익숙치 않으신 분들을 위한 사용법 연습 repo입니다.
- Github 계정, Github desktop이 있어야 합니다.
- Linux 환경 등이 익숙하지 않은 분들을 위해 GUI를 이용하는 방법으로 알려드립니다.

## 🙋‍♀️ 목차   

1. [❓ Git은 무엇인가?](#-git은-무엇인가)  
2. [🛠 Git 사용해보기](#-git-사용해보기)  
    - [1. 작업 공간 세팅](#1-작업-공간-세팅)  
    - [2. 파일 수정하고 변경사항 체크하기](#2-파일-수정하고-변경사항-체크하기)  
    - [3. Commit하기](#3-commit하기)  
    - [4. Push하기](#4-push하기)
    - [5. 주의사항](#5-주의사항)
    - [6. Others..](#5-Others..)

## ❓ Git은 무엇인가?   
- **Git**은 **<u>여러 파일에 대해 분산 버전 관리</u>** 하기 위해 사용합니다.   
- 설치 스크립트 등을 공식적으로 update 할 수 있고,  혹시 잘못 update한 사항이 있으면 roll-back이 가능합니다.

![image](https://github.com/user-attachments/assets/b0968ea0-577a-4651-9b3f-41d8698cd305)
<br>
[출처](https://inpa.tistory.com/entry/GIT-%E2%9A%A1%EF%B8%8F-%EA%B0%9C%EB%85%90-%EC%9B%90%EB%A6%AC-%EC%89%BD%EA%B2%8C%EC%9D%B4%ED%95%B4)
<br><br>

## 🛠 Git 사용해보기   
   
## 1. 작업 공간 세팅
![image](https://github.com/user-attachments/assets/58156a81-c26f-4fa7-9fbd-acd7397480bb)
<br>  
`File - Clone a repositoy`를 클릭하고, Clone 해올 Repo와 저장할 디렉토리를 선택합니다.  
<br> 
<br>

## 2. 파일 수정하고 변경사항 체크하기
그러면, 해당 디렉토리에 수정해야할 파일이 생겼을 것입니다.  
이제, 해당 파일을 열어 수정해준 뒤 ***Github desktop***으로 다시 돌아오면 다음과 같이 보일 것입니다.  

![image](https://github.com/user-attachments/assets/fba5f318-b26c-468f-9b09-9e2cd0642a4b)
<br>  
여러분의 수정사항에 맞게 - 되는 부분 혹은 + 된 부분이 생길 것입니다.  
<br> 
<br> 
## 3. Commit하기

좌하단에 버튼 위에 제목을 적어주시면 좋습니다.<br> 

![image](https://github.com/user-attachments/assets/79ca1eeb-cbf5-4d06-9c50-73f5cca087ae)


제목은, 버전 관리하게 될 때 빠르게 식별 가능하므로 **버전이나 변경사항** 등을 적어주시면 좋습니다.  
저는 간단하게 "조남현추가"로 적었습니다.
이제, 좌하단의 `Commit to main`을 눌러줍니다.  
<br> 
<br> 
## 4. Push하기
맨 처음 사진에서 보았듯이, 현재는 로컬에 변경사항을 저장한 것입니다.  
이제 원격 저장소인 Github에 Push 하기 위해  `Push origin`버튼을 눌러줍니다.
<br>
![image](https://github.com/user-attachments/assets/32ea141b-f440-4481-b8b2-6c05289d1caf)
<br>
<br>
자, 이제 모든 과정이 끝이 났습니다. 이제 Github에 가면 수정 사항이 바로 반영되어 있을 것입니다.

![image](https://github.com/user-attachments/assets/4607a740-9f98-4938-bd43-aa5345d7bd94)
<br> 
<br> 
## 5. 주의사항
일반적으로는 한 파일에 대해 팀원들이 동시에 작업할 일이 없을 것이라 생각됩니다만,  
행여 그런 일이 있다면 주의 사항이 있습니다.

### `누군가 먼저 작업을 완료하였다면, Pull을 먼저 한 뒤 Push 해야 합니다.`  

제가 생일을 적지 않은 파일에 누군가 생일을 먼저 적어버렸다면,  
그 파일을 먼저 받아오고 제 생일을 입력해야 할 것입니다.  
이 작업이 Pull 입니다. 아래 사진처럼 나올 것입니다.  

![image](https://github.com/user-attachments/assets/bd4c0151-6425-4c4a-b0c9-4353b45d687a)
<br> 
<br> 

이외에도, 동시 작업이 꼭 필요하다면,

### `반드시 수정할 구간을 명확하게 나눠서 수정하세요.`  
남이 수정하는 부분을 본인이 수정하면, merge 과정에서 오류가 납니다.  
해당 상황이 발생하면 수동으로 고쳐야 하기 때문에, 번거로우실겁니다.

## 6. Others..
**Linux** 환경 등에서 사용하기 위한 코드들은, 인터넷에 많이 나와 있습니다.  
다만, clone 등을 하시기 위해서는 ***ssh-key***를 발급받고 본인 계정에 등록하는 과정이 필요합니다.  
필요하신 분들은 [다음 블로그](https://k-sky.tistory.com/326)를 참고하여 진행해보시기 바랍니다.  

혹시 지원이 필요하신 분은 제게 메일 주시면 도와드리겠습니다.
감사합니다.
