# sk_rookie_github_edu
sk rookie를 위한 git 강의 저장소

리드미를 수정 중입니다

https://drive.google.com/drive/folders/1qS0LnBL17CgBVKrrHmCdWD8dOGyhzSQ7?usp=share_link

https://drive.google.com/drive/folders/1XT4kQhIp9J4MLuYEepGy95cKDio2DzI1

혹시 Linux를 사용하시고 GUI가 제공되지 않는 환경에서 설치파일을 다운받지 못하셨다면 콘솔에서 wget을 사용하여 다운이 가능 합니다.

▶ wget -O splunk-7.2.4-8a94541dcfac-Linux-x86_64.tgz 'https://www.splunk.com/bin/splunk/DownloadActivityServlet?architecture=x86_64&platform=linux&version=7.2.4&product=splunk&filename=splunk-7.2.4-8a94541dcfac-Linux-x86_64.tgz&wget=true'



편의상 다양한 설치 방법들이 존재하지만 압축파일(tgz)을 통한 설치로 설명 하겠습니다.



1. 다운받은 압축파일(splunk-7.2.4-8a94541dcfac-Linux-x86_64.tgz)을 압축해제

▶ tar xvzf splunk-7.2.4-8a94541dcfac-Linux-x86_64.tgz -C /opt 



2. 압축해제된 경로로 이동하여 Splunk 구동

▶ cd /opt/splunk/bin/

▶ ./splunk start --accept-license



3. username 및 password 설정

4. 설치완료

5. 외부에서 http://<리눅스서버IP>:8000 으로 접속하여 로그인 확인.


deb http://ftp.daumkakao.com/ubuntu/ focal main
deb http://archive.ubuntu.com/ubuntu/ focal main

deb http://ftp.daumkakao.com/ubuntu/ focal universe
deb http://archive.ubuntu.com/ubuntu/ focal universe

deb http://ftp.daumkakao.com/ubuntu/ focal multiverse
deb http://archive.ubuntu.com/ubuntu/ focal multiverse

deb http://ftp.daumkakao.com/ubuntu/ focal restricted
deb http://archive.ubuntu.com/ubuntu/ focal restricted
