## Hi there 👋

## 📑 기술 스택
<img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=Kotlin&logoColor=white"> <img src="https://img.shields.io/badge/Android Studio-3DDC84?style=for-the-badge&logo=Android Studio&logoColor=white"> 
<img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=Figma&logoColor=white"> 
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white"> 

<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white"> <img src="https://img.shields.io/badge/Spring Security-6DB33F?style=for-the-badge&logo=Spring Security&logoColor=white"> <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/apache tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=white"> <img src="https://img.shields.io/badge/amazonaws-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"> 

### 기술 스택 선정 이유

- 습관 형성에 초점을 두는 서비스 특성에 맞게 어디서든 접근이 용이한 앱을 선택하였습니다.
- Native platform와 Cross platform 중 어떤 것을 사용할지 고민하였으나 Cross platform을 사용할시 윈도우, 리눅스, 맥 버전으로 세 번의 컴파일을 거치는 번거로움과 프로그램의 규모가 큰 경우에는 컴파일 시간도 그만큼 길어지는 단점을 가지므로 변동 사항이 생길 시 빠른 반영을 하기 위해 Native platform을 플랫폼으로 선택하였습니다.
- 구성원의 개발환경에 Window의 비율이 높기에 Android Studio로 개발환경을 선정하였습니다.
- 코틀린은 많은 기업들이 사용하는 추세이고 문법이 간결하며 사용성이 좋고 Null Safe 언어이며 기존 라이브러리와의 상호운용성이 뛰어나기에 개발 언어로 선택하였습니다.
- Retrofit2는 빠른 성능, 간단한 구현, 가독성, 동기/비동기의 쉬운 구현 등의 특성을 가지고 있기에 서버와의 통신 라이브러리로 선택하였습니다.
- 서버 개발 언어인 자바는 객체 지향 프로그래밍의 장점을 활용하여 서비스를 개발할 수 있으며 다양한 레퍼런스를 활용할 수 있고 보안 운영 측면에서 안정적이며, 라이브러리 관리 자동화, 버전 관리가 편리한 spring framework를 사용할 수 있다는 특징을 가집니다.
- JPA를 사용하여 데이터베이스에 접근할 예정이며, 관계형 데이터베이스와 객체 지향 언어를 연결 할 때 발생하는 불일치를 줄여 DBMS에 대한 종속성을 줄일 것입니다.
- 사용자 인증 방법으로 선택한 JWT 토큰은 Header와 Payload를 사용하여 signature를 생성합니다. 또한, 인증 정보에 대한 별도의 저장소가 필요 없고 토큰 기반으로 로그인 시스템에 접근 및 권한 공유가 가능하다는 특징을 가집니다.
- AWS에서 제공하는 RDS, S3를 사용하여 데이터베이스를 구축하고 EC2를 사용하여 서버를 배포할 것입니다.
- 데이터 관리는 Scale up, out이 간편하고 백업 기능이 편리한 RDS를 사용하여 텍스트 정보로 이루어진 데이터를 관리하고, 파일 서버의 역할을 할 수 있는 S3를 사용할 것입니다. 또한 RDS와 S3, Rest API를 사용하여 생성한 서버를 24시간 서비스하기 위해 EC2를 활용하여 서비스 배포를 진행할 것입니다.

## 📑 소프트웨어 아키텍처
<img width="503" alt="스크린샷 2022-10-13 오후 5 49 51" src="https://user-images.githubusercontent.com/84445210/195549538-f7cf83c3-20d0-4678-a95d-33a94739bc6b.png">

## 📑 주요기능 명세서
### 📎 기능 사항 ID
<img width="702" alt="스크린샷 2022-10-13 오후 5 56 47" src="https://user-images.githubusercontent.com/84445210/195551448-c82e44a7-12bc-4c77-91f2-e79c8cd2edf6.png">
<img width="702" alt="스크린샷 2022-10-13 오후 5 57 24" src="https://user-images.githubusercontent.com/84445210/195551579-f66853a2-bfc1-47c3-8370-872d5e5748c9.png">
<img width="704" alt="스크린샷 2022-10-13 오후 6 01 49" src="https://user-images.githubusercontent.com/84445210/195552701-a1772cb2-5c46-41ae-8a0f-25bf6ddd1751.png">
<img width="705" alt="스크린샷 2022-10-13 오후 6 00 13" src="https://user-images.githubusercontent.com/84445210/195552328-f9286b0a-d9ed-4f2a-979c-a6b5b8e3e6d7.png">
<img width="700" alt="스크린샷 2022-10-13 오후 5 59 01" src="https://user-images.githubusercontent.com/84445210/195551987-400cdc5d-8ba5-43c8-bbae-7428af46d2e3.png">

### 📎 시스템 비기능 요구사항

#### -  보안요구사항
<img width="624" alt="스크린샷 2022-10-13 오후 6 35 47" src="https://user-images.githubusercontent.com/84445210/195561160-0876fc5d-f063-4ec7-a349-fd2fda750bfe.png">

#### -  소프트웨어 품질요구사항
<img width="628" alt="스크린샷 2022-10-13 오후 6 36 17" src="https://user-images.githubusercontent.com/84445210/195561332-a82d6936-b9f2-4792-8735-8b5e0a6e3739.png">

### 📎 우선순위
0. 로그인  1. 소비지출 2. 챌린지  3. 경제지식 4. 사용자 관리

## 📑 그라운드 룰
- 변수, 함수, 인스턴스 : Camel case | *ex) camelCase*
- 함수명 : Verb + Term | *ex) getUserInformation()*
- 클래스, 생성자 : Pascal case (Upper Camel case) | *ex) CamelCase*

## 📑 커밋 컨벤션
커밋 메세지는 “타입: 제목/ 본문/ 꼬리말”로 구성됨
### **1. 타입(Type)**
- Feat - 새로운 기능 추가
- Fix - 버그 수정
- Build - 빌드 관련 파일 수정
- Ci - CI관련 설정 수정
- Docs - 문서 (문서 추가, 수정, 삭제)
- Style - 스타일 (코드 형식, 세미콜론 추가: 비즈니스 로직에 변경 없는 경우)
- Refactor - 코드 리팩토링
- Test - 테스트 (테스트 코드 추가, 수정, 삭제: 비즈니스 로직에 변경 없는 경우)
- Chore - 기타 변경사항 (빌드 스크립트 수정 등)

### **2. 제목(Subject)**

- 제목은 50자를 넘기지 않고, 마침표를 붙이지 않습니다.
- 제목에는 commit 타입을 함께 작성합니다.
- 과거 시제를 사용하지 않고 명령조로 작성합니다.
- 제목과 본문은 한 줄 띄워 분리합니다.
- 제목의 첫 글자는 반드시 대문자로 씁니다.
- 제목이나 본문에 이슈 번호(가 있다면) 붙여야 합니다.

### **3. 본문(Body)**

- 선택 사항이기에 모든 commit에 본문 내용을 작성할 필요는 없습니다.
- 한 줄에 72자를 넘기면 안 됩니다.
- 어떻게(How)보다 무엇을, 왜(What, Why)에 맞춰 작성합니다.
- 설명뿐만 아니라, commit의 이유를 작성할 때에도 씁니다.

### **4. 꼬리말(Footer)**

- 선택 사항이므로 모든 commit에 꼬리말을 작성할 필요는 없습니다.
- Issue tracker ID를 작성할 때 사용합니다.
- 해결: 이슈 해결 시 사용
- 관련: 해당 commit에 관련된 이슈 번호
- 참고: 참고할 이슈가 있는 경우 사용

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
