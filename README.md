# Ransomware

> <-- 주의! 이 프로그램을 통해서 본인의 컴퓨터의 중요데이터가 암호화 될수 있습니다!-->

##소개
 최근 사용자의 컴퓨터 내의 중요 데이터를 암호화 하고, 이를 복호화 할수있는 키를 판매하는 바이러스가 있습니다.
 
 이를 Ransomware바이러스라고 하는데, Ransomware 바이러스를 실제로 구현해보았습니다. 
 
 컴퓨터 내의 모든 중요 파일을 암호화 한 후, 이에 대한 복호화를 하기 위해서는 Paypal을 통해서 복호화 Key를 구입해야 합니다.
 Key를 구입한 사용자는 이전처럼 파일을 사용할수있도록 복호화가 가능해진다.
 
##프로그램 순서도
1. 사용자에게 PikiCast 화면을 보여주어, 정상적인 프로그램인것처럼 둔갑한다.
2. 백그라운드에서 암호화할 파일들을 인댁싱한다.
3. 인댁싱한 파일들에 암호화 알고리즘(AES 256)을 적용한다
4. 암호화가 완료되었으며, 복호화 하기 위해서는 키를 구입해야 한다는 화면을 출력함.
5. 사용자가 Key를 Paypal을 통해 구입, 이메일로 키를 전송받음
6. 구입한 키를 화면에 입력하면, 복호화 할 파일들을 인댁싱함.
7. 인댁싱이 끝나면, 복호화 알고리즘을 통해 복호화를 진행함.
8. 복호화가 끝나면 복호화가 끝나다는 메시지 창을 사용자에게 출력함.
9. 프로그램을 종료
 
##암호화 되는 파일 리스트
- jpg,docx,hwp,pptx,ppt,avi,mp4,mkv,max,cad,zip,pdf,psd,txt,mp3

##개발자
한국디지털미디어고등학교 2학년 김준성 codertimo@gmail.com

한국디지털미디어고등학교 2학년 강희룡 ganddamuniya@naver.com

Java 수행평가의 목적으로 제작하였으며, 임의로 복사 및 배포를 허용합니다.


