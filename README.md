# 🕹 Game planning for next quarter
데이터를 통해 유저들의 선호와 게임 트렌드를 파악해서, "어느 지역을 대상으로, 어떤 장르를 어떤 플랫폼에 출시할 것인가"를 알아내는 것이 목표

## 1. Dataset
- Name : 게임의 이름
- Platform : 게임이 지원되는 플랫폼의 이름
- Year : 게임이 출시된 연도
- Genre : 게임의 장르
- Publisher : 게임을 제작한 회사
- NA_Sales : 북미지역에서의 출고량
- EU_Sales : 유럽지역에서의 출고량
- JP_Sales : 일본지역에서의 출고량
- Other_Sales : 기타지역에서의 출고량

## 2. Features
게임 시장은 계속해서 변화함. 특정 플랫폼/회사에서 발행한 게임의 수가 피크를 찍고 사라짐을 확인할 수 있음.  
따라서 모든 데이터를 다루기 보다는 최근 년도와 관계가 깊은 근래 15년만을 다뤄 데이터 축소화
![image](https://user-images.githubusercontent.com/75603262/124702910-4559cc00-df2c-11eb-9d7c-8052aa02900c.png)

## 3. 장르 및 플랫폼의 트렌드를 확인
