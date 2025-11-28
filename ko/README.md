# 💎 Investment Dashboard

> 30초 만에 IR 자료를 완성하는 무료 투자분석 도구

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/koing999/HUB.svg?style=social&label=Star)](https://github.com/koing999/HUB)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

[English](#english) | [한국어](#korean)

---

<a name="korean"></a>

## 🎯 무엇인가요?

**Investment Dashboard**는 스타트업 IR부터 프로젝트 투자심사까지, 복잡한 재무분석을 30초 만에 완성해주는 웹 기반 대시보드입니다.

### ✨ 주요 기능

- ✅ **NPV/IRR 자동계산** - Newton-Raphson 수렴 방식
- 📊 **몬테카를로 시뮬레이션** - 1000회 반복으로 정확한 리스크 분석
- 🎯 **2-Way 민감도 분석** - 매출 × WACC 교차 분석 히트맵
- 📈 **시나리오 비교** - 보수적/기본/낙관적 자동 계산
- 🔧 **Beta 조정 계산기** - Hamada 공식으로 Levered Beta 산출
- 📥 **엑셀 다운로드** - FCF 테이블 + 분석 요약 자동 생성
- 🎨 **산업별 프리셋** - IT/제조/헬스케어/유통 등 WACC 자동 적용
- 🌐 **100% 브라우저 기반** - 설치 불필요, 데이터 로컬 저장

### 🎬 데모

![Dashboard Screenshot](./screenshots/main-dashboard.png)

**👉 [라이브 데모 체험하기](https://github.com/koing999/HUB)** _(Vercel 배포 후 업데이트 예정)_

---

## 🚀 빠른 시작

### 방법 1: 온라인에서 바로 사용

_Vercel 배포 후 URL 업데이트 예정_

링크 클릭만 하면 끝! 설치 필요 없습니다.

### 방법 2: 로컬에서 실행

```bash
# 1. 저장소 클론
git clone https://github.com/koing999/HUB.git

# 2. 폴더 이동
cd HUB

# 3. HTML 파일 열기
open index.html  # Mac
start index.html # Windows
```

---

## 📖 사용법

### 1️⃣ 기본 설정

- 프로젝트명, 초기투자금액, 내용연수 입력
- 법인세율, 운전자본 비율 설정

### 2️⃣ WACC 계산

- 산업 프리셋 선택 (IT, 제조, 헬스케어 등)
- 또는 직접 입력 (자기자본비용, 타인자본비용, 부채비중)
- Beta 조정 기능으로 Levered Beta 자동 계산

### 3️⃣ 매출 데이터 입력

- **자동 생성**: CAGR 기반 자동 생성 (클릭 한 번)
- **Excel 업로드**: 기존 데이터 불러오기
- **직접 입력**: 테이블에서 수동 입력

### 4️⃣ 시나리오 선택

- 보수적 / 기본 / 낙관적 시나리오 선택
- 각 시나리오별 자동 조정 (영업이익률, WACC)

### 5️⃣ 분석 시작

- 🚀 **분석 시작** 버튼 클릭
- 결과 확인:
  - NPV, IRR, 회수기간, 손익분기점
  - 몬테카를로 시뮬레이션 (1000회)
  - 1-Way / 2-Way 민감도 분석
  - 현금흐름 차트

### 6️⃣ 결과 활용

- 📥 Excel 다운로드 (FCF 테이블 + 요약)
- 💾 프로젝트 저장 (로컬 스토리지)
- 🔄 프로젝트 불러오기

---

## 💼 이런 분들께 추천

| 대상 | 활용 방법 |
|------|-----------|
| 🚀 **스타트업 대표** | IR 자료 준비, 투자 유치 시뮬레이션 |
| 💼 **VC 심사역** | Deal flow 스크리닝, 빠른 밸류에이션 |
| 🎓 **MBA 학생** | 재무분석 실습, 케이스 스터디 |
| 📊 **컨설턴트** | 클라이언트 리포트 작성 |
| 🏢 **기업 전략팀** | 신사업 타당성 분석 |

---

## 🛠️ 기술 스택

- **Frontend**: Pure HTML5 / CSS3 / JavaScript (ES6+)
- **Charts**: Chart.js 3.9.1
- **Excel Export**: SheetJS (xlsx) 0.18.5
- **No Backend**: 100% 클라이언트 사이드 (데이터 로컬 저장)
- **No Dependencies**: 프레임워크 없음 (순수 바닐라 JS)

**왜 순수 JS인가?**
- ✅ 빠른 로딩 (프레임워크 오버헤드 제로)
- ✅ 쉬운 커스터마이징 (코드 한 파일에 전부)
- ✅ 설치 불필요 (HTML 파일 하나면 OK)

---

## 🤝 기여하기

기여는 언제나 환영합니다! 🎉

### 기여 방법

1. 이 저장소를 Fork 하세요
2. Feature 브랜치를 만드세요 (`git checkout -b feature/AmazingFeature`)
3. 변경사항을 커밋하세요 (`git commit -m 'Add some AmazingFeature'`)
4. 브랜치에 Push 하세요 (`git push origin feature/AmazingFeature`)
5. Pull Request를 열어주세요

### 개발 가이드

```bash
# 코드 수정 후 로컬에서 테스트
open index.html

# 수정 사항 확인
# 브라우저 개발자 도구 (F12) 활용
```

### 기여 아이디어

- 🌍 다국어 지원 (영어, 일본어, 중국어)
- 📱 모바일 최적화
- 🎨 다크모드 개선
- 📊 추가 차트 타입 (워터폴, 펀넬 등)
- 🔌 API 연동 (금융 데이터 자동 가져오기)
- 💾 클라우드 저장 기능
- 👥 팀 협업 기능

---

## 📜 라이선스

이 프로젝트는 MIT 라이선스를 따릅니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요.

**간단 요약:**
- ✅ 상업적 이용 가능
- ✅ 수정 가능
- ✅ 배포 가능
- ⚠️ 출처 표시 필요 (Copyright 유지)

---

## 🙏 감사의 말

이 프로젝트는 다음 오픈소스 라이브러리를 사용합니다:
- [Chart.js](https://www.chartjs.org/) - MIT License
- [SheetJS](https://sheetjs.com/) - Apache 2.0 License
- [Tailwind CSS](https://tailwindcss.com/) - MIT License

---

## 📞 문의

- 📧 Email: koing756@naver.com
- 💬 Issues: [GitHub Issues](https://github.com/koing999/HUB/issues)
- 🌐 GitHub: [HUB Repository](https://github.com/koing999/HUB)

**☕ 도움이 되셨다면?**  
[카카오페이로 커피 한잔 사주기](https://qr.kakaopay.com/Ej8t3tRhG) _(선택사항)_

---

## 🌟 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=koing999/HUB&type=Date)](https://star-history.com/#koing999/HUB&Date)

---

<a name="english"></a>

# 💎 Investment Dashboard (English)

> Complete your IR materials in 30 seconds - Free investment analysis tool

## 🎯 What is it?

**Investment Dashboard** is a web-based financial analysis tool that helps founders, investors, and analysts evaluate investment opportunities in 30 seconds.

## ✨ Key Features

- ✅ **Automatic NPV/IRR Calculation** - Newton-Raphson convergence method
- 📊 **Monte Carlo Simulation** - 1000 iterations for accurate risk analysis
- 🎯 **2-Way Sensitivity Analysis** - Revenue × WACC cross-analysis heatmap
- 📈 **Scenario Comparison** - Conservative/Base/Optimistic auto-calculation
- 🔧 **Beta Adjustment Calculator** - Hamada formula for Levered Beta
- 📥 **Excel Export** - FCF table + analysis summary
- 🎨 **Industry Presets** - IT/Manufacturing/Healthcare/Retail WACC templates
- 🌐 **100% Browser-Based** - No installation, local data storage

## 🚀 Quick Start

### Method 1: Use Online (Recommended)

_URL will be available after Vercel deployment_

Just click and start! No installation required.

### Method 2: Run Locally

```bash
# 1. Clone repository
git clone https://github.com/koing999/HUB.git

# 2. Navigate to folder
cd HUB

# 3. Open HTML file
open index.html  # Mac
start index.html # Windows
```

## 💼 Perfect For

| User | Use Case |
|------|----------|
| 🚀 **Startup Founders** | IR materials, fundraising simulation |
| 💼 **VC Analysts** | Deal flow screening, quick valuation |
| 🎓 **MBA Students** | Financial modeling practice, case studies |
| 📊 **Consultants** | Client report preparation |
| 🏢 **Corporate Strategy** | New business feasibility analysis |

## 🛠️ Tech Stack

- **Frontend**: Pure HTML5 / CSS3 / JavaScript (ES6+)
- **Charts**: Chart.js 3.9.1
- **Excel Export**: SheetJS (xlsx) 0.18.5
- **No Backend**: 100% client-side (local data storage)
- **No Dependencies**: No frameworks (pure vanilla JS)

**Why Pure JS?**
- ✅ Fast loading (zero framework overhead)
- ✅ Easy customization (all code in one file)
- ✅ No installation (just one HTML file)

## 🤝 Contributing

Contributions are always welcome! 🎉

1. Fork this repository
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**TL;DR:**
- ✅ Commercial use allowed
- ✅ Modification allowed
- ✅ Distribution allowed
- ⚠️ Attribution required (keep copyright)

## 📞 Contact

- 📧 Email: koing756@naver.com
- 💬 Issues: [GitHub Issues](https://github.com/koing999/HUB/issues)
- 🌐 GitHub: [HUB Repository](https://github.com/koing999/HUB)

**☕ Found this helpful?**  
[Buy me a coffee via KakaoPay](https://qr.kakaopay.com/Ej8t3tRhG) _(Optional)_

---

**Made with ❤️ by 조르딘 (JoREDIN)**

⭐ Star this repo if you find it helpful!
