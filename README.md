# 핫딜모아 v4 — GitHub 전용

GitHub Pages는 상업적 거래 중심 사이트에 제한이 있습니다. https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits 를 확인하고 허용되는 용도로만 공개하세요. 제휴 서비스 가입 자격도 확인하세요.

## 설치
1. GitHub에서 공개 저장소를 만들고 ZIP을 풀어 index.html, admin.html, deals.json, .nojekyll 파일을 저장소 루트에 업로드합니다.
2. Settings → Pages → Deploy from a branch → main / (root) → Save.
3. GitHub Settings → Developer settings → Personal access tokens → Fine-grained tokens에서 해당 저장소만 선택하고 Contents: Read and write 권한을 설정합니다. 토큰은 비밀번호처럼 보관하고 공유하지 마세요.
4. 공개 사이트 주소 뒤에 /admin.html을 붙여 접속하고 GitHub 인증 버튼을 누른 후 사용자명/저장소명, main, 토큰을 입력합니다. 토큰은 페이지 메모리에만 유지되며 새로고침하면 다시 입력해야 합니다.
5. 상품을 등록하면 deals.json에 커밋됩니다. 공개 페이지 반영은 GitHub Pages 배포 이후 이루어집니다.

## 참고
- 공개 저장소의 상품 데이터와 변경 이력은 누구나 볼 수 있습니다. 개인정보나 비밀키를 등록하지 마세요.
- 관리자 권한은 GitHub 저장소 쓰기 권한으로 제한됩니다. 다른 사람에게 쓰기 권한을 부여하지 마세요.
- 이미지 URL은 직접 입력합니다. 파일 업로드와 자동 수집은 지원하지 않습니다.
- 토큰 만료 및 GitHub API 호출 한도가 있습니다. AI 토큰은 사용하지 않습니다.
- 동시 수정 충돌 시 다시 시도하세요.
- 실제 GitHub 계정 연결 및 배포 테스트는 수행하지 않았습니다.

## v3 업데이트
상단 통합 제휴 안내, 텍스트형 목록, 개당 가격 자동 계산, 평소 가격 자유 입력, 코멘트, 방문자 복사 버튼을 추가했습니다. 기존 저장소를 업데이트할 때는 index.html과 admin.html만 교체 또는 추가하세요. deals.json을 덮어쓰면 기존 상품이 삭제됩니다. 제휴사별 고지 규정과 가입 자격을 확인하세요. GitHub Pages의 상업적 이용 제한도 확인해야 합니다.

## v4 관리자 분리
공개 index.html에는 관리자 메뉴 및 GitHub 쓰기 코드가 없습니다. admin.html 주소 자체는 공개되며 GitHub 쓰기 권한으로 변경을 보호합니다. 토큰은 페이지 메모리에만 보관합니다. 기존 저장소 업데이트 시 deals.json을 덮어쓰지 마세요.


## v5 디자인 업데이트
기존 저장소의 index.html 및 admin.html만 교체하세요. 기존 deals.json은 유지하세요. GitHub 인증과 저장 방식은 v4와 동일합니다.
