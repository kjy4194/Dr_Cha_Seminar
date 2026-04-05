# LP (Linker Payload) 기술 개발 과제

## 개요
- **과제명**: ADC (Antibody-Drug Conjugate) 제조를 위한 Linker-Payload 자동화 공정 장비 개발
- **소속**: KIMM 나노디스플레이실
- **시작일**: 2026-01-01
- **목표 완료일**: 2026-12-31
- **상태**: 진행 중 🔄

## 용어 정의

| 용어 | 설명 |
|------|------|
| **ADC** | Antibody-Drug Conjugate. 항체에 약물(Payload)을 링커(Linker)로 결합한 표적 항암제 |
| **Linker** | 항체와 약물을 연결하는 화학적 구조체. 절단 가능(cleavable) / 비절단(non-cleavable) 타입 |
| **Payload** | 세포독성 약물 (예: MMAE, DM1 등). 암세포에 전달되어 세포 사멸 유도 |
| **DAR** | Drug-to-Antibody Ratio. 항체 1개당 결합된 약물 수 (통상 2~8) |
| **Conjugation** | 항체와 Linker-Payload를 결합하는 공정 |

## 연구 배경
ADC는 차세대 항암 치료제로 글로벌 시장이 급성장 중이며,
Linker-Payload 합성 및 Conjugation 공정의 정밀 자동화가 생산성과 품질의 핵심이다.
바이오 파운드리 기반의 자동화 장비를 활용하여 LP 합성·접합 공정을 고도화한다.

## 핵심 기술 영역
- Linker-Payload 합성 자동화 (액체 핸들링 로봇 활용)
- Conjugation 공정 최적화 (DAR 제어, 반응 조건 자동화)
- 공정 중 품질 모니터링 (UV-Vis, SEC-HPLC 인라인 분석)
- 비전 기반 바이알(vial) 충진 검사 자동화
- AI 기반 공정 파라미터 최적화 (DAR 균일성 향상)

## 세부 과업

### 1단계: 문헌 조사 및 요구사항 분석 (완료)
- [x] ADC 제조 공정 국내외 동향 조사
- [x] Linker 종류별 특성 분석 (cleavable vs non-cleavable)
- [x] Payload 취급 안전 요구사항 검토 (고독성 물질 격리 환경)
- [x] 자동화 장비 요구사항 정의

### 2단계: 자동화 공정 장비 설계 (진행 중)
- [x] LP 합성용 액체 핸들링 로봇 사양 선정
- [ ] Conjugation 반응기 자동 제어 모듈 설계
- [ ] 인라인 품질 모니터링 시스템 설계 (SEC-HPLC 연동)
- [ ] 고독성 Payload 격리 환경(Isolator) 통합 설계

### 3단계: 프로토타입 제작 및 검증 (예정)
- [ ] 자동화 장비 프로토타입 제작
- [ ] DAR 균일성 검증 실험 (목표: DAR 4.0 ± 0.5)
- [ ] 수율 및 순도 분석 (목표: 순도 95% 이상)
- [ ] 처리량 성능 검증 (기존 수동 공정 대비 40% 향상 목표)

### 4단계: 최적화 및 보고 (예정)
- [ ] AI 기반 공정 파라미터 최적화 적용
- [ ] 기술 보고서 작성
- [ ] 특허 출원 (LP 자동화 공정 장비)

## 주요 참고 자료
- 관련 논문: Journal of Medicinal Chemistry, Bioconjugate Chemistry
- 국내외 ADC 제조 가이드라인 (FDA, EMA)
- 특허: ADC Conjugation 자동화 관련 특허 수집 중

## 안전 관리 사항
> ⚠️ Payload는 고독성 세포독성 물질로 취급 시 격리 환경(Isolator/RABS) 필수
- [ ] 고독성 물질 취급 SOP 수립
- [ ] 격리 장비(Isolator) 검증 완료
- [ ] 담당자 안전 교육 이수

## 관련 노트
- [[바이오파운드리_장비기술개발]]
- [[연구방법론]]
- [[AI_활용_역량]]

## 성과 지표
- [ ] Conjugation 공정 자동화 장비 프로토타입 완성
- [ ] DAR 균일성 목표 달성 (4.0 ± 0.5)
- [ ] 처리량 기존 대비 40% 이상 향상
- [ ] 기술 보고서 2편, 특허 출원 1건
