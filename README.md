# C 언어 채팅 프로그램

## 목차
1. [소개](#소개)
2. [주요 기술](#주요-기술)
3. [사용법](#사용법)
4. [실행 화면](#실행-화면)

---

## 소개

이 프로젝트는 C 언어를 사용하여 구현한 서버와 클라이언트 채팅 프로그램입니다.   
클라이언트는 서버에 접속하여 고유한 ID를 통해 채팅 방을 개설하거나 접속하여 채팅, 파일 업로드 및 다운로드를 할 수 있습니다. 
GTK 라이브러리를 사용하여 GUI를 구현하였습니다.

---

## 주요 기술

- **소켓 통신**: `<sys/socket.h>` 라이브러리를 사용하여 클라이언트와 서버간의 통신 구현
- **GTK 라이브러리**: `<gtk/gtk.h>` 를 이용하여 GUI 클라이언트 인터페이스 구현

---

## 사용법
- **서버 사용법**   
_server폴더로 이동하여 서버를 실행하고 클라이언트의 접속을 기다립니다.
기본적으로 50001포트를 사용합니다.
 ```bash
 ./server
```

![image](https://github.com/user-attachments/assets/9f37b543-7d0b-4867-bc90-52fc6892cba8)

클라이언트가 접속하면 채팅을 시작할 수 있습니다.

- **클라이언트 사용법**
_client폴더로 이동하여 클라이언트를 실행합니다.
 ```bash
 ./client
```

서버 IP 주소와 포트 번호, 입장할 방번호를 입력 후 Connect버튼을 눌러 채팅 방을 개설하거나 기존 채팅 방에 접속합니다.
![image](https://github.com/user-attachments/assets/e1de56ec-0953-425c-862f-e42335fcb004)

사용할 닉네임을 설정 후 채팅을 하거나 파일을 전송할 수 있습니다.   
![image](https://github.com/user-attachments/assets/22a0d104-eef0-48c1-abd9-c2dac60de4e8)   
![image](https://github.com/user-attachments/assets/aa0f32d9-a63f-48ba-a3d3-7504e1bbe4f7)

---

## 실행 화면
