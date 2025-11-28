# 한국 커뮤니티 공유 가이드

## 🇰🇷 한국 커뮤니티 포스팅 자료

---

## 1️⃣ GeekNews 포스팅

### 제목
```
[오픈소스] 스타트업 IR용 투자분석 대시보드 만들어봤습니다
```

### 본문
```markdown
안녕하세요!

스타트업 IR 준비하면서 매번 엑셀로 NPV/IRR 계산하는 게 너무 불편해서,
웹 기반 대시보드를 만들어봤습니다.

## 🎯 주요 기능

• **NPV/IRR 자동 계산** (Newton-Raphson 수렴 방식)
• **몬테카를로 시뮬레이션** (1000회 반복)
• **2-Way 민감도 분석** (매출 × WACC 히트맵)
• **시나리오 비교** (보수적/기본/낙관적)
• **Beta 조정 계산기** (Hamada 공식)
• **엑셀 다운로드** (FCF 테이블 + 요약)

## ✨ 특징

- 설치 필요 없음 (브라우저에서 바로 실행)
- 100% 무료
- MIT License 오픈소스
- 데이터 로컬 저장 (서버 전송 없음)

## 🔧 기술 스택

- Pure HTML/CSS/JavaScript (프레임워크 없음)
- Chart.js (차트)
- SheetJS (엑셀 다운로드)

순수 바닐라 JS로 만든 이유:
- 빠른 로딩 (프레임워크 오버헤드 제로)
- 쉬운 커스터마이징 (코드 한 파일)
- 설치 불필요

## 🎯 이런 분들께 유용합니다

- IR 준비하는 스타트업 대표님
- 투자심사 하시는 VC 심사역님
- 재무분석 배우는 MBA 학생
- 프로젝트 타당성 분석하는 기획자님

## 🔗 링크

- 데모: https://investment-dashboard.vercel.app
- GitHub: https://github.com/yourusername/investment-dashboard

기능 제안이나 버그 리포트는 GitHub Issue로 남겨주시면 감사하겠습니다!

피드백 환영합니다 🙏
```

---

## 2️⃣ 디스콰이엇 포스팅

### 제목
```
💎 투자분석 대시보드 오픈소스로 공개합니다
```

### 본문
```markdown
안녕하세요, 메이커님들!

스타트업 IR 준비할 때 쓰려고 만든 투자분석 툴을 오픈소스로 공개합니다.

## 무엇을 만들었나요?

웹 기반 투자분석 대시보드입니다.
NPV, IRR, 몬테카를로 시뮬레이션을 30초 만에 계산해줍니다.

## 왜 만들었나요?

기존 방식의 문제점:
❌ 엑셀 수작업: 공식 복잡 + IRR 수렴 안 됨
❌ 유료 SaaS: 월 $99 이상 + 기능 제한
❌ 시간 소모: 한 번 분석에 3시간+

그래서 만들었습니다:
✅ 브라우저에서 바로 실행
✅ 30초 만에 완성
✅ 100% 무료

## 주요 기능

1. **NPV/IRR 자동 계산**
   - Newton-Raphson 방식 (정확도 0.0001%)
   
2. **몬테카를로 시뮬레이션**
   - 1000회 반복으로 리스크 분석
   
3. **민감도 분석**
   - 1-Way: 단일 변수 영향
   - 2-Way: 매출 × WACC 히트맵
   
4. **시나리오 비교**
   - 보수적/기본/낙관적 자동 계산
   
5. **엑셀 다운로드**
   - FCF 테이블 + 분석 요약
   - IR 자료로 바로 사용

## 기술적 특징

- Pure Vanilla JS (React/Vue 없음)
- 한 파일에 모든 코드 (62KB)
- 프레임워크 오버헤드 제로
- 오프라인 동작 가능

## 누가 쓰면 좋을까요?

🚀 IR 준비 중인 창업자
💼 투자심사 하는 VC/PE
🎓 재무분석 배우는 학생
📊 타당성 분석하는 기획자

## 링크

🌐 데모: https://investment-dashboard.vercel.app
💻 GitHub: https://github.com/yourusername/investment-dashboard
📖 가이드: [README.md]

## 다음 계획

현재 기능 안정화 후:
- 클라우드 저장 (선택적 로그인)
- 팀 협업 기능
- 모바일 앱

피드백과 기여 환영합니다!

---

Made with ❤️ for Startup Community
MIT License
```

---

## 3️⃣ LinkedIn 포스팅

### 본문 (한글)
```
💎 투자분석 대시보드를 오픈소스로 공개합니다

스타트업 IR 준비하면서 느낀 불편함을 해결하기 위해 만든 툴입니다.

📊 무엇을 하나요?
- NPV/IRR 자동 계산 (30초 완성)
- 몬테카를로 시뮬레이션 (1000회)
- 2-Way 민감도 분석
- 시나리오 비교
- 엑셀 다운로드

✨ 왜 좋은가요?
- 100% 무료
- 설치 불필요 (브라우저 실행)
- 오픈소스 (MIT License)
- 데이터 로컬 저장 (보안)

🎯 누구에게 유용한가요?
- 스타트업 대표 (IR 준비)
- VC 심사역 (Deal flow 스크리닝)
- MBA 학생 (재무분석 실습)
- 기업 기획팀 (타당성 분석)

🔗 지금 바로 사용해보세요
Demo: https://investment-dashboard.vercel.app
GitHub: https://github.com/yourusername/investment-dashboard

피드백과 별(⭐) 부탁드립니다!

#스타트업 #투자 #재무분석 #오픈소스 #IR #VC
```

### 본문 (영문)
```
💎 I built an open-source Investment Dashboard

As a startup founder, I was frustrated with spending 3+ hours on Excel for every investment analysis. So I built a tool to solve my own problem.

📊 What it does:
- Automatic NPV/IRR calculation (30 seconds)
- Monte Carlo simulation (1000 iterations)
- 2-Way sensitivity analysis
- Scenario comparison
- Excel export

✨ Why it's great:
- 100% Free
- No installation (runs in browser)
- Open-source (MIT License)
- Privacy-first (local data storage)

🎯 Perfect for:
- Startup founders (IR prep)
- VC analysts (Deal screening)
- MBA students (Financial modeling)
- Corporate strategy teams

🔗 Try it now
Demo: https://investment-dashboard.vercel.app
GitHub: https://github.com/yourusername/investment-dashboard

Feedback and stars (⭐) appreciated!

#Startup #Investment #Finance #OpenSource #IR #VC
```

---

## 4️⃣ Reddit 포스팅

### r/startups
```markdown
Title: [Tool] Built a free investment analysis dashboard for IR prep

Body:
Hey r/startups,

I built a free tool for calculating NPV/IRR when preparing IR materials. Thought it might be useful for other founders too.

**What it does:**
- Calculates NPV, IRR, payback period, break-even
- Runs 1000-iteration Monte Carlo simulation
- 2-Way sensitivity analysis (Revenue × WACC)
- Exports to Excel for investor decks

**Why I built it:**
I was tired of:
- Spending 3+ hours in Excel for each analysis
- IRR formulas that don't converge
- Paying $99/month for SaaS tools I use once a month

**Tech:**
Pure HTML/CSS/JavaScript - no frameworks, no backend, no account needed. Just open and use.

**Try it:**
Demo: https://investment-dashboard.vercel.app
GitHub: https://github.com/yourusername/investment-dashboard

It's MIT licensed so feel free to fork/customize. Feedback welcome!
```

### r/entrepreneur
```markdown
Title: Made a free tool for quick investment analysis - thought you might find it useful

Body:
If you're evaluating investment opportunities or preparing for investor meetings, this might save you some time.

**Investment Dashboard** - calculates NPV, IRR, and risk analysis in 30 seconds.

Features:
- Automatic financial calculations
- Monte Carlo risk simulation
- Scenario comparison (pessimistic/base/optimistic)
- Excel export

It's 100% free, open-source, and runs in your browser (no signup).

Link: https://investment-dashboard.vercel.app

Would love to hear your feedback if you try it!
```

---

## 5️⃣ 스타트업 얼라이언스

### 제목
```
[무료 툴] IR 준비용 투자분석 대시보드 공유합니다
```

### 본문
```
안녕하세요, 얼라이언서님들!

IR 준비하실 때 쓰시라고 만든 투자분석 툴 공유드립니다.

## 어떤 툴인가요?

NPV, IRR, 몬테카를로 시뮬레이션을 자동으로 계산해주는 웹 대시보드입니다.
엑셀 3시간 작업을 30초로 단축시켜줍니다.

## 주요 기능

1. NPV/IRR 자동 계산
2. 1000회 몬테카를로 시뮬레이션
3. 민감도 분석 (1-Way, 2-Way)
4. 시나리오 비교 (보수적/기본/낙관적)
5. 엑셀 다운로드 (IR 자료용)

## 왜 만들었나요?

시드 투자 준비하면서:
- 엑셀 IRR 공식이 자꾸 #NUM! 에러
- 민감도 분석 테이블 만드는 데만 1시간
- 투자자마다 다른 시나리오 요청받음

→ 그래서 자동화 툴을 만들었습니다.

## 특징

- 100% 무료
- 설치 불필요
- 데이터 보안 (로컬 저장)
- 오픈소스 (MIT License)

## 링크

데모: https://investment-dashboard.vercel.app
GitHub: https://github.com/yourusername/investment-dashboard

IR 준비하시는 분들께 도움이 되었으면 좋겠습니다!
피드백 환영합니다 🙏
```

---

## 📅 공유 타임라인

### Day 1: 메인 커뮤니티
- [ ] GeekNews (오전 10시)
- [ ] 디스콰이엇 (오전 11시)
- [ ] 스타트업 얼라이언스 (오후 2시)

### Day 2: 글로벌 커뮤니티
- [ ] Product Hunt (PT 00:01 = 한국 오후 5시)
- [ ] r/startups (오전 10시)
- [ ] r/entrepreneur (오전 11시)

### Day 3: 소셜 미디어
- [ ] LinkedIn (오전 9시)
- [ ] Twitter (오전 9시)
- [ ] Facebook 그룹들 (오전 10시~)

### Day 4-7: 추가 채널
- [ ] 요즘IT 기고
- [ ] 패캠 블로그 투고
- [ ] 인프런 커뮤니티
- [ ] 개발자 커뮤니티들

---

## 💡 공유 팁

### 해야 할 것
✅ 진솔한 스토리텔링 ("내가 불편해서 만들었어요")
✅ 구체적인 문제 제시
✅ 실제 사용 사례 공유
✅ 피드백 요청
✅ 겸손한 태도

### 하지 말아야 할 것
❌ 과장 ("세계 최고", "혁명적")
❌ 상업적 홍보 느낌
❌ 비교 폄하 ("XX보다 100배 좋음")
❌ 연속 도배
❌ 댓글 무시

---

## 📊 성공 지표

### Week 1 목표
- GeekNews 조회수: 1,000+
- 디스콰이엇 좋아요: 50+
- GitHub Stars: 100+
- 실사용자: 200+

### Month 1 목표
- 총 방문자: 5,000+
- GitHub Stars: 500+
- 포크: 20+
- 기여자: 3+

---

**화이팅! 🚀**
