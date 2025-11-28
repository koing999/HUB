# 투자 경제성 분석 대시보드 - PRO Edition

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Stars](https://img.shields.io/github/stars/koing999/HUB?style=social)](https://github.com/koing999/HUB)
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fkoing999%2FHUB&label=방문자&countColor=%23263759&style=flat&labelColor=%23d9e3f0)

**브라우저만 있으면 바로 사용 가능한 투자 분석 도구**  
설치 불필요 | 완전 무료 | 오픈소스

---

## 🚀 빠른 시작

- **라이브 데모 (한국어)**: https://hub-999-rvi8.vercel.app/ko/
- **사용법 문서**: ./USAGE_GUIDE.md
- **English Version**: ../en/
- **GitHub**: https://github.com/koing999/HUB

---

## ✨ 주요 기능

### 📊 핵심 투자지표 자동 계산
- **NPV (순현재가치)** - 투자 가치 정량화
- **IRR (내부수익률)** - 투자 수익성 평가
- **회수기간 (Payback Period)** - 투자금 회수 시점
- **손익분기점 (BEP)** - 최소 매출 목표

### 🎲 리스크 분석 도구
- **Monte Carlo 시뮬레이션** - 1,000회 시나리오 자동 생성
- **1-Way 민감도 분석** - 단일 변수 영향 분석
- **2-Way 민감도 분석** - 복합 변수 영향 3D 히트맵

### 💼 실무 최적화 기능
- **WACC 자동 계산** - 12개 산업군 베타 프리셋 제공
- **시나리오 비교** - 낙관/기본/보수 동시 비교
- **Excel/PDF 내보내기** - 보고서 자동 생성
- **프로젝트 저장/불러오기** - 브라우저 로컬 저장

---

## 🎯 이런 분들에게 추천

✅ 스타트업 투자 IR 자료 준비  
✅ 사업 타당성 분석 (Feasibility Study)  
✅ 프로젝트 경제성 평가  
✅ 투자 심사역/VC/회계사/컨설턴트  
✅ MBA/재무 관리 학습자

---

## 🛠️ 기술 스택

| 항목 | 기술 |
|------|------|
| **Frontend** | HTML5, CSS3 (Tailwind), Vanilla JavaScript |
| **차트** | Chart.js |
| **엑셀 처리** | SheetJS (xlsx.js) |
| **배포** | Vercel (무료) |

**⚡️ 특징:**
- 100% 프런트엔드 (서버 불필요)
- 데이터 외부 전송 없음 (브라우저 내 처리)
- 모바일 반응형 UI

---

## 📖 사용 방법

### 옵션 1: 온라인 사용 (권장)
1. https://hub-999-rvi8.vercel.app/ko/ 접속
2. 템플릿 다운로드 → Excel 입력 → 업로드
3. WACC 설정 → 시나리오 선택 → 결과 확인

### 옵션 2: 로컬 실행
```bash
git clone https://github.com/koing999/HUB.git
cd HUB/ko
# index.html 파일 브라우저로 열기
```

---

## 💱 다중 통화 지원

**모든 통화 사용 가능!**

통화 단위와 상관없이 사용 가능합니다. 원하는 통화로 입력하세요:
- 💵 **USD** - 미국 달러
- 💶 **EUR** - 유로
- 💷 **GBP** - 영국 파운드
- 💴 **JPY** - 일본 엔
- 🇰🇷 **KRW** - 한국 원
- 🇧🇷 **BRL** - 브라질 헤알
- 🇲🇽 **MXN** - 멕시코 페소
- 🇨🇳 **CNY** - 중국 위안
- **그 외 모든 통화!**

💡 **팁**: 투자금, 매출 등 모든 입력값을 동일한 통화로 입력하면, 결과도 해당 통화로 나옵니다.

---

## 📐 계산 방법론

### NPV (Net Present Value)
```
NPV = Σ (FCFₜ / (1+WACC)ᵗ) - 초기 투자액
```

### IRR (Internal Rate of Return)
```
0 = Σ (FCFₜ / (1+IRR)ᵗ) - 초기 투자액
(반복법으로 IRR 계산)
```

### WACC (Weighted Average Cost of Capital)
```
WACC = (E/V × Re) + (D/V × Rd × (1-Tc))
- Re (자기자본비용) = CAPM 모델 적용
- Rd (타인자본비용) = 회사채 수익률 기준
```

---

## 🧪 고급 기능 상세

### Monte Carlo 시뮬레이션
- **실행 횟수**: 1,000회
- **변동성 적용**: CAGR ±20%, 영업이익률 ±10%
- **출력**: NPV 확률 분포, 신뢰구간, 리스크 지표

### 2-Way 민감도 분석
- **분석 범위**: 기준값 ±50% (10% 단위)
- **시각화**: 3D 히트맵 (빨강=위험, 파랑=기회)
- **축 변수**: 매출 CAGR × 영업이익률

---

## 🔒 데이터 보안

- ✅ **완전 오프라인 처리** - 모든 계산은 브라우저 내에서 실행
- ✅ **데이터 미전송** - 서버로 정보 전송 없음
- ✅ **로컬 저장** - 프로젝트 저장 시 브라우저 LocalStorage 사용

---

## 📦 Excel 템플릿 형식

```
| 연도 | 매출(억원) | 영업이익률(%) |
|------|------------|---------------|
| 1    | 100        | 10            |
| 2    | 120        | 12            |
| ...  | ...        | ...           |
```

- **다운로드**: 대시보드 상단 '템플릿' 버튼 클릭
- **예시 데이터**: 10년 샘플 포함 (CAGR 20%)

---

## 🤝 기여 방법

1. 이 저장소를 Fork
2. 새 브랜치 생성 (`git checkout -b feature/새기능`)
3. 변경사항 커밋 (`git commit -m '새 기능 추가'`)
4. 브랜치에 Push (`git push origin feature/새기능`)
5. Pull Request 생성

---

## 💖 프로젝트 후원하기

이 프로젝트가 도움이 되셨나요? ☕

### ⚡ 간편 후원 (PayPal)
전 세계 어디서나 즉시 후원 가능!

[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/LOCUJO)

👉 **[paypal.me/LOCUJO](https://paypal.me/LOCUJO)**

---

### 💎 정기 후원 (GitHub Sponsors)
월 정기 후원으로 지속 가능한 개발을 지원해주세요!

<a href="https://github.com/sponsors/koing999" target="_blank">
  <img src="https://img.shields.io/badge/GitHub_Sponsors-EA4AAA?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Sponsors로 후원하기">
</a>

---

### 🙏 여러분의 후원은 이렇게 사용됩니다

- 🚀 **새로운 기능 개발**
  - 고급 시나리오 분석 도구
  - AI 기반 투자 추천
  - 실시간 데이터 연동

- 📚 **문서 및 튜토리얼 개선**
  - 사용 가이드 영상 제작
  - 케이스 스터디 추가
  - 다국어 지원 확대

- 🐛 **버그 수정 및 안정성 개선**
  - 빠른 이슈 대응
  - 성능 최적화
  - 보안 강화

- 💬 **커뮤니티 지원**
  - 기술 지원
  - 기능 요청 반영
  - 정기 업데이트

감사합니다! 🙏

---

## 📧 문의

- **Email**: koing756@naver.com
- **GitHub Issues**: [이슈 등록하기](https://github.com/koing999/HUB/issues)
- **후원 문의**: koing756@naver.com

---

## 📜 라이선스

**MIT License** - 상업적 사용, 수정, 배포 자유

자세한 내용: [LICENSE](https://github.com/koing999/HUB/blob/main/LICENSE)

---

## 📊 로드맵

- [x] NPV/IRR 기본 계산
- [x] Monte Carlo 시뮬레이션
- [x] 2-Way 민감도 분석
- [x] Excel 템플릿 강화 (10년 예시)
- [ ] 시나리오 대시보드 UI 개선
- [ ] PDF 보고서 자동 생성 (고급)
- [ ] 다국어 지원 확대 (중국어, 일본어)

---

**⭐️ 도움이 되셨다면 GitHub Star를 눌러주세요!**  
https://github.com/koing999/HUB

---

*본 도구는 교육 및 참고 목적으로 제공되며, 실제 투자 결정 시 전문가 자문을 권장합니다.*
