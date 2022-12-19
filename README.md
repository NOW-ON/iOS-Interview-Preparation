# iOS Interview Preparation
iOS 면접 준비



 
### iOS



| 질문 | 답변모음 | 
|--|:--:|
| GCD | [#1](../issues/1) |
| 앱의 생명주기 | |
| Copy On Write | |
| | |


### Swift Fundamentals

| 질문 | 답변모음 | 
|--|:--:|
| Closure와 escaping closure | | 
| optional과 optional의 내부 구조 | | 
| 프로토콜 | |
| Collection Type의 종류와 특징 | |
| struct와 class의 차이 | |
| 이니셜라이져와 Convenience init | |
| Generic | |
| Extension에서 사용할 수 없는 프로퍼티 | |
| Access Control의 필요성과 각 종류의 특징  |  | 
| CaptureLists와 weak, unowned의 차이 | |
| enum의 caselterable과 연관 값(Associated Values | |
| | |
 

### AutoLayouts


| 질문 | 답변모음 |
|--|:--:|
| | |



### ARC


| 질문 | 답변모음 | 
|--|:--:|
| ARC의 동작원리 | |
 

### Architecture


| 질문 | 답변모음 | 
|--|:--:|
| Singleton Pattern | |
| SOLID | |
| MVVM vs MVC | |
| Delegate Pattern | |
  


### Rx


| 질문 | 답변모음 | 
|--|:--:|
| | |
 


### Network


| 키워드| 질문 | 답변모음 | 
|--|:--:|:--:|
| REST API | 특징과 단점 | |
|  | 가벼운 개념 정의 |  |
|  |Over-Fetching/Under-Fetching|  |
| TCP vs UDP | 프로토콜 특성에 따라 적합한 서비스 | |
| 프로세스와 스레드 | 정의 |  |
|   | 메모리 관점에서의 정리 |  |
| HTTP vs HTTPS  | 정의  |  |
| |SSL/TLS 관점에서 대칭키 암호화/비대칭키(공개키) 암호화|  |
|  | ATS  |  |


### Database


| 키워드| 질문 | 답변모음 | 
|--|:--:|:--:|
| 데이터베이스 특징 | 정의| |
| |트랜잭션 | |
| | ACID| |
| | 정합성 | |
| | 무결성| |
| | | |


### 운영체제


| 키워드| 질문 | 답변모음 | 
|--|:--:|:--:|
| 메모리 구조 | 코드| |
| | 데이터 | |
| | 힙 | |
| | 스택 | |
| | | |

 


## 발표 내용

<details> 
  <summary>AutoLayout</summary> 
<br>

| 질문 | 답변모음 |
|--|:--:|
| 오토레이아웃을 코드로 작성하는 방법 | [2022.10.17 윤여진](https://alike-cucumber-a6f.notion.site/3-0b7818ae470846a79d371e0a0b9b89c0) |
| `Storyboard`를 이용했을 때의 장단점 | [2022.10.17 이주영](https://alike-cucumber-a6f.notion.site/Storyboard-e160c249490a45019e804059f3dc9dec) |
| `SafeArea` | [2022.10.17 홍석준](https://alike-cucumber-a6f.notion.site/Safe-Area-e5783c7ec4f645e8aa79426dc2b5663e) |
| Left Constraint 와 Leading Constraint의 차이점 |  [2022.10.17 홍석준](https://alike-cucumber-a6f.notion.site/Left-Leading-Constraint-e9f2db656be94de987f4c27f8e2082ee) |
| hugging, resistance | [2022.10.19 이재용](https://alike-cucumber-a6f.notion.site/Hugging-Compression-Resistance-ca680c4230eb4390aab27a99bc533b63) |
| Intrinsic Size | [2022.10.19 김도이](https://kimdee.notion.site/Intrinsic-Size-ce83224da43143ebad61be9a591221af) |

 
</details> 

<details> 
  <summary>iOS</summary> 
<br>

| 질문 | 답변모음 |
|--|:--:|
| `Bounds`와 `Frame`의 차이점 | [2022.10.19 윤여진](https://alike-cucumber-a6f.notion.site/Frame-Bound-4e5eac8d98504b6ca56e734c3012ec80) |
| 실제 디바이스가 없을 경우 개발 환경에서 할 수 있는 것과 없는 것 | [2022.10.19 윤여진](https://alike-cucumber-a6f.notion.site/7ad3ceb3dea640af9f41c3a08a02d815) |
|UIKit 클래스들을 다룰 때 꼭 처리해야하는 애플리케이션 쓰레드 이름 | [2022.10.19 이주영](https://alike-cucumber-a6f.notion.site/UIKit-bd4f876322454036b8e5ab4bc1c97de2) |
| `@Main` | [2022.10.21 홍석준](https://alike-cucumber-a6f.notion.site/Main-2022-10-21-d7ba5d149f1743ca853711ef0a9d0683) |
| `NSOperationQueue`와 `GCD Queue`의 차이점 | [2022.10.21 김도이](https://kimdee.notion.site/NSOperationQueue-GCD-Queue-878028323d414304bc34c332a2d7872d) |
| Global DispatchQueue의 `QoS`의 종류와 의미  | [2022.10.21 김도이](https://www.notion.so/kimdee/Global-DispatchQueue-QoS-3a480b3635774764be5147caa21550c8) |
| GCD API 동작 방식과 필요성 |  [2022.10.21 김도이](https://kimdee.notion.site/GCD-API-4676cc2622f844aa924bb747bceb1282) |
| `prepareForReuse` |  [2022.10.21 이재용](https://alike-cucumber-a6f.notion.site/prepareForReuse-60ae3f5a78b74d3ba216670505752d18) |
| 하나의 View Controller 코드에서 여러 TableView Controller 역할을 해야 할 경우  |  [2022.10.21 이재용](https://alike-cucumber-a6f.notion.site/View-Controller-TableView-Controller-94f859e78daa400aa66ca588fb792eab) |
| TableView 동작 방식과 화면에 Cell을 출력하기 위해 최소한 구현해야 하는 DataSource 메서드 |  [2022.10.21 이재용](https://alike-cucumber-a6f.notion.site/TableView-Cell-DataSource-d7debe86ba7742c8aabafefc80ee82c1) |
| 다크모드 지원방법 | [2022.10.21 윤여진](https://alike-cucumber-a6f.notion.site/fcede1dd2a1148b0914b368bc890afd8) |
| 앱의 콘텐츠,데이터를 저장하는 특별한 객체  |  [2022.10.21 윤여진](https://alike-cucumber-a6f.notion.site/90be32e3d2534a6ca168a73d45fc8d9a) |
| 앱 화면의 콘텐츠를 표시하는 로직과 관리를 담당하는 객체 |  [2022.10.21 윤여진](https://alike-cucumber-a6f.notion.site/92c10f5aa23a42849a7baf5d759deb6e) |
| App Bundle의 구조와 역할 | [2022.10.21 이주영](https://alike-cucumber-a6f.notion.site/App-Bundle-1d990e129a904f6482a030936eb9290f)|
| 모든 View Controller 객체의 상위 클래스와 그 역할 | [2022.10.21 이주영](https://alike-cucumber-a6f.notion.site/View-Controller-b1158c9b8d89400eb1976ea3dd5465ac) |
|  |  [yyyy.MM.dd 이름]() |



</details> 


