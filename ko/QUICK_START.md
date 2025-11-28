# 🚀 5분 만에 GitHub & Vercel 배포하기

> 코딩 몰라도 OK! 클릭만 하면 됩니다.

---

## ✅ 준비물

1. **GitHub 계정** (없으면 [여기서 가입](https://github.com/signup) - 1분)
2. **Vercel 계정** (GitHub로 로그인하면 자동 생성)
3. **이 폴더의 파일들** (전부 업로드할 거예요)

---

## 📦 Step 1: GitHub 저장소 만들기 (2분)

### 1-1. GitHub 로그인
```
https://github.com
```
→ 우측 상단 "Sign in" 클릭

### 1-2. 새 저장소 생성
1. 우측 상단 `+` 버튼 클릭
2. `New repository` 클릭
3. 정보 입력:
   - **Repository name**: `investment-dashboard`
   - **Description**: `Free investment analysis dashboard`
   - **Public** 선택 (중요!)
   - **Add a README file** 체크 해제
   - **Add .gitignore** 선택 안 함
   - **Choose a license** → MIT License 선택
4. `Create repository` 클릭

### 1-3. 파일 업로드
1. 생성된 저장소 페이지에서
2. `uploading an existing file` 클릭
3. 이 폴더의 **모든 파일** 드래그 앤 드롭
   - index.html
   - landing.html
   - README.md
   - LICENSE
   - USAGE_GUIDE.md
   - PRODUCT_HUNT.md
   - KOREAN_COMMUNITY.md
4. 하단 "Commit changes" 클릭

✅ **완료!** 이제 코드가 GitHub에 올라갔습니다!

---

## 🌐 Step 2: Vercel 배포하기 (3분)

### 2-1. Vercel 접속
```
https://vercel.com
```

### 2-2. GitHub로 로그인
1. `Sign Up` 클릭
2. `Continue with GitHub` 클릭
3. GitHub 계정 인증 (Authorize 클릭)

### 2-3. 프로젝트 Import
1. 대시보드에서 `Add New...` 클릭
2. `Project` 선택
3. `Import Git Repository` 클릭
4. `investment-dashboard` 저장소 찾기
5. `Import` 클릭

### 2-4. 배포 설정
1. **Project Name**: 그대로 두거나 원하는 이름
2. **Framework Preset**: `Other` (그대로 두기)
3. **Root Directory**: `./` (그대로)
4. **Build Command**: 비워두기 (변경 없음)
5. **Output Directory**: 비워두기 (변경 없음)

→ `Deploy` 클릭!

### 2-5. 배포 완료 대기
- 30초~1분 소요
- "Congratulations!" 화면 나오면 성공!

✅ **완료!** 이제 세계 어디서나 접속 가능한 URL이 생겼습니다!

---

## 🎉 Step 3: 링크 확인하기

### 3-1. Vercel 대시보드에서
```
https://your-project-name.vercel.app
```
→ 이 주소가 당신의 대시보드 URL입니다!

### 3-2. 테스트
1. 링크 클릭
2. landing.html이 보이면 성공!
3. "무료로 시작하기" 버튼 클릭
4. 대시보드 작동 확인

---

## 🔧 Step 4: README 수정하기 (선택)

### 4-1. GitHub에서 README 수정
1. GitHub 저장소 페이지로 이동
2. `README.md` 파일 클릭
3. 연필 아이콘 (Edit) 클릭
4. 다음 항목 수정:
   ```
   [Your Name] → 본인 이름
   your@email.com → 본인 이메일
   yourusername → GitHub 사용자명
   https://toss.me/yourid → 토스 후원 링크 (선택)
   ```
5. `Commit changes` 클릭

✅ **완료!** 이제 완전히 본인의 프로젝트입니다!

---

## 📱 Step 5: 세상에 알리기 (선택)

### 5-1. Product Hunt 런칭
- `PRODUCT_HUNT.md` 파일 참고
- 글 복사해서 Product Hunt에 등록

### 5-2. 한국 커뮤니티 공유
- `KOREAN_COMMUNITY.md` 파일 참고
- GeekNews, 디스콰이엇 등에 공유

### 5-3. SNS 공유
- LinkedIn, Twitter 포스팅
- "제가 만든 오픈소스 프로젝트" 소개

---

## 🎯 최종 체크리스트

배포 완료했다면 다음을 확인하세요:

- [ ] GitHub 저장소 Public으로 설정됨
- [ ] Vercel URL로 접속 가능
- [ ] landing.html 정상 작동
- [ ] index.html (대시보드) 정상 작동
- [ ] README.md에 본인 정보 업데이트
- [ ] LICENSE 파일 존재 확인

모두 체크되었다면 🎉 **성공!**

---

## ❓ 자주 묻는 질문

### Q: 배포 비용이 드나요?
A: 아니요! GitHub과 Vercel 모두 무료입니다. (월 방문자 10만명까지 무료)

### Q: 도메인을 바꾸고 싶어요
A: Vercel 대시보드 → Settings → Domains에서 변경 가능

### Q: 코드를 수정하면 자동으로 반영되나요?
A: 네! GitHub에 파일 업로드하면 Vercel이 자동으로 재배포합니다.

### Q: 삭제하고 싶어요
A: GitHub 저장소 Settings → 맨 아래 "Delete this repository" 클릭

---

## 🆘 도움이 필요하면?

### GitHub Issues
```
https://github.com/yourusername/investment-dashboard/issues
```

### 이메일
```
your@email.com
```

---

## 🎊 축하합니다!

당신은 이제 **오픈소스 메이커**입니다! 🚀

다음 단계:
1. ⭐ GitHub Star 모으기 (친구들에게 공유)
2. 📣 커뮤니티 공유하기
3. 🔧 기능 개선하기
4. 💰 수익화 고민하기 (Pro 버전)

**화이팅!** 💪
