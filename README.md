# 과제 체크 · 학생 실습 예제

[실제 GitHub Pages 앱](https://sky6174.github.io/assignment-check-demo/) · [단계별 실습·프롬프트·강사 설명](https://vibe-coding-course-three.vercel.app/assignment-lab.html)

무료 AI 도구로 만든 단일 HTML 앱을 GitHub Pages에 배포하는 수업의 강사 기준 코드입니다. 특정 무료 서비스에서 이 코드를 생성했다는 실행 기록을 뜻하지 않습니다. 수강생은 Gemini 기본 또는 ChatGPT Free 등 접근 가능한 도구 한 개에 교재의 요청을 입력하고 결과를 비교합니다.

## 기능

과제명·과목·마감일 입력, 완료 체크, 전체/미완료/완료 보기, 마감일순 정렬, 오늘/기한 지남 집계, 삭제와 되돌리기, 가상 예제 3개를 제공합니다. 데이터는 현재 origin과 브라우저의 localStorage에 저장됩니다. 다른 사람·기기와 공유되지 않으며 로컬 파일과 Pages의 저장 영역도 다릅니다. 서버·외부 API·설치·빌드가 필요 없습니다.

## 배포

1. `index.html`을 브라우저에서 열고 입력·완료·새로고침을 확인합니다. 파일 환경의 저장이 제한되면 공개 Pages 또는 로컬 HTTP로 확인합니다.
2. 학생 자신의 GitHub 계정에 `assignment-check` 공개 저장소를 만듭니다.
3. `Add file → Upload files`로 `index.html`을 저장소 최상위에 올리고 commit합니다.
4. `Settings → Pages → Deploy from a branch → main → /(root) → Save`로 설정합니다.
5. 배포 완료 URL을 열고 휴대폰에서 핵심 기능을 확인합니다. 페이지 파일명을 `Index.html`로 바꾸거나 한 단계 아래 폴더에 넣지 않습니다.
6. 수정한 파일을 다시 commit하고 새 배포 완료 후 확인합니다.

공개할 소스에는 가상 예제만 넣습니다. 실제 과제 입력은 브라우저 내부에 보관됩니다. 브라우저의 사이트 데이터 삭제·시크릿 세션 종료·저장 제한에서는 보존되지 않을 수 있습니다. 읽기/쓰기 실패 시 앱이 임시 모드를 표시합니다.
