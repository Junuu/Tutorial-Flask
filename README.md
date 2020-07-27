플라스크 연습


### [Google Colab에서 플라스크 실행하기](https://medium.com/@kshitijvijay271199/flask-on-google-colab-f6525986797b8)
### [python + vscode 다운받고 hello print 해보기](https://blog.naver.com/PostView.nhn?blogId=wideeyed&logNo=221439098133)
### [python pip install](https://076923.github.io/posts/Python-28/#reference-1)
### [vscode python flask](https://m.blog.naver.com/PostView.nhnblogId=poiulkj321&logNo=221367665053&proxyReferer=https:%2F%2Fwww.google.com%2F)
### [index.html 불러오기](https://niceman.tistory.com/151)
### [js,css 불러오기](https://infinitt.tistory.com/119?category=1071293)
### [href 링크로 다른 페이지 넘어가기](https://tariat.tistory.com/761)
### [post ,get 공부](https://medium.com/@mystar09070907/flask%EB%A1%9C-get-post-%EC%9A%94%EC%B2%AD-%EB%B3%B4%EB%82%B4%EA%B8%B0-1-57d8f4559793)
### [숫자를 입력받아 사칙연산 정답맞추기](https://infinitt.tistory.com/269?category=1071293)
### [pandas install 오류 해결](https://stackoverflow.com/questions/60763529/unable-to-import-pandas-pandas-libs-window-aggregations)
### [render_template 에서 개행태그가 이상하게 변환대는것을 막음](https://stackoverrun.com/ko/q/12663581)
### [pandas dataframe html으로 표시](https://stackoverflow.com/questions/22180993/pandas-dataframe-display-on-a-webpage)
### [python 주기적으로 함수 실행하기](https://1byte.tistory.com/18)
### [vscode 버그해결](https://www.it-swarm.dev/ko/python/visual-studio-code-%EB%82%B4%EB%B6%80%EC%97%90%EC%84%9C-python-%EC%8B%A4%ED%96%89%EC%8B%9C-%EC%9E%98%EB%AA%BB%EB%90%9C-%EA%B5%AC%EB%AC%B8-%EC%98%A4%EB%A5%98/805777607/)
### [python 공백 리스트 체크](https://hashcode.co.kr/questions/22/%EB%B9%88-%EB%A6%AC%EC%8A%A4%ED%8A%B8%EB%A5%BC-%ED%99%95%EC%9D%B8%ED%95%98%EB%8A%94-%EB%B0%A9%EB%B2%95%EC%9D%84-%EA%B0%80%EB%A5%B4%EC%B3%90%EC%A3%BC%EC%84%B8%EC%9A%94)

### [python 여러줄 문자열 다루기](https://ledgku.tistory.com/44)
### [크롤링 속도 개선을 위한 N배 빠른 멀티 프로세싱](https://beomi.github.io/2017/07/05/HowToMakeWebCrawler-with-Multiprocess/)
### [python 멀티프로세싱](https://sungmin-joo.tistory.com/11)
### [script 입력 방지](https://www.it-swarm.dev/ko/javascript/javascript%EC%97%90%EC%84%9C-html-%EB%B0%8F-%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8-%EC%82%BD%EC%9E%85-%EB%B0%A9%EC%A7%80/1044047794/)
### [flask multi request](https://medium.com/@dkhd/handling-multiple-requests-on-flask-60208eacc154)
### html.parser -> lxml 로 바꾼후 로딩속도 7초에서 5초로 증가 ( 속도개선)
### [AWS에 등록할 수 있는 최상위 도메인 목록](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/registrar-tld-list.html)
### [AWS elastic beanstalk Cafe24 도메인 네임서버 설정](https://www.it-swarm.dev/ko/amazon-ec2/godaddy-%EB%8F%84%EB%A9%94%EC%9D%B8%EC%9D%84-aws-elastic-beanstalk-%ED%99%98%EA%B2%BD%EA%B3%BC-%EC%97%B0%EA%B2%B0%ED%95%98%EB%8A%94-%EB%B0%A9%EB%B2%95%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9E%85%EB%8B%88%EA%B9%8C/1068284212/)
### [AWS freenom 도메인 네임서버 설정+HTTPS 설정](https://medium.com/@rlatla626/route-53%EC%9D%84-%EC%9D%B4%EC%9A%A9%ED%95%9C-%EB%8F%84%EB%A9%94%EC%9D%B8-%EC%97%B0%EA%B2%B0-f92aaeedf6ea)
### [flask 404 error page 만들기](https://webisfree.com/2017-09-29/python-flask%EC%97%90%EC%84%9C-custom-404-page-%EB%A)
### [aws Elastic Beanstalk flask](https://www.youtube.com/watch?v=b28AlfTRacc)
1. Elastic Beanstalk 생성 ( 이름, 환경 python3.6)
2. 코드 .zip 으로 업로드 해야하며 .py 파일과 cmd python 경로에서 pip freeze 또는 python -m pip freeze 를 하면 나오는 현재 다운로드한 모듈의 버전들을 requirements.txt 에 저장
3. .py 코드에서 app = flask(__name__) application = app = flask(__name__)으로 수정
4. .py 파일명을 application.py로 변경
5. .py파일 , static 폴더, templates 폴더, requirements.txt를 .zip으로 압축후 업로드
6. 호스팅 완료
7. 도메인 네임서버 설정 and HTTPS 설정해야 함.

### [aws Elastic Beanstalk Auto Scaling(]https://docs.aws.amazon.com/ko_kr/elasticbeanstalk/latest/dg/using-features.managing.as.html)
환경 -> 구성 -> 용량(편집) -> 환경 유형 – 로드 밸런싱 수행을 선택 -> 최대 최소 인스턴스 설정 -> 적용
### [Elastic Beanstalk classic load balancer http to https redirect](https://www.youtube.com/watch?v=0IVwrHx1hPI)
https 인증서를 업로드 한 후 https가 들어가지나 사이트 입력시 http로 들어가질때 설정법
### [사이트맵 만들기 ] (https://m.post.naver.com/viewer/postView.nhn?volumeNo=23034092&memberNo=6457418&vType=VERTICAL)
### [서버 부하 테스트] (https://support.loader.io/article/20-verifying-an-app) 영문 도움말 읽어보면 친절하게 하는방법 설명되어 있음.
### [503 Service Temporarily Unavailable 에러 해결](https://medium.com/@degaze.film/aws-load-balancer-503-service-temporarily-unavailable-e1e91c0dfcdb)
### 문제점 : 크롤링이 메모리를 너무 많이 잡아먹어서 메모리 부족으로 서버가 다운됨 따라서 db나 .txt 파일에 크롤링 결과를 저장하여 불러오도록 함.
### 추가 부하 테스트 : 재무제표 기업의 분석의 경우에는 1번의 크롤링이 필수적임 따라서 한번의 크롤링을 test 페이지에 구현하고 test 페이지를 get(불러오면서) 하면서 몇명의 동시유저를 감당할 수 있는지 부하 테스트가 필요함.
### 테스트 결과 : 15명 동시접속 성공 평균속도 2.6초 100명 동시접속 성공 평균속도 6.8초  200 동시접속 성공 평균속도 7.5초 400명 동시접속 평균 속도 11초 600명 동시접속 성공 평균 속도 15초 800명 동시접속 에러 60%
### [python 파일 읽고 쓰기1](https://kongdols-room.tistory.com/47)
### [python 파일 읽고 쓰기2](https://alphahackerhan.tistory.com/26)
### [python 파일 읽기 UnicodeDecodeError](https://nackwon.tistory.com/120)
### [python n초마다 특정 코드 실행](https://www.it-swarm-ko.tech/ko/python/n-%ec%b4%88%eb%a7%88%eb%8b%a4-%ed%8a%b9%ec%a0%95-%ec%bd%94%eb%93%9c-%ec%8b%a4%ed%96%89/969092320/)
### [python 현재시간 불러오기](https://webisfree.com/2017-08-02/python%EC%97%90%EC%84%9C-%ED%98%84%EC%9E%AC%EC%8B%9C%EA%B0%84%EC%9D%84-%EA%B0%80%EC%A0%B8%EC%98%A4%EA%B8%B0)
### [python thread 2번 호출되는 문제](https://stackoverrun.com/ko/q/11997289)
### aws lambda 함수 생성 오류 
#### "역할 템플릿 생성 중에 오류가 발생했습니다. 두 번 이미 있는지 확인할 역할 이름을 확인한 후 다시 시도하십시오." 라는 오류가 발생하면 하단부분에 아래와 같은 글을 발견할 수 있을 것이다.
#### IAM 콘솔에서 (crwaling-role-yy13q9ei) 역할을 확인하십시오.
#### 1. () 괄호 안에있는 링크를 눌러 이동하여 준다.
#### 2. 정책이름을 누룬 후 정책편집을 눌러준다.
#### 3. 시각적 편집기에서  경고가 보일 것이다.
#### 4. cloudwatch logs 를 눌러 리소스부분에서 모든 리소스를 선택해준다.
#### 5. 정책검토를 누룬다.
#### 6. 변경된 내용 저장
#### 7. Lambda로 돌아가 함수생성 시 함수가 생성된다.
#### 오류가 발생하는 이유와 해결되는 이유는 모르겠음..

### [linux cron이란?](https://www.cyberciti.biz/faq/define-cron-crond-and-cron-jobs/)
### cmd 파일수정 : notepad filename 파일읽기: type filename [파일생성](https://m.blog.naver.com/PostView.nhn?blogId=jed00&logNo=140188420401&proxyReferer=https:%2F%2Fwww.google.com%2F)
### [Elastic Beanstalk 인스턴스 접속](https://stackoverflow.com/questions/4742478/ssh-to-elastic-beanstalk-instance)
