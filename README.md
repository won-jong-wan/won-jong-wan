# 👋 안녕하세요, 임베디드 시스템 개발자 원종완입니다!

임베디드 시스템과 AI 기술을 융합하는 것에 흥미를 느끼고 있습니다.  
💡 하드웨어와 소프트웨어의 경계에서 실제로 작동하는 시스템을 만드는 것이 좋습니다.

---

## 🧠 주요 프로젝트

### ⌨️ [USB-Macro](https://github.com/won-jong-wan/USB-Macro)
**로봇 제어 자동화를 위한 USB 동글 시스템 (Plug & Run)**

- **핵심 기술**: STM32F411 (Black Pill), TinyUSB, Linux Kernel Driver, Qt, Python
- **주요 성과**: SSH/네트워크 없이도 로봇을 자동으로 제어할 수 있는 현장 친화적 시스템 구현
- **특징**:
  - PC에서 명령 패킷을 미리 적재 → 로봇에 꽂으면 자동 실행되는 Plug & Run 구조
  - 네트워크 장애 시에도 CDC↔UART 시리얼 브릿지로 라즈베리파이 콘솔 접근 가능
  - PC(Qt GUI) → 동글(STM32 펌웨어) → 로봇(RPi Daemon) 전체 스택 직접 구현
  - 커스텀 Linux 커널 드라이버 개발로 `/dev/custom_usb_*` 디바이스 파일 인터페이스 제공
  - 로봇 현장에서 SSH/네트워크 불안정 문제를 하드웨어 레벨에서 해결

### 🎤 [Pride-and-Prejudice](https://github.com/won-jong-wan/Pride-and-Prejudice)
**Hailo 8 + Raspberry Pi를 이용한 AI 기반 모의면접 시스템**

- **핵심 기술**: Hailo 8 AI 가속기, Raspberry Pi, Python
- **주요 성과**: 실시간 AI 면접 피드백 시스템 구현
- **특징**:
  - Edge AI를 활용한 온디바이스 추론으로 빠른 응답 속도 구현
  - Hailo 8 가속기를 통한 효율적인 AI 모델 실행
  - 취업 준비생을 위한 실전 면접 연습 환경 제공

### 🎮 [dance_with_VGA_STM32F411RE](https://github.com/won-jong-wan/dance_with_VGA_STM32F411RE)
**STM32F411RE Nucleo 보드를 활용한 VGA 비디오 출력 구현**

- **핵심 기술**: STM32F411RE, VGA 프로토콜, 임베디드 C
- **주요 성과**: 640×480@60Hz 해상도의 VGA 신호 생성
- **특징**:
  - 마이크로컨트롤러의 타이머와 DMA를 활용한 효율적인 비디오 신호 생성
  - 하드웨어 리소스를 최적화하여 안정적인 60Hz 출력 달성
  - 베어메탈 프로그래밍을 통한 Low-level 하드웨어 제어 경험

### 🤖 [pf_amcl](https://github.com/won-jong-wan/pf_amcl)
**ROS2 기반 로봇 위치 추정 및 경로 계획 교육 프로젝트**

- **핵심 기술**: ROS2, AMCL, Potential Field, Gazebo, C++/Python
- **프로젝트 배경**: 로봇공학 수업의 조교로 근무하며 학생들의 최종 과제로 설계한 프로젝트
- **교육 목표**: 
  - AMCL(Adaptive Monte Carlo Localization)을 통한 로봇 위치 추정 이해
  - Potential Field 알고리즘 기반 경로 계획 및 장애물 회피 구현 능력 배양
  - ROS2 프레임워크와 Gazebo 시뮬레이터 활용 경험
- **특징**:
  - TurtleBot3를 활용한 실습 중심 과제 구성
  - 인력/척력 파라미터 조정을 통한 알고리즘 이해 심화
  - 실제 로봇 시스템 개발의 전체 파이프라인 경험 제공

### 🥷 [ninja-academy](https://github.com/won-jong-wan/ninja-academy)
**YOLOX 기반 실시간 포즈 인식 & 분신술 효과 생성**

- **핵심 기술**: YOLOX, OpenCV, Python, 컴퓨터 비전
- **주요 성과**: 실시간 카메라 입력으로 사람 포즈 인식 및 시각 효과 생성
- **특징**:
  - YOLOX 객체 감지 모델을 활용한 실시간 포즈 추적
  - 분신술 효과를 위한 커스텀 후처리 알고리즘 구현
  - 웹캠 기반 인터랙티브 시각 효과 데모

### 🎮 [A-safe-picking-game](https://github.com/won-jong-wan/A-safe-picking-game)
**안드로이드 기반 게임 애플리케이션**

- **핵심 기술**: Java, Android SDK
- **특징**: 대학 과제로 개발한 모바일 게임 프로젝트

---

## 💻 기술 스택

### Embedded Systems
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![ARM](https://img.shields.io/badge/ARM-0091BD?style=flat-square)
![Firmware](https://img.shields.io/badge/Firmware-555555?style=flat-square)

### Robotics & Automation
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo-FF6F00?style=flat-square)

### AI & Machine Learning
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberry-pi&logoColor=white)

### Mobile Development
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)

### Tools & Platforms
![Linux Embedded](https://img.shields.io/badge/Linux_Embedded-000000?style=flat-square&logo=linux&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

---

## 🎯 관심 분야

- 💡 **임베디드 시스템 & 펌웨어 개발**: MCU 기반 시스템 설계 및 구현
- 🤖 **Edge AI & 하드웨어 가속**: AI 모델의 임베디드 환경 최적화
- 🚗 **로봇공학 & 자율주행**: ROS 기반 로봇 시스템 개발
- 🎨 **그래픽스 & 비디오 신호 처리**: VGA, HDMI 등 디스플레이 인터페이스
- 🔧 **하드웨어-소프트웨어 통합**: 실제 작동하는 완성된 시스템 구축

---

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=won-jong-wan&show_icons=true&theme=tokyonight)

---

## 📫 연락처

📧 Email: jonwon2009@naver.com  
💼 GitHub: [@won-jong-wan](https://github.com/won-jong-wan)
