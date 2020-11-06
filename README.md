# nodejs
learning nodejs
# 노드를 처음 시작할때 설치 및 사용법
2020.11.07 02:50

참고 강의 사이트 : https://opentutorials.org/course/3332/21028 (생활코딩)


사용법
1. 다운로드 및 설치
   다운로드 사이트 : https://nodejs.org/ko/
   14.15.0.LTS 버전으로 다운로드 받았으며, 설치시 별다른거 건드릴 필요없이 Next만 누르면 됨.
   
   <img width="200%" src="https://user-images.githubusercontent.com/67315764/98396043-7da8c200-20a0-11eb-91e9-77045971fe5d.png"></img>
  


2. cmd를 이용한 node 사용법(윈도우 사용자 참고)

   윈도우키+R 을 누르면 실행창이 뜨는데 실행창에 cmd를 치고 엔터를 누르면 명령프롬프트가 나온다.

   <img width="200%" src=https://user-images.githubusercontent.com/67315764/98397378-9f0aad80-20a2-11eb-83bd-3035d49688a7.PNG></img>
   
   ⑴ 명령프롬프트 창에서 node -v 입력 후 엔터를 누르면 노드의 버전을 알려준다.
   
   ⑵ 명령프롬프트 창에서 node 입력 후 엔터를 누르면 노드를 사용할 수 있게 해준다.
   
   ⑶ ex)console.log(1+1); 입력 시 출력 되는 문자 2
   
   ⑷ ctrl+c를 두번 누르면 사용 종료
   
   ※ cmd 사용법
   1. cd..          ▶ 현재 폴더(디렉토리)에 한단계 상위 폴더(디렉토리)로 이동  ex) c:\호석\하이 → c:\호석
   2. cd [폴더 경로] ▶ 이동하려는 폴더로 이동                                ex) cd c:\호석\하이
   3. dir           ▶ 현재 폴더(디렉터리)에 있는 폴더와 파일명을 보여줌.   
   


3. 이클립스를 이용한 Nodejs 사용법
   
   이클립스를 설치했다는 가정하에 이클립스에서 Nodejs 를 설치하는 방법을 작성하였다.
   
   ⑴ 이클립스를 실행하고 node Plugin을 설치를 위해 메뉴 상단  help - Eclipse Marketplace 메뉴로 가서 Find 검색란에 node 입력 후 검색한다.
   
      이때 node가 검색이 안될수 있으니 nodeclipse로 검색하거나 검색란 우측 두번째칸에 All categories를 Web으로 하여 검색하면 잘 찾아질것이다.
      
   <img width="200%" src="https://user-images.githubusercontent.com/67315764/98402239-50611180-20aa-11eb-8ac5-ffdc9b4b1589.png"></img>
   
   ⑵ 화면과 같이 Nodeclipse.github.io 1.0.2 라고 뜨면 Install을 눌러주면 Confirm Selected Features 화면으로 이동한다.
     
   <img width="200%" src="https://user-images.githubusercontent.com/67315764/98402398-8f8f6280-20aa-11eb-94af-98a701d6d5fb.png"></img>
   
   ⑶ Confirm 을 누른후 만약 경고 메세지가 OK를 누르고 Install anyway 수초 또는 수분 후 Restart를 여부를 묻는 창이 뜨는데 Restart를 눌러주면 재실행된다.
      
   <img width="50%" height="100%" src="https://user-images.githubusercontent.com/67315764/98403702-ba7ab600-20ac-11eb-9657-1f4bf7b83254.png"></img>
   
   ⑷ 이클립스가 실행되면 메뉴 상단 File - new - Node.js Project를 하면 프로젝트를 생성할 수 있다. (Other에서 찾는 방법도 있다.)
      프로젝트 생성 시 Teamplate to use에서 none/empty를 제외한 나머지를 선택하게 되면 자동으로 node.js Web server를 만들어준다.   
      
   <img width="50%" height="100%" src="https://user-images.githubusercontent.com/67315764/98405122-10e8f400-20af-11eb-816d-39eab5350979.PNG"></img>
   
   ⑸ 이후 생성된 hello-world-server.js 를 오른쪽 마우스 클릭후 Run as - 2 Node.js Application을 실행하면
   
   <img width="200%" src="https://user-images.githubusercontent.com/67315764/98405331-6cb37d00-20af-11eb-891d-fbaf136b1e1c.png"></img>
   
   ⑹ 아래와 같이 콘솔 창에 Server running at http://127.0.0.1:1337/ 라고 주소창이 뜨게된다.
   
   <img width="200%" src="https://user-images.githubusercontent.com/67315764/98405652-f82d0e00-20af-11eb-80eb-20ff684b151c.png"></img>
   
   ⑺ 이 서버 주소를 http://127.0.0.1:1337/ 웹브라우저를 이용하여 주소창에 치게 되면 아래와 같은 Hello world 라는 표시가 뜨게 된다. 끝.
   
   <img width="200%" src="https://user-images.githubusercontent.com/67315764/98406163-d41dfc80-20b0-11eb-9952-89ae354f429c.png"></img>
   
   
   
     
