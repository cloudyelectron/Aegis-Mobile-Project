# 📱 Aegis Tactical Smartphone Series – Product Concept Document (2025 통합본 v1.2)

## 🔰 1. 제품 개요 (Product Overview)
Aegis 스마트폰 시리즈는 전술, 생존, 현장 작전을 위해 설계된 모듈형 러기드폰입니다. 호환성, 내구성, 생산 효율성을 극대화하기 위해 통합 플랫폼을 기반으로 구축되었으며, 각 모델은 특정 임무 프로필에 맞춰 제작됩니다.

**Aegis Mobile - Rugged Secure Phone Ecosystem**

---

## ❄️ 2. 소개 및 비전 (Introduction & Vision)
**Aegis Mobile**은 프라이버시, 내구성, 전술적 유틸리티라는 단일 목표를 가지고 구축된 새로운 차원의 러기드 스마트폰 및 소프트웨어 생태계입니다.

Aegis는 기존 스마트폰이 취약한 현대적인 위협 환경에 대한 대응입니다. 우리의 사용자는 다음과 같습니다:
- 최전선 작업자
- 아웃도어 전문가
- 보안에 민감한 개인
- 재난 구조 요원

그들에게 필요한 것은 장난감이 아닌 도구입니다.

**한국어 슬로건**: “위험할 때는 PTT!” (“When it matters: PTT!”)

---

## 🏋️ 3. 제품 라인업 개요 (Product Line Overview)

| 모델 (Model) | 타겟 (Target) | 주요 특징 (Key Features) | 가격 (Price USD) |
|---|---|---|---|
| **Lite** | 예산 사용자, 첫 구매자 (Budget users, first-time buyers) | IP68, 기본 PTT, 최소 보안 OS (IP68, basic PTT, minimal secure OS) | $349 ~ $399 |
| **Core** | 주류 작업자, 프로슈머 (Mainstream workers, prosumers) | 향상된 견고성, 중간 사양, 좋은 카메라 (Improved ruggedness, mid specs, good camera) | $549 ~ $649 |
| **Pro** | 열악한 환경의 전문가 (Professionals in tough fields) | 높은 견고성, 프리미엄 사양, 열화상 카메라 (High ruggedness, premium specs, thermal cam) | $799 ~ $949 |
| **Ultra** | 고위험, 고수요 사용자 (High-risk, high-demand users) | 플래그십 사양, IR 라이트, 최고 수준의 내구성 (Flagship specs, IR Light, highest durability) | $1199 ~ $1399+ |
| **Guardian** | 맞춤형 B2G 고객 (Custom B2G clients) | 모듈형, 임무별 맞춤 (NV 카메라, 에어 갭) (Modular, mission-specific (NV cam, air gap)) | $999 ~ $1499+ |

모든 모델 공통 사항:
- 물리적 PTT 버튼 (PTT physical button)
- Aegis OS (보안 강화 안드로이드 포크) (Aegis OS (secure forked Android))
- 오프라인 도구 (Offline tools)
- 보안 우선 UX (Security-first UX)

---

## 📄 4. Aegis OS 컨셉 (Aegis OS Concept)
오프라인 작동, 모듈형 제어 및 낮은 디지털 서명에 중점을 둔 강화된 안드로이드 포크입니다. (A hardened Android fork, focused on **offline operation, modular control, and low digital signature.**)

주요 모듈 (Key modules):
- **스텔스 모드 (Stealth Mode)**: 모든 네트워크 방출 비활성화 (disables all network emissions)
- **통신 보관소 (Comm Vault)**: 세분화된 제어로 Zello, Signal, MeshTalk 통합 (Zello, Signal, MeshTalk with granular control)
- **센서 감시 (Sensor Watchdog)**: 예기치 않은 활성화 (마이크, GPS) 시 경고 (alerts on unexpected activations (mic, GPS))
- **오프라인 툴킷 (Offline Toolkit)**: 나침반, 지도, 문서, 카메라, 암호화된 보관소 (compass, maps, docs, camera, encrypted vault)
- **PTT 허브 (PTT Hub)**: 사용자 정의 가능한 PTT 할당 및 UI 위젯 (customizable PTT assignments and UI widgets)

디자인 원칙 (Design principles):
- 최소한의 백그라운드 활동 (Minimum background activity)
- 모든 센서 및 입출력에 대한 사용자 제어 (User control over all sensors and I/O)
- 간단하고 어두운 테마의 UX (Simple, dark-themed UX)

---

## 📝 5. 타겟 사용자 및 사용 사례 (Target Users & Use Cases)

| 사용자 유형 (User Type) | 요구 사항 (Needs) | Aegis 혜택 (Aegis Benefits) |
|---|---|---|
| 현장 엔지니어 (Field Engineers) | 튼튼한 폰, PTT, 오프라인 지도 (Durable phone, PTT, offline maps) | 보안 탐색 도구를 갖춘 Core/Pro (Core/Pro with secure nav tools) |
| 보안 부대 (Security Forces) | GPS 추적 없음, 빠른 통신, EM 차폐 (No GPS trace, fast comms, EM shield) | 스텔스 모드를 갖춘 Ultra/Guardian (Ultra/Guardian with stealth mode) |
| 활동가 (Activists) | 감시 방지, 프라이버시 우선 (Anti-surveillance, privacy-first) | Aegis OS를 탑재한 Lite/Core (Lite/Core with Aegis OS) |
| 생존주의자 (Preppers) | 오프라인 준비, 긴 배터리 (Offline readiness, long battery) | 태양광 및 모듈형 전원을 갖춘 Pro (Pro with solar & modular power) |
| 언론인 (Journalists) | 안전한 사진 및 메모, 데이터 삭제 (Secure photos & notes, data wipe) | 암호화된 보관소를 갖춘 Pro/Ultra (Pro/Ultra with encrypted vault) |

---

## 🚀 6. 시스템 아키텍처 및 핵심 기술 (System Architecture & Core Technologies)

**시스템 계층 (System Layers):**
1. **하드웨어 플랫폼 (Hardware Platform)**: 러기드 SoC + 강화된 EM 차폐 + 확장 가능한 모듈 (열화상, NV 카메라) (Rugged SoC + Enhanced EM shielding + Expandable modules (thermal, NV cam))
2. **Aegis OS**: 강화된 안드로이드 포크, 실시간 원격 측정 제어, 오프라인 지원 (Hardened Android fork, real-time telemetry control, offline support)
3. **보안 계층 (Security Layer)**:
   - 앱 샌드박싱 (App sandboxing)
   - 긴급 데이터 삭제 (Emergency wipe)
   - 제로-지식 스토리지 (Zero-knowledge storage)
   - 비행기/스텔스 하드웨어 토글 (Airplane/Stealth hard toggles)
4. **사용자 인터페이스 (User Interface)**:
   - 위젯 기반 대시보드 (Widget-based dashboard)
   - PTT 빠른 타일 (PTT Quick Tiles)
   - 오프라인 우선 앱 (Offline-first apps)

**사용된 기술 (Technologies Used):**
- 오픈 소스 안드로이드 AOSP 기반 (Open-source Android AOSP base)
- Zello SDK, Signal Protocol
- 사용자 정의 권한 관리자 (Custom permission manager)
- 전자기 차폐 기술 (Electromagnetic shielding techniques)
- E Ink 잠금 화면 (선택 사항) (E Ink lockscreen (optional variant))

**통합 스택 (Integration Stack):**
- OS 모듈 업데이트를 위한 GitHub CI/CD (GitHub CI/CD for OS module updates)
- USB 또는 신뢰할 수 있는 LAN을 통한 OTA (OTA via USB or trusted LAN)
- 하드웨어 증명을 통한 보안 부팅 (Secure Boot with hardware attestation)

### 🔷 모델 개요 (Models Overview)

| 모델 (Model) | 주요 특징 (Key Features) |
|---|---|
| Lite | 기본적인 생존 중심 스마트폰, 저렴한 가격 (Basic survival-focused smartphone, budget-friendly.) |
| Core | 고해상도 카메라, 광각 렌즈, 향상된 LED 조명 (High-res camera, wide-angle lens, enhanced LED light.) |
| Pro | 저조도 최적화, 후면 물리적 프라이버시 셔터 (Optimized for low-light, physical privacy shutter on rear.) |
| Ultra | 근적외선 지원, UV LED, 하위 티어 기능 모두 포함 (Near-infrared capable, UV LED, all lower-tier features.) |
| Guardian | 풀 IR 카메라 기능 추가, 엘리트 야간 작전 (Adds full IR camera capability, elite night operations.) |

---

## 🔦 7. 손전등/조명 시스템 (Flashlight / Light System)

| 모델 (Model) | 밝기 (Brightness Lumen) | 특징 (Features) |
|---|---|---|
| Lite | 300lm | 기본 손전등 (Basic flashlight) |
| Core | 500lm | 스트로브 추가 (Adds strobe) |
| Pro | 800lm | 적색광 지원 (Red light support) |
| Ultra | 1000lm | UV LED 추가 (Adds UV LED) |
| Guardian | 1000+lm | 풀 IR 조명 기능 추가 (Adds full IR light capability) |

---

## 📸 8. 카메라 시스템 (Camera System)

| 모델 (Model) | 전면 카메라 (Front Camera) | 후면 카메라 (Rear Camera) | 특수 기능 (Special Features) |
|---|---|---|---|
| Lite | 기본 카메라 (Basic camera) | 기본 후면 카메라 (Basic rear camera) | - |
| Core | 고해상도 + 광각 (High-res + wide-angle) | 고해상도 + 광각 (High-res + wide-angle) | - |
| Pro | 저조도 센서 (Low-light sensor) | 물리적 프라이버시 셔터 (Physical privacy shutter) | 야간 촬영 최적화 (Optimized for night shooting) |
| Ultra | 근적외선 지원 (Near-infrared support) | 저조도 + 프라이버시 (Low-light + privacy) | 풀 NIR 야간 촬영 (Full NIR night photography) |
| Guardian | 적외선 센서 (Infrared sensor) | 풀 야간 IR (Full night-capable IR) | 군용 야간 작전 지원 (Military-grade night operation support) |

---

## 🧩 9. 확장 액세서리 (좌측 상단 택티컬 포트) (Expansion Accessories (Top-left Tactical Port))

- **포트 위치 (Port Position)**: 엉킴 방지, 수직 도구 정렬, 촉각 접근을 위한 좌측 상단 (Top-left for tangle-free use, upright tool alignment, and tactile access.)
- **모듈 (Modules)**: 핫스왑 택티컬 모듈을 위한 범용 어댑터 시스템 (Universal adapter system for hot-swapping tactical modules.)

### 🔌 모듈형 액세서리 (Modular Accessories)

- 교체 가능한 안테나 (Swappable antenna)
- 내시경 (모양 유지가 가능한 구부러지는 타입) (Endoscope (bendable with shape retention))
- 3.5mm 이어폰 잭 어댑터 (3.5mm jack adapter)
- CSM 라디오 모듈 (전술 통신 터미널) (CSM radio module (tactical communication terminal))
- 열화상 카메라 (옵션으로 고급 FLIR 포함) (Thermal camera (including optional high-end FLIR))
- 차량용 독 (충전 + CSM 통합) (Car dock (charging + CSM integration))

### 🔧 Gemini’s Suggested Modules

- 외장 배터리 팩 (External battery pack)
- 고성능 마이크/스피커 모듈 (High-performance mic/speaker module)
- 환경 센서 팩 (온도, 가스, 기압) (Environmental sensor pack (temp, gas, baro))
- 고정밀 GPS 모듈 (RTK 지원) (High-precision GPS module (RTK support))
- 암호화된 저장 공간 모듈 (Encrypted storage module)
- 산소 포화도 측정기 모듈 (Pulse oximeter module)
- 태양광 충전 패널 (Solar charging panel)
- 택티컬 그립 & 마운트 시스템 (Tactical grip & mount system)

---

## 🧠 10. UX / 소프트웨어 기능 (UX / Software Features)

- **스텔스 모드 (Stealth Mode)**: 통신, 조명, 화면, LED 개별 토글 (Toggle comms, light, screen, LED individually)
- **사용자 정의 버튼 매핑 (Custom Button Mapping)**: 짧게/길게/두 번 누르기 지원 (Support for short/long/double presses)
- **택티컬 UI (Tactical UI)**: 장갑/햇빛 아래 사용을 위한 큰 아이콘 (Large icons for gloves/sunlight usage)
- **PTT 통합 (PTT Integration)**: Zello + 위젯 지원 (Zello + widget support)

---

## 💵 11. 예상 BOM / 제조 비용 (USD, 대량 생산 ~10,000대 기준) (Estimated BOM / Manufacturing Costs (USD, mass production ~10,000 units))

| 부품 (Component) | Lite | Core | Pro | Ultra | Guardian |
|---|---|---|---|---|---|
| SoC | $20 | $30 | $40 | $50 | $50 |
| RAM + 저장 공간 (Storage) | $15 | $20 | $25 | $30 | $30 |
| 디스플레이 (Display) | $15 | $18 | $20 | $25 | $25 |
| 카메라 (Camera) | $5 | $10 | $18 | $30 | $40 |
| IR/NIR 센서 | - | - | - | $8 | $20 |
| LED 시스템 (System) | $3 | $4 | $6 | $8 | $10 |
| 배터리 (Battery) | $5 | $5 | $5 | $6 | $6 |
| 러기드 케이스 (Casing) | $8 | $8 | $10 | $12 | $15 |
| 기타 센서 (Misc. Sensors) | $3 | $5 | $6 | $8 | $10 |
| 조립 및 테스트 (Assembly & Testing) | $13 | $13 | $16 | $19 | $20 |

### ✅ 총 예상 제조 비용 (Total Estimated Manufacturing Cost)

| 모델 (Model) | 비용 (Cost USD) |
|---|---|
| Lite | ~$87 |
| Core | ~$113 |
| Pro | ~$166 |
| Ultra | ~$226 |
| Guardian | ~$276 |

---

## 🛒 12. 예상 소매 가격 (40–60% 마진) (Expected Retail Pricing (40–60% margin))

| 모델 (Model) | MSRP (USD) |
|---|---|
| Lite | $149 – $179 |
| Core | $199 – $229 |
| Pro | $279 – $329 |
| Ultra | $399 – $449 |
| Guardian | $499 – $599 |

---

## 🧭 13. 다음 단계: 프레젠테이션 슬라이드 (Next Step: Presentation Slides)

# Aegis Tactical Smartphone Pitch Deck

---

## • Problem Statement  
### 왜 기존 스마트폰은 현장 작전/생존용으로 부적절한가?  
기존 스마트폰은 현장 작전/생존용으로써의 내구성이 부족합니다.  
그 외에도, 빠르게 손전등을 키는 것, 빠르게 연락을 취하는 것, 전자기파를 즉시 차단하는 것 등이  
불편한 UI에 가로막혀 있거나, 아예 기능이 존재하지 않기도 합니다.  

---

## • Aegis as the Solution  
### Aegis는 어떤 문제를 해결하는가?  
- **PTT 버튼** 탑재로 위급상황에서도 즉시 연락 가능.  
- **프로그래머블 버튼**으로 손전등, SOS, 전자기파 차단 등을 즉시 실행.  
- **전 모델 공통 러기드 설계**로 생존/공사/전장 환경에서도 신뢰 가능.

---

## • Product Line Overview  
### Lite / Core / Pro / Ultra / Guardian 모델 차별화  

- **Lite**: 입문자용, Aegis 생태계의 매력에 빠져드는 입구.  
- **Core**: 실사용자층(군경, 마니아 등)에 어필, 브랜드의 중심.  
- **Pro**: 전문가용, 다기능/고성능, 독자적 생김새와 기능 탑재.  
- **Ultra**: 민간 최고급 모델, 전략적 통제 기능 집약.  
- **Guardian**: 군경/보안 특화형, 위장 가능 외관, 야간 작전 특화.

---

## • Tactical Modularity  
### 모듈식 확장 시스템의 강점  

- 기능 확장을 위한 **상단 왼쪽 포트** 탑재.  
- 기능 분리로 **불필요한 비용 절감**, 생태계 유지.  
- **타사 대비 설계 편의성** 및 전술적 직관성 강조.

---

## • User Experience  
### UX, Stealth Mode, PTT 연동 등  

- **집중도 중심 UI**: 큰 아이콘, 작은 폰트 등 시선 유도 설계.  
- **Stealth Mode**: 완전 차단 / 소리&화면만 제한 모드 제공.  
- **PTT 연동**: 1회 - 무전 / 2회 - 상대 선택 / 5회 - SOS 전송 등.

---

## • Target Markets  
### 누구를 위한 제품인가?  

- 군/경/구조대/보안 요원  
- 생존 전문가/프리퍼  
- 저널리스트/의사  
- 전술적 기기에 매력을 느끼는 일반 소비자  

---

## • Profitability  
### 제조원가 vs 예상판매가 / 수익률 시뮬레이션 (별도 시트로 제공)

---

## • Competitive Comparison  
### Sonim, CAT 등과 비교한 차별성  

- **프라이버시 중심 설계**  
- **물리적 버튼 기반 즉시성**  
- **획기적인 UI / 인체공학적 설계**  
- **직관적인 모듈 확장 시스템**  

---

## • Launch Plan & Branding  
### 브랜딩 방향성  

- “위험할 땐 PTT”  
- “통제할 수 없는 세계, 방패는 곧 언어다.”  
- 위계질서식 고급화 전략, 복잡하지 않은 생태계 유지.  

### 마케팅 초기 전략  

- **Lite / Core** 모델로 사용자 기반 확보.  
- 생태계 적응 후 **Pro / Ultra**로 자연스러운 확장.  
- 군경 대상 **Guardian** 커스텀형으로 공식 수요 확보.

---


## Aegis Phone : Ultimate Rugged Smartphone Concept

### 개요 (Overview)
Aegis는 재난 지역, 현장 임무 또는 전투 시나리오와 같은 고위험 환경을 위해 설계된 전문가급 초고성능 러기드 스마트폰 컨셉입니다. 모듈성, 내구성, 전술 통신 및 자가 지속 가능성을 강조합니다.

### 1. 외부 디자인 (External Design)

#### A. 하우징 (Housing)
- 고무 처리된 범퍼가 있는 군용 강화 폴리머 프레임 (Military-grade reinforced polymer frame with rubberized bumpers)
- 탄소 섬유 및 알루미늄 합금 구조 지지대 (Carbon fiber and aluminum alloy structural supports)
- 방수, 방진, 충격 방지 (IP69K, MIL-STD-810H) (Waterproof, dustproof, shockproof (IP69K, MIL-STD-810H))

#### B. 디스플레이 (Display)
- 5.5인치 Full HD IPS 또는 OLED, 사파이어 글래스, 장갑 호환 터치스크린 (5.5” Full HD IPS or OLED, Sapphire glass, glove-compatible touchscreen)
- 자동 밝기 조절 기능으로 햇빛 아래에서도 잘 보임 (Sunlight-readable with auto brightness)
- 젖거나 장갑을 낀 손으로 사용하기 위한 터치 잠금 버튼 (Touch lock button for use with wet or gloved hands)

#### C. 버튼 및 포트 (Buttons & Ports)
- 오버사이즈 촉각 버튼 (PTT, SOS, 전원, 볼륨) (Oversized tactile buttons (PTT, SOS, Power, Volume))
- 사용자 정의 가능한 "택티컬 액션 버튼" (Customizable “Tactical Action Button”)
- 마그네틱 충전 옵션이 있는 밀봉된 USB-C 포트 (Sealed USB-C port with magnetic charging option)
- 3.5mm 이어폰 잭 (스크류 캡 밀봉) (3.5mm jack (screw-cap sealed))

### 2. 내부 하드웨어 (Internal Hardware)

#### A. CPU / RAM / 저장 공간 (Storage)
- Qualcomm Snapdragon 8 Gen 시리즈 (Qualcomm Snapdragon 8 Gen-series)
- 8GB / 12GB RAM 옵션 (8GB / 12GB RAM options)
- 128GB / 256GB 저장 공간 + 최대 2TB MicroSD (128GB / 256GB storage + MicroSD up to 2TB)

#### B. 배터리 (Battery)
- 10,000mAh 탈착식 리튬 이온 배터리 (10,000mAh removable Li-ion battery)
- 핫스왑 지원 (Hot-swap supported)
- 태양광 충전 백팩 패널 인터페이스 (Solar-charging backpack panel interface)

#### C. 오디오 / 센서 (Audio / Sensors)
- 듀얼 전면 스피커 (크고 선명함) (Dual front-facing speakers (LOUD + clear))
- 노이즈 캔슬링 기능이 있는 트리플 마이크 배열 (Triple mic array with noise cancellation)
- 후면 레이더 센서 / 열화상 카메라 모듈 (모듈형) (Rear radar sensor / Thermal camera module (modular))
- 기압, UV, 습도, 자이로스코프 및 고도계 센서 (Air pressure, UV, humidity, gyroscope, and altimeter sensors)

### 3. 소프트웨어 기능 (Software Features)

#### A. OS
- 보안 OTA 업데이트가 적용된 강화된 Android 14 (AOSP 기반) (Hardened Android 14 (AOSP-based) with secure OTA updates)
- 보안 부팅 + 암호화된 저장 공간 (Secure boot + encrypted storage)
- 키오스크 모드 및 게스트 프로필 (Kiosk mode and guest profiles)

#### B. 통신 스위트 (Communication Suite)
- 내장된 Zello PTT 통합 (Built-in Zello PTT integration)
- LoRa를 통한 오프라인 메시 네트워크 기능 (옵션 추가 기능) (Offline mesh-network capability via LoRa (optional add-on))
- 듀얼 물리 SIM + eSIM (Dual physical SIM + eSIM)
- Wi-Fi Direct를 통한 암호화된 파일 공유 (Encrypted file sharing over Wi-Fi Direct)

#### C. 전술 및 현장 도구 (Tactical & Field Tools)
- 스마트 헬멧 또는 안경을 통한 HUD 오버레이 호환 (HUD overlay compatible (via smart helmet or glasses))
- 자동 위치 비콘 기능이 있는 SOS 기능 (SOS function with auto-location beacon)
- 전술 지도 인터페이스 (Tactical map interface)
- 로컬 전용 로그북, 그리기 및 경로 표시 앱 (Local-only logbook, drawing & route marking app)

### 4. 모듈성 및 액세서리 (Modularity & Accessories)

#### A. 추가 기능 모듈 (Add-on Modules)
- 열화상 카메라 (Thermal camera)
- LoRa 메시 통신 장치 (LoRa mesh communicator)
- 확장 배터리 팩 (Extended battery pack)
- 후면 레이더 / 모션 센서 유닛 (Rear radar / motion sensor unit)

#### B. 백팩 및 전원 시스템 (Backpack & Power System)
- 태양광 패널 + 배터리 독이 있는 백팩 (Backpack with solar panel + battery dock)
- 유선 냉각 팬 및 식품 보존 시스템 인터페이스 (Wired cooling fan and food preservation system interface)
- USB 허브 (백팩 하네스에 통합) (USB hub (integrated into backpack harness))

### 5. 사용 사례 시나리오 (Use-Case Scenarios)
- 재난 대응 (Disaster Response): 강력한 PTT, GPS 로깅, 열화상 이미징 (Strong PTT, GPS logging, thermal imaging)
- 야생 트레킹 / 생존 (Wilderness Trekking / Survival): 태양광 충전, 방수, 오프라인 도구 (Solar charge, waterproofing, offline tools)
- 전투 또는 전술적 사용 (Combat or Tactical Use): HUD 인터페이스, 암호화된 통신, 후방 모션 센서, 견고한 컨트롤 (HUD interface, encrypted communication, rear motion sensor, rugged controls)

### 6. UI / UX 주요 사항 (UI / UX Highlights)
- 장갑을 낀 손에 최적화된 최소한의 빠른 인터페이스 (Minimalist, fast interface optimized for gloved hands)
- 손전등, 화면 잠금, PTT, SOS 빠른 토글 (Quick toggles for flashlight, lock screen, PTT, SOS)
- 대시보드 뷰: 배터리, 온도, 나침반, 날씨, 후방 센서 피드 (Dashboard view: battery, temp, compass, weather, rear sensor feed)
- 지도, 라디오 및 임무 노트에 액세스하기 위한 간단한 3번 스와이프 제스처 (Simple 3-swipe gesture to access maps, radio, and mission notes)

### 7. 예상 가격 (Estimated Pricing)

| 구성 요소 (Component) | 예상 비용 (Est. Cost USD) |
|---|---|
| 핵심 폰 유닛 (Core Phone Unit) | $450 - $600 |
| 열화상 모듈 (Thermal Module) | $120 |
| 태양광 백팩 시스템 (Solar Backpack System) | $80 - $120 |
| LoRa 메시 모듈 (LoRa Mesh Module) | $50 |
| 스마트 HUD 헬멧 인터페이스 (Smart HUD Helmet Interface) | $150+ |

### 8. 오픈 소스 / 사용자 정의 계획 (Open Source / Customization Plans)
- 부트로더 잠금 해제 가능 (Bootloader unlockable)
- 루트 액세스 옵션 (보증 무효 경고 포함) (Root-access optional with warranty void warning)
- 모듈형 포트 및 액세서리용 개발자 SDK (Developer SDK for modular ports & accessories)
- 현장 도구 플러그인용 오픈 API (지도, HUD, 센서) (Open API for field tool plugins (maps, HUD, sensors))

### 비전 (Vision)
Aegis 폰은 단순한 폰이 아닙니다. 보호하고, 생존하고, 이끌기 위해 위험 속으로 발을 내딛는 사람들을 위한 생명선, 지휘 장치 및 전술 보조 장치입니다.

**현장 우선. 언제나.** (Field First. Always.)

---

# Aegis-Mobile-Project

🌐 소개 (Introduction)

Aegis Mobile은 현대 사회의 디지털 위협과 감시에 대응하기 위해 탄생한, 전자전 대비형 러기드 스마트폰 생태계입니다. 이 프로젝트는 다음을 목표로 합니다:

📡 전자기장 탐지 회피 및 생존성 (Electromagnetic field detection avoidance and survivability)
🔐 개인 정보 및 통신 보안 극대화 (Maximize personal information and communication security)
🧱 극한 환경에서도 견디는 러기드 설계 (Rugged design to withstand extreme environments)
📢 물리적 PTT 버튼 기반의 커뮤니케이션 효율성 확보 (Secure communication efficiency based on physical PTT button)
🌱 탈중앙화된 생태계 구축 (Establish a decentralized ecosystem)

📦 제품 라인업 (Device Line-up)

1. Aegis Lite
   입문형 러기드 보안폰 (Entry-level rugged security phone)
   IP68, 낙하방지, PTT 버튼, 보급형 보안 안드로이드 (IP68, drop-proof, PTT button, entry-level secure Android)
   가격대: $349 ~ $399

2. Aegis Core
   주력형 중간 가격대 모델 (Mainstream mid-range model)
   향상된 방수·방진 성능, 보안 OS, 중급 하드웨어 성능 (Enhanced waterproof and dustproof performance, secure OS, mid-range hardware performance)
   가격대: $549 ~ $649

3. Aegis Pro
   고급형 전문가용 기기 (High-end professional device)
   열화상 카메라 등 특수 기능, 높은 보안 성능 (Special features such as thermal camera, high security performance)
   가격대: $799 ~ $949

4. Aegis Ultra
   플래그십급 성능 및 보안 (Flagship-level performance and security)
   위성통신, 정밀 GPS, 최고급 재질, 강화된 통신차단/위장 기능 (Satellite communication, precision GPS, top-quality materials, enhanced communication blocking/camouflage features)
   가격대: $1,199 ~ $1,399+

5. Aegis Guardian
   특수 목적형 (정부, 군사, 산업) (Special purpose (government, military, industrial))
   야간 투시, 자가 삭제 기능, 전자기장 위장기술 적용 (Night vision, self-destruct function, electromagnetic field camouflage technology applied)
   가격대: $999 ~ $1,499+

---

## Aegis Mobile Series: 브랜드 철학 & 라인업 개요

### 🔰 철학적 슬로건 (Philosophical Slogans)

"통제할 수 없는 세계, 방패는 곧 언어다." (Korean)
Aegis Mobile은 단순한 스마트폰이 아니다. 정보가 곧 생존이 되는 세상에서, 당신을 지키는 최전선의 방패다. 라인업마다 철학과 목적이 있으며, 사용자의 역할과 환경에 최적화된 성능과 디자인을 제공한다.

### 🌈 색상 & 패턴 아이덴티티 (Color & Pattern Identity)

1. **Aegis Lite – 유연한 관찰자 (The Flexible Observer)**
   - 대표 색상: 회색 + 연한 오렌지 포인트 (Main Colors: Gray + Light Orange Accent)
   - 심볼 패턴: 단순하고 두꺼운 방패 외형만 존재 (로고 없음) (Symbol Pattern: Simple and thick shield outline only (no logo))
   - 브랜드 이미지: 부담 없는 느낌 + 안정감 (Brand Image: 부담 없는 느낌 + 안정감)
   - 의미 부여: "누구보다 조용하게, 그러나 확실하게 존재감을 남긴다." (Meaning: "Quieter than anyone, yet leaves a definite presence.")

2. **Aegis Core – 균형의 방패 (The Shield of Balance)**
   - 대표 색상: 네이비 블루 / 올리브 그린 (Main Colors: Navy Blue / Olive Green)
   - 심볼 패턴: 방패 내부에 링 형태 추가 (Symbol Pattern: Ring shape added inside the shield)
   - 브랜드 이미지: 군경 출신에게 익숙한 색조 + 안정적인 밸런스 (Brand Image: Color tones familiar to military/police personnel + stable balance)
   - 의미 부여: "밸런스는 곧 생존의 기술이다." (Meaning: "Balance is the art of survival.")

3. **Aegis Pro – 결단의 장인 (The Master of Decision)**
   - 대표 색상: 블랙 / 탄색 (Main Colors: Black / Tan)
   - 심볼 패턴: 방패 내부에 원형 3개 + 선들 (Symbol Pattern: Three circles + lines inside the shield)
   - 브랜드 이미지: 실전 전문가용, 기능성과 전장의 블렌딩 (Brand Image: For field experts, blending functionality and the battlefield)
   - 의미 부여: "혼돈 속에서 전문가는 단 한 번의 결단으로 전황을 바꾼다." (Meaning: "In chaos, a professional changes the tide with a single decision.")

4. **Aegis Ultra – 정보의 사령관 (The Commander of Information)**
   - 대표 색상: 멀티캠/보라색, 탄색/보라색 (Main Colors: Multicam/Purple, Tan/Purple)
   - 심볼 패턴: 완전한 Aegis 로고 (Symbol Pattern: Complete Aegis logo)
   - 브랜드 이미지: 사령관, 고급 감시/지휘용. 도시와 야전 모두 대응 가능. (Brand Image: Commander, for advanced surveillance/command. Capable in both urban and field environments.)
   - 의미 부여: "사령관은 절대 드러나지 않는다. 단지, 모든 것을 본다." (Meaning: "The commander never reveals themselves. They simply see everything.")

5. **Aegis Guardian – 자유의 투사 (The Champion of Freedom)**
   - 대표 색상: 사용자 커스텀 (위장/단색/로고 삭제 등 가능) (Main Colors: User custom (camouflage/solid colors/logo removal etc. possible))
   - 심볼 패턴: 완전한 로고 or 삭제 가능 (Symbol Pattern: Complete logo or removable)
   - 브랜드 이미지: 특수 대응군, 군·경 실전 커스터마이징 (Brand Image: Special response units, military/police field customization)
   - 의미 부여: "규칙은 없다. 단지, 싸울 이유만 있다." (Meaning: "There are no rules. Only the reason to fight.")

### 💡 추가 요소 제안 (Additional Element Suggestions)

| 항목 (Item) | 제안 (Suggestion) |
|---|---|
| 로고 위치 (Logo Position) | 후면 상단 모서리 or 하단 중앙, 작고 절제된 디자인 (Rear top corner or bottom center, small and understated design) |
| 패턴 방식 (Pattern Method) | Lite: 무문양 / Pro 이상: 레이저 음각 or 실리콘 텍스처 (Lite: No pattern / Pro and above: Laser engraving or silicone texture) |
| 버튼 포인트 (Button Point) | Ultra/Guardian: 보라색 or 사용자 지정 커스텀 가능 (Ultra/Guardian: Purple or user-specified custom possible) |
| 액세서리 연계 (Accessory Coordination) | 라인업별 컬러 맞춤형 스트랩, 케이스, 마운트 제공 (Provide color-matched straps, cases, and mounts for each lineup) |

**Aegis Mobile – 당신의 언어가, 당신을 지킨다.** (Aegis Mobile – Your language protects you.)

---

## 🧠 핵심 개념 (Core Philosophy)

🔒 **보안 & 프라이버시 중심 (Security & Privacy Focused)**
- 위치 추적 방지, 오프라인 보호 (Prevent location tracking, offline protection)
- 마이크·카메라 하드웨어 차단 기능 (Microphone and camera hardware blocking function)

🧱 **물리적 생존성 강화 (Enhanced Physical Survivability)**
- MIL-STD-810H, IP68~69K 등급 (MIL-STD-810H, IP68~69K rating)
- 극한 온도/수분/충격/전자기 보호 (Protection against extreme temperatures/moisture/shock/electromagnetic fields)

🛰️ **통신 옵션 다양화 (Diversification of Communication Options)**
- LoRa, 위성, mesh 네트워크 지원 (Pro 이상) (LoRa, satellite, mesh network support (Pro and above))
- 블루투스, WiFi 차단 모드 지원 (Bluetooth, WiFi blocking mode support)

🧰 **생존/현장 기능 강화 (Enhanced Survival/Field Functions)**
- SOS 신호, 열화상, 나침반, 도구 앱 번들 (SOS signal, thermal imaging, compass, tool app bundle)
- 재난/야전용 툴킷 지원 (Disaster/field toolkit support)

📚 **오픈소스 & 개발 참여 구조 (Open Collaboration)**
- Github 기반으로 아이디어/기획/프로토타입을 문서화 (Document ideas/plans/prototypes on Github)
- OSS 커뮤니티를 통한 보안 OS 아이디어 제안 (Suggest security OS ideas through the OSS community)
- 추후 관심 있는 하드웨어 개발자와의 협력 기반 형성 (Form a foundation for future collaboration with interested hardware developers)

💭 **다음 목표 (Next Steps)**
- 아이디어 구체화 → 커뮤니티 피드백 수집 (Refine ideas → Collect community feedback)
- UI/UX 목업 제작 (특히 PTT 기능, 전자전 대응 인터페이스) (Create UI/UX mockups (especially PTT function, electronic warfare response interface))
- Aegis OS 방향성 정립 (기존 OS 커스터마이징 또는 미니멀 OS 설계) (Establish the direction of Aegis OS (customize existing OS or design a minimal OS))
- 실현 가능성 시뮬레이션 (Feasibility simulation)

🔥 **"우리는 우리 자신을 보호할 수 있는 도구를 직접 만들 수 있어야 한다."** (Korean)
— Aegis Mobile 프로젝트 철학 (Aegis Mobile project philosophy)

---

# 🛡️ Aegis OS – Rugged & Privacy-Centric Mobile OS

> "위험할 땐 PTT, 그리고 침묵할 땐 완전한 은닉"

Aegis OS는 러기드 폰에 최적화된, 생존과 보안 중심의 안드로이드 기반 운영체제입니다.
디지털 추적을 피하고, 위협 상황에서 빠르게 대응할 수 있도록 설계된 Aegis OS는 생존과 은닉을 위한 새로운 생태계를 제안합니다.

---

## 🔹 컨셉 키워드 (Concept Keywords)
- 전자전 대응 / 프라이버시 최우선 (Electronic warfare 대응 / Privacy First)
- 러기드 하드웨어 친화적 (Rugged Hardware Friendly)
- 직관적 PTT & 스텔스 기능 중심 UX (Intuitive PTT & Stealth Feature Focused UX)
- 전자기장 절감 모드 & 오프라인 대응 (Electromagnetic Field Reduction Mode & Offline Response)
- Zero Trust 기본 철학 (Zero Trust Basic Philosophy)

---

## 🔹 핵심 철학 (Core Philosophy)

> “항상 연결되어 있지 않아도 안전함.”

- 평상시: 일반 스마트폰처럼 사용 가능
- 위협 시: 단 3초만에 **전자적 은닉 모드** 전환
- **디지털 존재 최소화**, **생존성 극대화**

---

## 🔹 시스템 구조 (System Architecture)

### ⚙️ Aegis OS Core
- Hardened Android 기반 (AOSP 또는 GrapheneOS 커스텀)
- Google-free (MicroG 또는 자체 VoIP 지원)

### 🧩 주요 모듈 (Key Modules)

| 모듈 (Module) | 설명 (Description) |
|---|---|
| **Stealth Engine** | 비행기 모드 이상 수준의 완전 은닉 전환 (스케줄 & 버튼 기반) (Complete stealth mode 전환 beyond airplane mode level (schedule & button based)) |
| **Secure PTT Layer** | Zello, TeamTalk 등과 통합. 1초 내 송출 가능 (Integrated with Zello, TeamTalk, etc. Transmit within 1 second) |
| **Aegis Shield** | VPN, Tor, 위치 기반 추적 방지 (VPN, Tor, location-based tracking prevention) |
| **Aegis KillSwitch** | 통신, 마이크, 센서 전원 차단 (물리 or 소프트 기반) (Communication, microphone, sensor power cut (physical or software based)) |

---

## 🔹 UI/UX 디자인 철학 (UI/UX Design Philosophy)

- **스텔스 미니멀 UI**: 화면 꺼짐 상태에서도 무전 가능 (**Stealth Minimal UI**: Walkie-talkie 가능 even when screen is off)
- **PTT 우선 인터페이스**: 홈 화면 위젯으로 무전 대상 지정 (**PTT Priority Interface**: Designate walkie-talkie target with home screen widget)
- **고대비 전술 테마**: 실외 가시성 보장 (**High Contrast Tactical Theme**: Ensures outdoor visibility)
- **정보 은닉 UI**: 개인정보 최소 노출, 위장 모드 포함 (**Information Concealment UI**: Minimize exposure of personal information, includes camouflage mode)

---

## 🔹 기본 내장 앱 (예상) (Pre-installed Apps (Expected))

- 📡 **Aegis Stealth Controller** – 스텔스 모드 관리 및 예약 (Stealth mode management and scheduling)
- 🎙️ **Aegis PTT Hub** – 무전앱 통합 센터 (Walkie-talkie app 통합 center)
- 🔒 **Aegis Vault** – 암호화 파일 보관소 (Encrypted file storage)
- 📁 **LocalOnly Notes** – 오프라인 메모 앱 (Offline memo app)
- 🛰️ **Passive Nav** – 위치 송신 없는 지도 탐색 (Map exploration without location transmission)

---

## 🔹 보안 & 생존 기능 (Security & Survival Features)

- **Offline QR 메신저 / Signal 비접속 채팅**
- **자가 와이프 기능** (비밀번호 or 물리키 트리거)
- **물리 PTT + SOS 버튼 연동**
- **햇빛 최적화 생존 디스플레이 모드**
- **GPS 없는 지형 추적 가능 모드**

---

## 🔹 왜 Aegis OS인가? (Why Aegis OS?)

| 비교 기준 (Comparison Criteria) | 기존 보안 OS (Existing Secure OS) | Aegis OS |
|---|---|---|
| 무전 기능 통합 (Walkie-talkie feature integration) | ❌ 없음 (None) | ✅ 내장 (Built-in) |
| 스텔스 전환 속도 (Stealth mode 전환 speed) | ⏱️ 수 초~분 (Seconds to minutes) | ⚡ 1~3초 (1~3 seconds) |
| 물리 버튼 기반 기능 (Physical button based features) | 🔸 일부 (Some) | ✅ 기본 탑재 (Standard equipped) |
| 러기드폰 친화성 (Rugged phone friendliness) | ❌ 일반 하드웨어 (General hardware) | ✅ 특화 설계 (Specialized design) |
| 생존/전술 UX (Survival/Tactical UX) | ❌ 없음 (None) | ✅ 포함 (Included) |

---

## ✅ 타겟 유저 (Target Users)

- 정치/군사/현장 활동가
- 보안 전문가 및 탐험가
- 저널리스트 & 생존주의자
- 통신 기반 산업 종사자

---

## 🌐 추가 아이디어/기여 (Additional Ideas/Contributions)

> 이 저장소는 **컨셉 아이디어 공유용**입니다.
> 누구나 자유롭게 논의하거나 기여할 수 있어요.

---

**"내가 사서 쓰고 싶은 러기드 OS, Aegis OS"** (Korean)
"The rugged OS I want to buy and use, Aegis OS" (English Translation)

---

# ⚡ Aegis OS 유즈케이스 & 워크플로우 (Use Cases & Workflows)

이 섹션은 Aegis OS의 실제 사용 시나리오를 바탕으로, 각 기능이 어떻게 유기적으로 작동하는지를 설명합니다.

---

## 🔹 시나리오 1: 위협 상황에서 빠르게 은닉 (Scenario 1: Quickly Concealing in Threatening Situations)

> 💡 무전 도중 의심스러운 검문소 출현. 상대가 디지털 장비를 갖췄다면 추적 위험 존재.

### 🔄 워크플로우 (Workflow)
1. 사용자는 **물리 스텔스 버튼**을 3초간 길게 누름
2. 즉시 스텔스 모드 진입:
   - 블루투스, Wi-Fi, 셀룰러 완전 종료
   - 위치 전송 차단 및 로그 삭제
   - 스텔스 알림 토스트: "📵 스텔스 모드가 작동했습니다"
3. 외부에서는 폰이 꺼진 것처럼 보임
4. 내부적으로는 오프라인 노트, 지도, 음성기록 가능
5. **기록은 자동 암호화되고**, 위장 앱(예: 계산기)에 숨겨짐

---

## 🔹 시나리오 2: 팀과 PTT로 빠르게 연락 (Scenario 2: Quickly Contacting the Team via PTT)

> 💡 구조팀과 빠르게 연락 필요. 셀룰러가 불안정하므로 Wi-Fi + 무전 사용.

### 🔄 워크플로우 (Workflow)
1. 홈 화면의 Zello 위젯에서 “🔥1팀 구조” 버튼 터치
2. 즉시 무전 시작: “여기는 동쪽 입구. 상황 확인바람.”
3. 상대방이 응답: “확인. 1분 내 진입 예정.”
4. 자동으로 통신 로그는 내부 암호 저장
5. **Aegis Vault**로 음성 내역 백업 가능

---

## 🔹 시나리오 3: 평상시 로우 프로파일 모드 (Scenario 3: Low Profile Mode in Normal Times)

> 💡 사용자는 일반적인 업무를 하되, 디지털 흔적을 최소화하고자 함.

### 🔄 워크플로우 (Workflow)
1. 부팅 시 “로우 프로파일 모드” 선택
2. Aegis Shield가 자동 작동:
   - VPN + 광고 차단
   - 위치 접근 앱 차단
   - 추적 불가능한 브라우징 (Tor 기반 or Local-only)
3. 앱은 Aegis OS에서 허가된 것만 실행됨
4. 사용자는 로컬 파일/지도/노트만 사용 가능

---

## 🔹 시나리오 4: 긴급상황에서의 SOS 전송 (Scenario 4: Sending an SOS in an Emergency)

> 💡 납치나 위급 상황에서 빠르게 신호 전송 필요.

### 🔄 워크플로우 (Workflow)
1. 전용 SOS 버튼(PTT 겸용) 두 번 누름
2. 즉시 다음 작동:
   - 지정 연락처에 암호화된 메시지 전송 (Zello or Signal)
   - 위치는 마지막 GPS 기준으로만 포함
   - **폰 잠금 + 자동 와이프 예약**
3. 사용자는 위장 앱으로 대피 or 로그 삭제

---

## 📦 기타 특수 기능들 (Other Special Features)

| 기능 (Feature) | 설명 (Description) |
|---|---|
| **자기장 차단 모드 (Magnetic Field Blocking Mode)** | 지문/전자기 센서 감지 중지 (Stop fingerprint/electromagnetic sensor detection) |
| **위장 인터페이스 (Camouflage Interface)** | 계산기/메모 앱 UI에 스텔스 메뉴 숨김 (Hide stealth menu in calculator/memo app UI) |
| **디지털 흔적 이레이저 (Digital Footprint Eraser)** | 최근 사용 기록, 로그, 캐시 등 자동 정리 (Automatically clear recent usage history, logs, cache, etc.) |
| **무전 예약 전송 기능 (Walkie-talkie Scheduled Transmission Function)** | Wi-Fi 연결 시 자동 송출 예약 (Schedule automatic transmission when Wi-Fi is connected) |

---

## 📋 요약 (Summary)

- 위협 상황 → **스텔스 + 로그 제거 + 위장**
- 협업 → **PTT 위젯 + 음성 로그 관리**
- 평시 → **보안 우선 & 로컬 앱 중심**
- 긴급 상황 → **SOS 트리거 + 자동 보안**

---

## 🎨 4. Aegis OS 디자인 시스템 & UI 예시 (Aegis OS Design System & UI Examples)

### ✅ 핵심 컨셉 요약 (Key Concept Summary)

| 스타일 (Style) | 미니멀 + 전술 느낌 (다크 테마 위주) (Minimal + tactical feel (mainly dark theme)) |
|---|---|
| 컬러 팔레트 (Color Palette) | 탄색, 군녹색, 어두운 회색, 옅은 네온 오렌지 (Tan, military green, dark gray, light neon orange) |
| 폰트 (Font) | 굵은 산세리프, 직선적 (예: Orbitron, Roboto Mono) (Bold sans-serif, linear (e.g., Orbitron, Roboto Mono)) |
| 아이콘 (Icon) | 단순하고 기능 중심, 직관적 (Simple and function-oriented, intuitive) |
| 조작 방식 (Operation Method) | 터치 + 물리 버튼 혼합 (장갑 착용 고려) (Touch + physical button mix (considering glove wear)) |
| 애니메이션 (Animation) | 최소화, 반응 속도 우선. 슬라이드 or 페이드 정도만 사용 (Minimize, prioritize response speed. Use only slide or fade) |


### 🛠️ 주요 UI 구성 요소 (Key UI Components)

#### ◾ Aegis Launcher
- 전용 런처: 모든 아이콘은 커스터마이징 가능 (Dedicated launcher: All icons are customizable)
- “Mission Mode” 설정 가능 (테마 + 앱 제한 설정) (“Mission Mode” setting possible (theme + app restriction setting))
- 화면 좌우 슬라이드로 미션 노트, 경로, 무전 채널 전환 (Switch mission notes, routes, and walkie-talkie channels by swiping left or right on the screen)

#### ◾ Zello 전술 위젯 (Zello Tactical Widget)
- 홈 화면에 최대 4명까지 고정 (Fix up to 4 people on the home screen)
- 터치하면 즉시 무전 가능 (Touch to immediately start walkie-talkie)
- 길게 누르면 암호명 변경 가능 (Long press to change code name)
- 상태 아이콘 (온라인 / 미응답 / 무전 중) (Status icons (online / unresponsive / transmitting))

#### ◾ 스텔스 모드 표시 UI (Stealth Mode Display UI)
- 상단에 조용히 나타나는 토스트 알림:
  > 🕶 스텔스 모드 작동 중 (위치, 통신 차단됨)
- 스텔스 상태일 땐 전체 UI 색조가 '차콜 블랙'으로 전환 (When in stealth mode, the entire UI color tone switches to 'charcoal black')

#### ◾ Vault 인터페이스 (Aegis Vault)
- 암호화된 폴더 구조 (Encrypted folder structure)
- 파일 위장 기능: 이미지나 문서로 변장 가능 (File camouflage function: Can be disguised as images or documents)
- Zello 음성 기록, 메모, 지도 좌표 저장 가능 (Can save Zello voice recordings, memos, and map coordinates)
- 진입 시 지문 or 패턴 + 위장 경로 입력 필요 (Requires fingerprint or pattern + camouflage path input upon entry)

#### ◾ 모드 전환 UI (Mode Switching UI)
- 긴급 모드 전환 시, 중앙 팝업:

#### ◾ 위장 UI (Camouflage UI)
- 진입 시 ‘계산기’, ‘파일 탐색기’, ‘기록 지우기’ 등으로 위장 (Disguised as 'Calculator', 'File Explorer', 'Clear History', etc. upon entry)
- 예시:
- 계산기 앱을 열고 1379= 입력하면 Vault 열림 (Open the calculator app and enter 1379= to open Vault)
- 탐색기에서 특정 폴더 열면 Zello 기록 재생됨 (Open a specific folder in Explorer to play Zello recordings)

### 📐 디자인 규칙 요약 (Design Rule Summary)

| 규칙 (Rule) | 설명 (Description) |
|---|---|
| 최소 인터랙션 (Minimum Interaction) | 기능 접근은 1~2 터치 이내 (Function access within 1-2 touches) |
| 고명도 대비 (High Brightness Contrast) | 야외 시인성 확보를 위해 텍스트 대비 높임 (Increase text contrast to ensure outdoor visibility) |
| 피드백 강조 (Emphasis on Feedback) | 무전 성공/실패, 모드 진입 등은 진동 + 시각적 피드백 (Walkie-talkie success/failure, mode entry, etc. are indicated by vibration + visual feedback) |
| 일관된 UI 흐름 (Consistent UI Flow) | 위장-전술-기록 모두 동일한 인터페이스 구성 사용 (Use the same interface structure for camouflage-tactical-record) |

### 🎯 사용자 페르소나 예시 (Example User Personas)

| | |
|---|---|
| 🔧 구조대원 (Rescuer) | 빠른 무전, 위치 공유, 로그 보관 (Quick walkie-talkie, location sharing, log storage) |
| 🎒 생존 전문가 (Survival Expert) | 통신 차단, 로컬 지도, 오프라인 기록 (Communication blocking, local maps, offline records) |
| 🕶 정보 요원 (Intelligence Agent) | 위장 인터페이스, 긴급 로그 삭제, 보안 백업 (Camouflage interface, emergency log deletion, secure backup) |

---

## 🔶 1. 로고 디자인 컨셉 (Aegis 브랜드 상징) (Logo Design Concept (Symbol of Aegis Brand))

- 방패 모양 + 회로 패턴 → 기술 & 방어를 상징 (Shield shape + circuit pattern → symbolizes technology & defense)
- A 모양을 응용한 미니멀 스타일 → ‘Aegis’의 A를 추상화 (Minimal style applying the shape of A → abstracting the A of ‘Aegis’)
- 디지털 느낌의 눈 (감시/보안 상징) → 스텔스 & 감시 회피 기능 강조 (Digital-feeling eye (symbol of surveillance/security) → emphasizes stealth & surveillance evasion functions)

### 💡 옵션: “어둠 속의 방패” 컨셉으로 검정+은색 톤 추천 (Option: Recommend black+silver tone with the “Shield in the Dark” concept)

## 🔷 2. UI/UX 디자인 키워드 (UI/UX Design Keywords)

| 요소 (Element) | 컨셉 설명 (Concept Description) |
|---|---|
| Zello 위젯 중심 (Zello Widget Centric) | 홈 화면에서 물리 PTT 버튼과 연결되는 무전 인터페이스, 빠른 접근 가능 (Walkie-talkie interface connected to the physical PTT button on the home screen, providing quick access) |
| Stealth Toast 알림 (Stealth Toast Notification) | "스텔스 모드 작동 중"이라는 간결한 알림으로 상태 전달 (Conveys status with a concise notification saying "Stealth Mode Activated") |
| 심플 아이콘 디자인 (Simple Icon Design) | 군용/산업용 느낌, 거친 현장에서도 알아보기 쉬운 직관적 디자인 (Military/industrial feel, intuitive design that is easy to recognize even in harsh environments) |
| 다크 테마 기본 (Dark Theme Default) | 은신과 프라이버시 강조, 눈에 부담 적음 (Emphasizes concealment and privacy, reduces eye strain) |
| 에어갭 모드 (Air Gap Mode) | 원터치로 모든 무선 통신 차단 (비행기 모드와 구분됨) (Blocks all wireless communication with one touch (different from airplane mode)) |

## 🔸 3. 슬로건 제안 (국문/영문) (Slogan Suggestions (Korean/English))

| 언어 (Language) | 슬로건 (Slogan) |
|---|---|
| 🇰🇷 한글 | “위험할 땐 PTT” / “디지털 정글의 방패, Aegis” | 
| 🇺🇸 영어 | “When it matters, Push to Talk” / “Your Shield in the Digital Jungle” | 

---
"In an uncontrolled world, the Shield is a language." 
"통제할수 없는 세상, 방패는 곧 언어다."

크래딧: Cloudyelectron, Gemini, ChatGPT

> Document maintained by: Cloudyelectron
> Last Updated: April 2025
