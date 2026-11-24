# 평온재 브랜드 사이트

GitHub Pages로 바로 공개할 수 있는 정적 사이트입니다.

## 파일 구성

```
index.html      메인 페이지 (확정 3차안)
about.html      서브 1 · 평온재 이야기
images/         사이트에 쓰인 이미지 17개
.nojekyll       GitHub Pages가 파일을 그대로 쓰도록 하는 빈 파일
README.md       이 안내 파일
```

## 업로드 방법

1. 저장소의 **맨 위(루트)** 에 `index.html`, `about.html`, `images` 폴더, `.nojekyll`을 그대로 올립니다.
   `images` 폴더 안의 파일 이름과 위치를 바꾸지 마세요. 페이지가 `images/파일명` 경로로 이미지를 불러옵니다.
2. 저장소 **Settings → Pages** 에서 Source를 `Deploy from a branch`, Branch를 `main` / `/(root)` 로 선택하고 저장합니다.
3. 1~2분 뒤 `https://<계정이름>.github.io/<저장소이름>/` 으로 접속합니다.

## 참고

- 글꼴은 Google Fonts의 Noto Sans KR을 불러옵니다. 실제 운영 시 Pretendard로 바꾸려면 두 HTML 파일의 `<head>` 글꼴 링크를 교체하세요.
- 연락처, 사업자 정보, 가격의 `[ ]` 표시, 온라인 추모관 운영 기간 `[N]년`은 임의값입니다. 공개 전에 실제 정보로 바꿔야 합니다.
- 메인의 '가족평장묘', '온라인 추모관', '시공 사례' 등 아직 만들지 않은 서브페이지 메뉴는 메인 페이지의 해당 섹션으로 이동합니다.
