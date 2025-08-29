# 건물형 태양광발전 - 가이드 북 (Building-Integrated Photovoltaics: A Guidebook) - Grasshopper를 활용한 파라메트릭 BIPV 설계

이곳은 **'건물형 태양광발전 - 가이드 북 (Building-Integrated Photovoltaics: A Guidebook)'** 의 **4.2장, "Grasshopper를 활용한 파라메트릭 BIPV 설계"** 에서 사용되는 예제 파일을 제공하는 공식 GitHub 저장소입니다.

본 예제는 건축가가 설계 초기 단계에서 직접 BIPV의 성능을 시뮬레이션하고, 데이터 기반의 디자인 의사결정을 내리는 과정을 체험할 수 있도록 돕는 것을 목표로 합니다.

---

## 📂 파일 구성 (Release)

* **JL Simplified BIPV Simulation v1.0.0.3dm**: 예제에서 사용되는 기본 3D 모델이 포함된 Rhino 파일입니다. (주변 건물, 분석 대상 매스 등)
* **JL Simplified BIPV Simulation v1.0.0.gh**: Ladybug Tools를 활용한 BIPV 일조시간 및 잠재 발전량 분석 워크플로우가 담긴 Grasshopper 스크립트 파일입니다.

---

## 💻 사전 준비 사항 (Prerequisites)

이 예제 파일을 원활하게 사용하기 위해서는 아래의 소프트웨어 및 플러그인이 반드시 설치되어 있어야 합니다.

1.  **Rhino 8** (또는 그 이상 버전)
2.  **Grasshopper** (Rhino 7 이상 버전에 기본 내장)
3.  **Ladybug Tools 1.8.0**
    * [Ladybug Tools 다운로드 링크](https://github.com/ladybug-tools/lbt-grasshopper/wiki/1.1-Windows-Installation-Steps)
4.  **Ladybug Tools 연동 프로그램**: Ladybug Tools의 모든 기능을 사용하기 위해 필요한 필수 연동 프로그램들입니다. **오류 방지를 위해 반드시 아래 링크의 'Compatibility Matrix'를 확인하고, Ladybug Tools 1.8.0 버전에 맞는 정확한 버전으로 설치해야 합니다.**
    * Radiance
    * OpenStudio
    * OpenStudio App
    * URBANopt CLI
    * [연동 프로그램 버전 확인 및 설치 링크](https://github.com/ladybug-tools/lbt-grasshopper/wiki/1.4-Compatibility-Matrix)

---

## 🚀 사용 방법 (How to Use)

1.  이 저장소의 파일들을 다운로드합니다. (페이지 우측 상단의 `Code` -> `Download ZIP` 클릭)
2.  '사전 준비 사항'에 명시된 모든 프로그램과 플러그인이 정상적으로 설치되었는지 확인합니다.
3.  Rhino에서 `BIPV_Analysis_Example.3dm` 파일을 엽니다.
4.  Rhino 명령어 입력창에 `Grasshopper`를 입력하여 Grasshopper 창을 엽니다.
5.  Grasshopper 메뉴의 `File` > `Open Document...`를 통해 `BIPV_Analysis_Workflow.gh` 파일을 엽니다. (혹은 Drag&Drop)
6.  교재의 **4.2장**에 설명된 1단계부터 10단계까지의 지침에 따라 스크립트를 순서대로 실행하며 파라메트릭 BIPV 설계 과정을 학습합니다.

---

## 📝 참고 사항 (Notes)

* 본 스크립트는 교육 및 개념 이해를 돕기 위해 간소화되었습니다. 실제 복잡한 프로젝트에 적용할 경우, 추가적인 수정 및 최적화 과정이 필요할 수 있습니다.
* 스크립트나 예제 파일에 대한 질문이나 피드백은 본 저장소의 'Issues' 탭을 통해 남겨주시면 감사하겠습니다.
