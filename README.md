# 🚗2023KEB_Group1 VectorMen
차량 제어 및 통신 통합 시험, 검증 시스템입니다.
사용자는 해당 시스템을 통해 실제 차량에 적용되는 차량 네트워크와 제어기들의 작동을 시험 및 검증할 수 있습니다.

## 🐕‍🦺 설명
![Demo_gif](https://github.com/K-Software-BootCamp/2023KEB_Group1/assets/126951066/c2cd2db0-0a8f-40b2-add3-4bde60c6bb26)
- MBD기반 Simulink 제어 Model 구축 (PMSM모터, 에커만 스티어링 etc)
- CANoe를 통한 가상 제어기 구현 및 메시지, 시그널 설정 > 통신 시스템 검증 (1 Channel CAN Protocol)
- Unity를 이용한 차량 시뮬레이션 환경 제공

## 📦 구조도
CANoe Vector I/O 라이브러리를 통해 MATLAB/Simulink와 데이터 송수신
Unity - MATLAB/Simulink 간 UDP Socket을 통해 데이터 송수신 (127.0.0.1:25000)
![Document1](https://github.com/K-Software-BootCamp/2023KEB_Group1/assets/126951066/2e872f94-4809-47cf-a799-a87614775c8b)

## ⏲️ 개발 기간
- 23.07.24일 - 23.08.23일

## 👪 멤버 구성
- 🛡️ 시험, 검증팀 : 하동훈, 조병민, 김상협
- ⚙️ 제어, 설계팀 : 김태영, 김기현, 방상우

## 🌊 개발 환경
### 1. 사용 언어
C++, C#, CAPL
### 2. 작업 툴
CANoe, MATLAB/Simulink, Unity, Blender
### 3. IDE
Visual Studio 2022
### 4. 협업 툴
Jira, Git, Github, Notion

## 📁 폴더 구조
```
📦Project
 ┣ 📂CAPL - 가상 시나리오 생성 CAPL 코드
 ┃ ┣ 📜SimulatorON.can
 ┃ ┣ 📜Sim_Test.can
 ┃ ┗ 📜Sim_Test.cbf
 ┣ 📂Database - 메시지, 시그널 정의 dbc파일
 ┃ ┗ 📜MBD.dbc
 ┣ 📂Exec32 - 32Bit dll, Simulink to CANoe build image, ini etc
 ┣ 📂Exec64 - 64Bit dll etc
 ┣ 📂Model - MATLAB / Simulink Model
 ┃ ┣ 📜Main.slx
 ┃ ┗ 📜PMSM_Motor.slx
 ┣ 📂Panel - CANoe Panel, Image
 ┃ ┣ 📂Bitmaps
 ┃ ┣ 📜controlPanel.xvp...
 ┣ 📂VectorKEB_Unity - Unity Simulation.exe, dll + etc
 ┣ 📜MBD_Test.cfg - CANoe cfg 파일, 설정 저장
 ┣ 📜MBD_Test.stcfg
 ┣ 📜ProjectSettings.vtesettings
 ┗ 📜기능 명세서.xlsx - 기능 명세서
```
 
## 🚀 주요 설명
### MATLAB / Simulink
링크
### CANoe
링크
### Unity
링크
 

## Acknowledgement
```
“본 연구는 과학기술정보통신부 및 정보통신기획평가원의 SW전문인재양성사업의 연구결과로 수행되었음“(2022-0-01127)

```
