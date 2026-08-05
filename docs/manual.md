# JIWU Mission Network · 편한IT 웹사이트 제작 매뉴얼

이 문서는 JIWU Mission Network · 편한IT 웹사이트의 제작 및 유지보수를 위한 가이드입니다.

## 1. 프로젝트 개요
- **사이트명:** 박기현 | JIWU Mission Network · 편한IT
- **프레임워크:** Hugo (v0.164.0+extended)
- **테마/템플릿:** Hugo Blox (hugo-theme-academic-cv)
- **CSS 프레임워크:** Tailwind CSS

## 2. 개발 환경 설정
로컬 환경에서 사이트를 실행하고 수정하려면 다음 환경이 필요합니다.
- **필수 도구:** Node.js, npm, Hugo (extended 버전)
- **로컬 서버 실행 명령어:**
  ```bash
  npx hugo server -D
  ```

## 3. 주요 폴더 및 파일 구조
- `config/_default/`: 사이트 전반의 메타데이터 및 설정 파일 (예: `params.yaml`, `hugo.yaml`)
- `content/_index.md`: 홈페이지 메인 화면 레이아웃 및 각 섹션 콘텐츠 정의
- `content/authors/me/_index.md`: 대표 박기현 님의 프로필 정보, 메인 사진(`avatar.png`), 소셜 링크 등
- `content/blog/`: 블로그 및 칼럼 마크다운 게시글 모음
- `plan.md`: 기획 초안 및 요구사항 문서 (참고용)

## 4. 커스텀 가이드
### 4.1 첫 화면 문구 수정
메인 타이틀 문구는 `content/_index.md` 파일 내 `resume-biography-3` 블록의 `text` 필드에서 수정합니다.

### 4.2 프로필 사진 변경
`content/authors/me/` 폴더 내에 `avatar.png` 또는 `avatar.jpg` (정사각형 권장) 파일을 덮어씌웁니다.

### 4.3 블로그 글 작성
`content/blog/` 디렉터리에 새로운 마크다운 파일(예: `my-post.md`)을 생성하거나 폴더 구조를 만들어 작성합니다.

---
*참고: 본 매뉴얼은 AI 어시스턴트에 의해 작업이 진행될 때마다 지속적으로 업데이트됩니다.*
