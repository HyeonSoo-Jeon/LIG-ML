# 🚀 LIG-ML: Laser-Induced Graphene 기반 진동 센서 및 AI 예지보전

**2026학년도 1학기 대학원 튜터링 프로젝트** LIG 센서 제작부터 Edge AI(TinyML)를 활용한 실시간 고장 진단 시스템 구축까지의 전 과정을 다룹니다.

---

## 👥 팀 구성
* **팀명**: BTS (Best Tutoring System)
* **튜터**: 전현수
* **튜티**: 안세응, 이학준

---

## 📅 활동 로드맵 (10주 과정)

### **Phase 1: 센서 설계 및 제작 (1~3주차)**
* **1주차:** 오리엔테이션, LIG 선행 연구 조사 및 역할 분담
* **2주차:** 레이저 공정 변수(출력, 속도) 설계 및 센서 구조 최적화 도면 작성
* **3주차:** LIG 센서 제작(PI 필름 패터닝) 및 전기적 특성(Gauge Factor) 평가

### **Phase 2: 데이터 수집 및 전처리 (4~5주차)**
* **4주차:** 휘트스톤 브리지 회로 구성 및 모터 결함(Unbalance 등) 데이터 로깅
* **5주차:** 데이터셋 구축, 시간/주파수 영역(FFT, RMS) 특징 추출 및 PCA 분석

### **Phase 3: AI 모델링 및 최적화 (6~7주차)**
* **6주차:** 머신러닝(SVM, Random Forest) 베이스라인 모델 구축 및 성능 평가
* **7주차:** 딥러닝(CNN, LSTM) 모델 설계 및 하이퍼파라미터 튜닝

### **Phase 4: Edge AI 구현 및 시스템 통합 (8~10주차)**
* **8주차:** **TinyML** 적용 (Edge Impulse 활용 모델 양자화 및 ESP32 탑재)
* **9주차:** 실시간 추론 결과 분석 및 GUI 대시보드(Streamlit) 시각화
* **10주차:** 전체 연구 과정 문서화, 결과 영상 제작 및 최종 리뷰

---

## 🛠 Tech Stack
* **Hardware:** Laser Engraver (CO2/UV), Polyimide Film, ESP32, DAQ
* **Languages:** Python, C/C++
* **AI/ML:** PyTorch/TensorFlow, Scikit-learn, Edge Impulse (TinyML)
* **Tools:** GitHub, Slack, Notion, Streamlit

---

## 🎯 최종 목표 (KPI)
1.  **LIG 센서 최적화:** 고감도 진동 감지가 가능한 최적 레이저 공정 레시피 확보
2.  **고성능 AI 모델:** 90% 이상의 진동 결함 분류 정확도 달성
3.  **On-device AI:** MCU(ESP32) 환경에서 지연 시간 최소화 및 실시간 알림 시스템 구현
