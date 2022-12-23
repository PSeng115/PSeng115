# **Java Swing (JFrame) 이용하여 슈팅 게임 구현하기**

## 1)개발환경
1. 운영체제: windows OS
2. 개발도구: eclipse
3. 개발언어: java

## 2)개발개요
아케이드 게임에 시초라 할 수 있는 슈팅 게임을 구현 하고자 했고, 12월 컨셉과 시기에 맞춰 산타와 코로나를 메인 캐릭터로 잡아 게임을 만들었다.

## 3)개발환경
-KEY 이벤트를 사용하여 조작키 구현
-JFrame을 이용하여 images폴더를 만들어 이미지 파일 사용
-music폴더를 만들어 Thread를 사용하여 음악(BGM) 설정
-엔딩을 위한 공격, 점수를 처리하기 위한 if 함수 사용
-엔딩 후 재시작을 위한 reset메소드 구현

## 4)게임설명
크리스마스에 산타가 선물을 배송하는데, 코로나가 방해를 한다.   
플레이어가 산타가 되어 코로나를 무찌르며 아이들에게 선물을 배송하러 간다.   
산타가 코로나 캐릭터를 죽이면 200씩 스코어가 오르고, 스코어가 총 800이 되면 승리 엔딩이 나오고,
코로나를 죽이기 전 산타 캐릭터가 먼저 죽으면 패배 엔딩이 뜨며 R키를 누르면 재시작 할 수 있다.

>조작키:

    산타(사용자): W,A,D,S키로 위,왼,오,아래쪽으로 이동이 가능하며, 스페이스바로 공격할 수 있다.
    코로나(적플레이어): 자동으로 생성되어 공격을 한다.


## 5)이미지
-이미지는 직접 그려 사용하였다.

![산타](ShootingGame/bin/images/PaPaPlaye.png)   
![산타공격](ShootingGame/bin/images/PaPaPlayeAttack.png)   
![코로나](ShootingGame/bin/images/Covid.png)    
![코로나 공격](ShootingGame/bin/images/CovidA.png)   
![첫 시작 화면](ShootingGame/bin/images/mainS.png)   
![로딩 화면](ShootingGame/bin/images/loadingS.png)   
![게임 화면](ShootingGame/bin/images/gameS.png)   
![승리 엔딩](ShootingGame/bin/images/happyE.png)    
![패배 엔딩](ShootingGame/bin/images/Over.png)    


