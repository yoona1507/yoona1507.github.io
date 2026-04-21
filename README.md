# My Study Hub 📚

공부 앱 3개를 한 번에 웹에 올려서 핸드폰·PC 어디서든 쓰는 프로젝트.

- 🇯🇵 **JLPT 일본어** (N5~N3, 1459 단어) → `/jlpt/`
- 🇨🇳 **HSK 중국어** → `/hsk/`
- 🩺 **FM 가정의학과 퀴즈** → `/fm/`

---

## 🚀 GitHub Pages 업로드 가이드 (핸드폰 / PC 공용)

### 1단계. GitHub 가입
1. https://github.com 접속 → **Sign up**
2. 이메일 / 비밀번호 / 유저네임 입력 (유저네임은 URL에 쓰이니 깔끔하게!)
3. 이메일 인증 완료

### 2단계. 저장소(Repository) 만들기
1. 로그인 후 오른쪽 위 `+` → **New repository**
2. **Repository name**: `study-apps` (또는 `<유저네임>.github.io` 를 쓰면 URL이 더 짧아짐)
3. **Public** 선택 (Pages는 무료 플랜에서 Public만 가능)
4. **Add a README file** 체크 안 해도 됨 (이미 있음)
5. **Create repository** 클릭

### 3단계. 파일 업로드
1. 만들어진 저장소 페이지에서 **Add file → Upload files** 클릭
2. `Desktop/study-apps` 폴더 안의 내용물을 **전부 드래그**
   - `index.html`
   - `README.md`
   - `jlpt/` 폴더 (index.html + data.js)
   - `hsk/` 폴더 (index.html + data.js)
   - `fm/` 폴더 (index.html)
3. 아래쪽 **Commit changes** 클릭

> 📱 핸드폰에서 하면 폴더 업로드가 안 될 수 있어요. PC/노트북에서 하는 게 제일 쉽습니다.

### 4단계. Pages 켜기
1. 저장소 상단 메뉴에서 **Settings** 클릭
2. 왼쪽 메뉴에서 **Pages** 클릭
3. **Source**: `Deploy from a branch`
4. **Branch**: `main` / `/ (root)` 선택 후 **Save**
5. 1~2분 기다리면 페이지 상단에 초록색으로 URL이 떠요:
   ```
   https://<유저네임>.github.io/study-apps/
   ```

### 5단계. 핸드폰에서 열기
- 위 URL을 핸드폰 브라우저로 접속
- **크롬/사파리 메뉴 → 홈 화면에 추가** 하면 앱처럼 아이콘이 생김 🎉

---

## 📝 업데이트하는 법
- GitHub 저장소에서 해당 파일 클릭 → 연필 아이콘(Edit) → 수정 → Commit
- 또는 새 파일을 다시 업로드(같은 이름이면 덮어쓰기)
- 1~2분 후 자동으로 사이트에 반영됨

## 🔧 폴더 구조
```
study-apps/
├── index.html        ← 허브 랜딩 페이지 (메인)
├── README.md
├── jlpt/
│   ├── index.html
│   └── data.js
├── hsk/
│   ├── index.html
│   └── data.js
└── fm/
    └── index.html
```

## ⚠️ 주의
- FM 폴더의 큰 PDF·Word 파일은 일부러 포함 안 했어요 (GitHub 100MB 제한 + 검색엔진 노출 문제).
  → 그런 건 Google Drive 같은 곳에 따로 올리고 링크로 연결하는 걸 추천합니다.
