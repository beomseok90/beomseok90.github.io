---
layout: post
comments: true
date: 2019-02-20 17:00:00
categories: IT
---

블로그를 시작하기에 앞서 고민했던 것 중에 하나가 바로 _블로그 플랫폼_ 선택이었다. 장단점을 따져 ~~좀 더 개발자스러운(?)~~ [Github](https://github.com/)에 [Jekyll](https://jekyllrb.com/)을 사용해 만들기로 하였고
기능상 자체적으로 지원되지 않는 **웹 로그 분석 기능** 및 **댓글 기능**을 추가해야만 했다.
그중 먼저 웹 로그 분석에 필요한 [Google Analytics](https://www.google.com/analytics/)에 연동해보려 한다.


## Google Analytics 연동
### 1. 접속
* <https://www.google.com/analytics/> 으로 이동

### 2. 새 계정 설정  
2-1. **무료로 시작하기** 클릭   
![GA_join](/images/2019-02-20/GA_join.png)

2-2. 정보를 입력  
![GA_join2](/images/2019-02-20/GA_join2.png)

2-3. **ID추적하기** 클릭  
![GA_join3](/images/2019-02-20/GA_join3.png)

### 3. 약관 동의
* 거주지역을  **대한민국**으로 선택 후 **동의 함** 클릭

### 4. 추적코드 입력
* **추적코드**를 복사하여 `header.html` 등 반복적으로 실행되는 영역이 존재하는 파일의 `<head>` 태그 내에 붙여넣기  
![GA_join4](/images/2019-02-20/GA_join4.png)

### 5. 연동 완료
* Google Analytics에 접속하여 웹 로그 분석
* 내 IP 주소를 제외하는 필터 적용은 [블로그채널](https://blogchannel.tistory.com/263?category=620429)를 참고 하였습니다.  

----
## 마치며
* 익숙치 않은 개발환경으로 Google Analytics를 연동해보며 조금은 헤메기도 했지만 마크다운 문법을 공부하고 새로운 API를 적용하며 기능을 추가하고 글을 써내려가는 동안 또 한번 프로그래밍의 재미를 느낄 수 있었다. 앞으로도 나 자신이 점점 발전해나가는 과정이라고 생각하며 천천히 즐겨보려 한다.