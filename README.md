# 메이플스토리 디스코드 봇 [봇이담.]

>메이플스토리 유저들을 위한 discord Bot 입니다. <br/>
간단한 사용자 정보와, 농장 정보, 이벤트 목록 등을 검색이 가능합니다.

![](img/main.jpg)
## 📌참고
**해당 코드는 이영빈(진동아델)에 의해 만들어졌으며 모든 코드의 저작권은 이영빈(진동아델)에게 있습니다.** <br>
해당 소스코드를 응용 하고 싶으신 분은 [여기](https://github.com/dudqls5271/discord-java-bot-2022/fork)을 클릭해 fork 해주세요.

**해당 봇은 개인정보를 요구 하지 않습니다.**
봇이 사용 하는 사용자 정보 -> 서버ID, 채팅방ID

## ✅ 초대 방법!

[봇이담. 초대 링크](https://discord.com/oauth2/authorize?client_id=961659381789909043&scope=bot&permissions=0)
을 클릭하여 서버에 추가 합니다.

## 🚩 사용 방법

**/ 명령어를 치면 해당 명령어 리스트가 나옵니다.**

_더 많은 예제와 사용법은 [페치 노트](https://github.com/dudqls5271/discord-java-bot-2022/tree/master/PatchNote)를 참고하세요._

## 🕹 개발 환경 

| 프로그램 명 | 버전       |
|--------|----------|
| <img src="https://img.shields.io/badge/JAVA-007396?style=flat-square&logo=Java&logoColor=white"/></a>   | 11.0.14  |
|<img src="https://img.shields.io/badge/JDA-5865F2?style=flat-square&logo=Discord&logoColor=white"/></a>   | 4.4.0_352 |
| <img src="https://img.shields.io/badge/MySql-4479A1?style=flat-square&logo=MySql&logoColor=white"/></a>  | 8.0.29   |
| <img src="https://img.shields.io/badge/IntelliJ IDEA-000000?style=flat-square&logo=IntelliJ IDEA&logoColor=white"/></a>  | 2022.1.1 |

## 🖥 서버 및 배포 방법

> 서&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 버: EC2<br>
> DB &nbsp;&nbsp; 서버: RDS <br>
> 배포&nbsp; 방법: JAR

## 🧩 업데이트 내역
* [3.0.0](https://github.com/dudqls5271/Maple_DIscordBot/tree/main/PatchNote/2022_07_28)
  * 추가 
    * `방무 계산기` 기능이 추가
      * Ex)  /방무 실방무 [스텟창] [스킬방무] 
    * `도박` 기능이 추가
      * Ex) /도박 [선택] [횟수]
    * 오류문구 추가
      * 각 상황에 맞는 오류 문구를 출력해줍니다.
  
  * 수정
    * `유저 무릉 검색`이 수정
      * 최고 기록과 몬스터 사진이 맞니 않는 오류가 있었습니다.
    * `농장 검색` 이 수정
      * 해당 기능이 작동 하지 않는 오류가 있었습니다. <br/>
      기존 크롤링 사이트 : https://meso.kr에서 더이상 크롤링을 하지 못하게 되어서<br/>
      https://wachan.me에서 AIP을 가지고와서 보여주는 방식으로 변경 되었습니다.
* [2.0.0](https://github.com/dudqls5271/Maple_DIscordBot/tree/main/PatchNote/2022_07_20)
  * 추가: `유저 검색` 기능이 추가
    * Ex) /정보 (내용)
  * 추가: `유저 무릉 검색` 기능이 추가
    * Ex) /무릉 (내용)
  * 추가: `유저 유니온 검색` 기능이 추가
    * Ex) /유니온 (내용)
* [1.0.0](https://github.com/dudqls5271/Maple_DIscordBot/tree/main/PatchNote/2022_07_12)
  * 추가: `농장 검색` 기능이 추가
    * EX) /농장 [몬스터이름, 조합식] [몬스터 이름]
  * 추가: `무기 추가 옵션` 기능 추가
    * Ex) /추옵 무기이름
  * 수정: `커맨드`가 변경
    * 불필요한 커멘드가 삭제
  * 수정: 기존 `커맨드`가 변경
    * /커맨드 [전부, 히든] (커맨드 이름)
* [0.1.0](https://github.com/dudqls5271/Maple_DIscordBot/tree/main/PatchNote/2022_06_27/README_2022_06_27.md)
    * 최초 배포
* 0.0.1
    * 작업 진행 중

## 🧪 실험실 
해당 항목은 기능이 있지만 아직 실험 중이라 추천을 하지 않습니다.
* 0.1.1
  * 실험중 : `썬데이 메이플 알림` 기능
    * 봇이담. 이 있는 서버에 `봇-공지`가 있으면 금요일마다 선데이 메이플에 관한 공지를 해줍니다.
  * 실험중 : `이벤트 1일 알림` 기능
    * 봇이담. 이 있는 서버에 `봇-공지`가 있으면 이벤트 기간이 1일이 남았을때 공지를 해줍니다.


## ⭐️개발자 정보
해당 이미지를 클릭하면 이동 합니다. <br/>

<a href="https://twitter.com/maple_Dkepf"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=flat-square&logo=Twitter&logoColor=white"/></a>&nbsp;
<a href="discordapp.com/users/249166055316914177"><img src="https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=Discord&logoColor=white"/></a>&nbsp;
<a href="mailto:youngbin5271@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=Gmail&logoColor=white"/></a> &nbsp;
<br>

_**버그 제보 환영**_


## 크롤링 및 AIP 사용
| 홈페이지 이름           | URL |
|-------------------|-----|
| MapleGG           | https://maple.gg   |
| NexonMapleStory   | https://maplestory.nexon.com/Home/Main |
| 와쨩의 메이플 정보 센터_농장  | http://wachan.me/farm.php |



