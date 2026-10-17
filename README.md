# Astral Guardian Skill Site

별수호자(Astral Guardian) 스킬 설정 및 편집 사이트입니다.

## GitHub Pages 배포 방법

1. GitHub에서 새 저장소(repository)를 만듭니다.
2. `index.html` 파일을 저장소 최상위(root)에 업로드합니다.
3. 저장소의 **Settings → Pages**로 이동합니다.
4. **Build and deployment**에서 `Deploy from a branch`를 선택합니다.
5. Branch를 `main`, 폴더를 `/(root)`로 지정하고 저장합니다.
6. 배포가 완료되면 Pages에 표시된 URL로 사이트를 열 수 있습니다.

## 데이터 저장 안내

- 스킬 편집 내용은 현재 브라우저의 `localStorage`에 저장됩니다.
- 브라우저/기기 간 자동 동기화는 지원하지 않습니다.
- 다른 기기로 설정을 옮길 때는 사이트의 AI 프롬프트 탭에서 JSON을 내보내고, 다른 기기에서 불러오세요.
- 공개 저장소에 올리는 경우 `index.html`과 설정 내용이 공개됩니다. 민감한 정보는 넣지 마세요.

## 파일

- `index.html`: 사이트 본체
