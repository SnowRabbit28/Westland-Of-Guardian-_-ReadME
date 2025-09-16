# Westland-Of-Guardian


 ## 👨‍🏫 프로젝트 소개

**게임 제목** : 황야의 수호자

**장르** : 캐주얼 슈팅 디펜스 게임

**컨셉 :** 끝없는 침략에 시달리는 황야의 작은 마을을 지키기 위해 나선 보안관의 이야기.

**목표** : 간단한 조작만으로 누구나 쉽게 접근할 수 있으면서도, 
타격감과 성장 요소를 통해 손맛을 느낄 수 있는 디펜스형 캐주얼 슈팅 게임

## 개발기간

___2025. 07. 08 ~ 2025. 07. 30___

## 게임 특징

**심플하지만 강렬한 조작 시스템**
- 조준과 슈팅이 전부인 직관적인 조작
- 각 웨이브마다 총기 선택 -> 강화 -> 진화를 거치는 빠른 진행
- 사선 연사, 반사 총알, 연속 발사 등 강화 효과를 통한 전략적 타격

**총기 3 in 1 시스템**
- 총기 선택 : 리볼버, 스나이퍼, 머신건 중 하나를 선택해 각기 다른 전투 스타일 체험 가능
  <img width="903" height="476" alt="image" src="https://github.com/user-attachments/assets/a7272f8b-d9c0-4f57-b244-8ff1783722f1" />

- 3 in 1 강화 : 더블, 트리플, 팅기기 등 다양한 전투 옵션 제공
  <img width="891" height="481" alt="image" src="https://github.com/user-attachments/assets/4384833e-17fb-45eb-98cd-00836111c35f" />

- 진화 : 리볼버 알파, 스나이퍼 알파, 머신건 알파로 진화하며 압도적인 화력


## 핵심 루프 구현

- " 조준 -> 사격 -> 처치 "
  - 최소 기능으로 디펜스 플레이 구현
  - 플레이어 조작 및 전투 루프 구현
- 적 구성 및 스폰 ( 웨이브 ) 구성
  - 일반, 정예, 보스 등 다양한 등급의 적
  - 적 마다 서로 다른 이동 로직 보유
    
<img width="104" height="127" alt="image" src="https://github.com/user-attachments/assets/685c13ab-c636-42d2-aac0-8f56aa576101" /> <img width="92" height="120" alt="image" src="https://github.com/user-attachments/assets/fe754de7-a283-426a-99d5-c2317fe46609" /> <img width="136" height="135" alt="image" src="https://github.com/user-attachments/assets/d0c1a728-b87a-485e-9895-9b63c17de79b" /> <img width="150" height="180" alt="image" src="https://github.com/user-attachments/assets/e44312d8-759d-4792-a335-5fd054f47ec2" />


## 기능 구현 내용
**완료된 인게임 MVP 기능**

- 3종의 총기 중 1종 선택으로 게임 시작
- 웨이브마다 무기 강화 / 무기 진화 중 택1 => 성장
- 제한된 플레이 공간 내에서 적의 침공을 막아내는 디펜스 중심 구조
- 간단한 조작 속에서도 다양한 성장 루트를 통해 반복 플레이 유도
