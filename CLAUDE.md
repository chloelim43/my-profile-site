# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 언어 및 커뮤니케이션 규칙

### 기본 응답 언어
- **Claude의 응답**: 한국어로 작성
- **코드 주석 및 문서화**: 한국어로 작성
- **커밋 메시지**: 한국어로 작성
- **코드 내 변수명/함수명**: 영어 (코드 표준 준수)

### 예시
```javascript
// 함수명은 영어로 작성
function calculateTotal(items) {
  // 주석은 한국어로 작성
  // 모든 상품의 가격을 합산한다
  return items.reduce((sum, item) => sum + item.price, 0);
}
```

## 프로젝트 구조

현재 리포지토리는 초기화 상태입니다. 프로젝트 구조가 추가되면 이 섹션을 업데이트하세요.

## 개발 환경 설정

프로젝트 타입에 따라 다음을 추가하세요:

### Node.js / JavaScript 프로젝트
```bash
npm install          # 의존성 설치
npm run dev          # 개발 서버 실행
npm test             # 테스트 실행
npm run lint         # 린트 검사
npm run build        # 빌드
```

### Python 프로젝트
```bash
pip install -r requirements.txt  # 의존성 설치
python manage.py runserver       # 서버 실행
pytest                           # 테스트 실행
```

## 아키텍처 및 설계 원칙

프로젝트 구조가 확정되면 다음 항목들을 문서화하세요:

- **프로젝트 목적**: 이 프로젝트가 무엇을 하는지
- **기본 아키텍처**: 주요 구성 요소와 상호작용 방식
- **중요한 설계 결정**: 왜 특정 기술/패턴을 선택했는지
- **모듈/패키지 설명**: 각 주요 모듈의 책임과 관계

## 코딩 스타일 및 관례

프로젝트 타입에 따라 다음을 설정하세요:

- ESLint/Prettier (JavaScript)
- Black/Flake8 (Python)
- 기타 린터/포매터 설정

## 자주 사용되는 명령어

프로젝트 개발 시 자주 사용되는 명령어를 추가하세요:

```bash
# 예시 - 프로젝트에 맞게 수정하세요
npm run test -- --watch     # 감시 모드로 테스트 실행
npm run build -- --mode=dev # 개발 모드로 빌드
```

## 주의사항

- 이 파일은 Claude Code 인스턴스에 의해 읽혀지므로 프로젝트의 중요한 정보를 포함합니다.
- 프로젝트 구조와 워크플로우가 변경되면 이 파일을 업데이트하세요.
