# 🚗2023KEB_Group1 VectorMen
차량 제어 및 통신 통합 시험, 검증 시스템

## 🐕‍🦺Service
- MBD기반 Simulink 제어 Model 구축
- CANoe를 통한 가상 제어기 구현 및 메시지, 시그널 설정 > 통신 시스템 검증
- Unity를 이용한 차량 시뮬레이션 환경 제공

## 📦Structure
Image
  
## 📁 Directories
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
 ┗ 📜ProjectSettings.vtesettings
 
## 👪👪 Member
⚙️ 제어, 설계팀 : 김태영, 김기현, 방상우
🛡️ 시험, 검증팀 : 하동훈, 조병민, 김상협

## Acknowledgement
“본 연구는 과학기술정보통신부 및 정보통신기획평가원의 SW전문인재양성사업의 연구결과로 수행되었음“(2022-0-01127)

