# Chloe Lim - 포트폴리오 웹사이트

개인 포트폴리오를 소개하는 모던하고 반응형 웹사이트입니다.

## ✨ 주요 기능

- 🎨 **Tailwind CSS CDN** - 간편한 스타일링
- 🌓 **다크모드** - localStorage를 활용한 모드 저장
- 📱 **반응형 디자인** - 모든 기기에서 최적화
- ⚡ **부드러운 애니메이션** - 스크롤 효과와 호버 상호작용
- 🔗 **스무스 스크롤** - 네비게이션 링크로 부드러운 이동

## 📋 페이지 섹션

1. **Hero** - 대표 소개 및 CTA 버튼
2. **About** - 개발자 소개 및 특징 3가지
3. **Skills** - 기술 스택 카드 (HTML5, CSS3, JavaScript, React, Node.js, Git, MongoDB, Tailwind)
4. **Projects** - 3개의 포트폴리오 프로젝트
5. **Contact** - 이메일, GitHub, LinkedIn, Twitter 연락처
6. **Footer** - 저작권 정보

## 🛠️ 기술 스택

- HTML5
- Tailwind CSS (CDN)
- Vanilla JavaScript
- Font Awesome (아이콘)

## 📖 설정값

### 기본 정보
- **이름**: Chloe Lim
- **직업**: 풀스택 웹 개발자
- **이메일**: tngud43@gmail.com

### 기술 스택
- Frontend: HTML5, CSS3, JavaScript, React, Tailwind
- Backend: Node.js
- Database: MongoDB
- Tools: Git

### 프로젝트
1. E-commerce 플랫폼 (React, Node.js, MongoDB)
2. Task 관리 앱 (React, JavaScript)
3. 날씨 앱 (React, API)

## 🚀 사용 방법

### 로컬 서버 실행

**Python 3 사용:**
```bash
python -m http.server 8000
# http://localhost:8000 에서 접속
```

**Node.js http-server:**
```bash
npx http-server
```

**VS Code Live Server:**
- VS Code의 Live Server 확장 프로그램 설치 후 사용

## 🎨 커스터마이징

### 색상 변경
`index.html`의 Tailwind 색상 클래스를 수정하여 색상 변경 가능:
- `from-blue-400` → 다른 색상으로 변경
- `text-blue-600` → 다른 색상으로 변경

### 정보 수정
- 이름, 직업, 소개 텍스트 수정
- 프로젝트 정보 및 링크 변경
- 연락처 링크 업데이트

### GitHub 링크 연결
연락처 섹션의 GitHub 링크를 실제 프로필 URL로 변경:
```html
<a href="https://github.com/your-username">
```

## 📱 반응형 브레이크포인트

- **모바일**: 기본 (< 768px)
- **태블릿**: `md:` (768px +)
- **데스크톱**: `lg:` (1024px +)

## 🌙 다크모드

- 달 아이콘 버튼으로 다크모드 토글
- 선택한 모드는 localStorage에 저장되어 자동 로드

## 📂 파일 구조

```
my-profile-site/
├── index.html        # 메인 페이지 (HTML + CSS + JS)
├── README.md         # 프로젝트 설명 (이 파일)
└── .gitignore        # Git 무시 파일
```

## 🔧 추가 커스터마이징 아이디어

- 각 프로젝트 카드의 GitHub 링크 업데이트
- 연락처 섹션의 소셜 링크 추가
- 자신의 정보에 맞게 About 섹션 수정
- 더 많은 프로젝트 추가
- 이력서/CV 다운로드 링크 추가

## 📄 라이선스

개인 프로젝트로 자유롭게 사용하시길 바랍니다.

---

**제작**: Chloe Lim | **마지막 업데이트**: 2024
