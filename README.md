# Experience Driven Architectural Design Process

경험 주도 건축 설계 프로세스 — 인터랙티브 프로세스 모델.

사용자 경험에서 출발해 건축을 설계하려는 누구나 따를 수 있도록 제안하는 **일반 프로세스**입니다.
Design Thinking을 건축 실무 단계에 맞춰 **0. Diagnosis부터 6. Deliver까지 일곱 단계**로 확장했습니다.

> 특정 프로젝트의 진행 현황이 아니라 프로세스 정의 그 자체입니다.
> 어떤 단계가 완료되었는지를 나타내는 표시는 두지 않습니다.

## 단계 구성

| 건축 단계 | 프로세스 노드 |
|---|---|
| Pre-design | 0. Diagnosis → 1. Empathize |
| Programming | 2. Define → Insight |
| Schematic Design | 3. Ideate |
| Design Development | 4. Prototype → 5. Evaluate |
| Construction Documents | 6. Deliver → Final Design → POE Data |

POE Data는 다시 **1. Empathize**로 순환합니다.

## 구성

| 섹션 | 내용 |
|---|---|
| 프로세스 모델 | 7단계 노드. 클릭하면 목적·방법·담당(사람/AI)·근거·산출물이 펼쳐집니다 |
| 피드백 루프 | 원본 모델의 "Missing connection to Empathy"를 피드백 루프로 닫은 경로. 토글로 켜고 끌 수 있습니다 |
| 한눈에 보기 | 경험 문장 18장이 KJ법으로 묶여 올라가 수치화 판정을 받는 애니메이션 |
| 적용 사례 | 단독주택 예시에서 경험 진술이 설계 수치가 되기까지의 4단계 추적 |
| 참고문헌 | 인용 문헌과 저널 등급, 그리고 **아직 확보하지 못한 것** |

## KJ법에 대하여

이 프로세스의 ② 단계는 **분류 항목을 미리 정해 두지 않습니다.**
라벨을 전부 펼치고 → 끌리는 것끼리 모은 **뒤에** → 그 뭉치를 한 문장으로 요약한 **표찰**을 써 붙이고 →
표찰끼리 같은 방식으로 다시 모아 올라갑니다. 어디에도 붙지 않는 카드는 **외톨이로 그대로 둡니다.**

## 기술

단일 HTML 파일. 외부 라이브러리 없이 순수 HTML/CSS/JS이며 브라우저 저장소를 사용하지 않습니다.
다크모드와 반응형을 지원합니다.

## 원본 모델

이 프로세스의 출발점은 아래 논문의 Fig. 4입니다. 해당 도판은 구독 저널 수록 그림이라
페이지에 복제하지 않고 **출처만 표기**합니다.

> Hettithanthri, U., Hansen, P., & Munasinghe, H. (2023).
> *Exploring the architectural design process assisted in conventional design studio: a systematic literature review.*
> International Journal of Technology and Design Education, 33(5), 1835–1859.
> [doi:10.1007/s10798-022-09792-9](https://doi.org/10.1007/s10798-022-09792-9) · SSCI Q1 · SCIE

"Missing connection to the empathising phase"라는 표현은 이 논문 저자들이 명명한 것입니다.

## HX 지표

Insight 단계의 네 지표는 아래 논문 Table 1의 분류를 따릅니다.

> Ergan, S., Shi, Z., & Yu, X. (2018).
> *Towards quantifying human experience in the built environment: A crowdsourcing based experiment to identify influential architectural design features.*
> Journal of Building Engineering, 20, 51–59.
> [doi:10.1016/j.jobe.2018.07.004](https://doi.org/10.1016/j.jobe.2018.07.004) · SCIE · Q1

`restorativeness` · `stress and anxiety` · `aesthetics and pleasure` · `motivation`
각 지표의 설계 특성도 같은 표를 따르며, 본 프로세스가 덧붙인 항목은 페이지에서 회색으로 구분해 표시합니다.

## 진행 중

- 0. Diagnosis · 5. Evaluate · 6. Deliver의 **근거 칸은 아직 비어 있습니다.**
- Wicked Problem(Rittel & Webber, 1973), Kano(1984), Space Syntax(Hillier & Hanson, 1984) **원전 미확보**.
- "수치화 가능/불가"를 **가르는 판별 기준**을 제시한 선행 연구는 아직 찾지 못했습니다.
- 적용 사례는 **프로세스 검증용 예시**이며 실제 프로젝트가 아닙니다.
