# Colosseum-Battle
* 3D actionRPG game made using Unreal engine 4. * Made for study and portfolio.  
* Developed with Unreal Engine 4.  
* Source control by azure devops.

프로젝트명 : Colosseum Battle  
개발 기간 : 2020.05 ~ 2020.10 (5개월)  
개발 환경 : C++ / Unreal Engine 4 / Azure DevOps  
개발 인원 : 1명  
URL Video : https://youtu.be/pyPxxSHCPiw   
Git Repository : https://dev.azure.com/wnsdd1/_git/ActionRPGProject  
  
요약 설명  
ㆍ콜로세움 맵에서 아군 AI와 함께 스테이지 별로 등장하는 적군들을 모두 처치하는 PC게임  
ㆍUnreal Engine 4의 기능학습 및 적용을 목적으로 개발 진행  
  
구현 내용  
ㆍ캐릭터들의 기반이 되는 캐릭터 베이스에는 캐릭터들의 이동, 무기, 데미지 관련 처리 등 공통 부분들에 대한 구현 진행.  
ㆍ스탯관리, 스킬관리 및 활성화 등의 동작들을 수행하는 어빌리티 시스템 컴포넌트 구현.  
ㆍ각 캐릭터들은 캐릭터 베이스를 상속받은 후, 세부적으로 각기 다른 부분들에 대한 처리는 블루프린트로 구현하여 코드의 재사용성 및 다형성을 가질 수 있도록 구현.  
ㆍ각 캐릭터들에 대한 스탯 수치들은 csv파일을 통한 데이터테이블을 불러오도록 데이터 주도형으로 구성하여 밸런스 수정 작업등으로 인한 수치 변경 시 외부에서 손쉽게 접근할 수 있도록 진행.  
ㆍAI들은 적군 탐색 및 공격, 플레이어 주변을 이동하며 수색, 플레이어와 거리가 멀어지면 플레이어를 따라오도록 구현.  
ㆍ아군 플레이어를 선택하거나 플레이어가 죽으면 자동으로 남아있는 아군 AI로 빙의되도록 하며 죽은 캐릭터의 상태창 이미지는 어둡게, 스탯들은 모두 0으로 표시되도록 구현.  
  
1. 기본 데이터 형식 설정  
  a. 스탯(체력, 마나, 스테미너, 이동속도)  
2.전투 시스템  
  a. 공격 시스템 (Default Attack, Skill)  
  b. Key - Q(Util), E(강한 스킬), R (궁극기), Mouse Right Button(짧은 스킬)  
  c. Ability 시스템, Weapon System  
  d. 기본형 적 기능 추가  
  e. 기본형 적 AI  
3.리더 변경 시스템 ( 태그, 빙의 )  
4.HUD  
5.맵  
  a. 적군 스폰 웨이브  
  b. 맵 레벨 디자인 등  
6.게임 흐름 ( 타이틀 -> 스테이지 선택 -> 아군 선택 등등 )  
7.리더가 아닌 아군 AI  
8.다양한 캐릭터 추가  
9.맵 추가  
  
![Preview_Ingame](https://user-images.githubusercontent.com/62101267/159232227-8445b70b-0a63-4162-aefe-d66c145fc665.png)
