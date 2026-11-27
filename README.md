# 장윤우 포트폴리오 - GitHub Pages

이 폴더만으로 동작하는 정적 포트폴리오입니다. Python, npm, 원본 노트북, 외부 이미지 폴더가 필요하지 않습니다.

## 파일 구성

```text
index.html             페이지 내용
assets/css/style.css   디자인과 반응형·인쇄 스타일
assets/images/         프로필과 프로젝트 이미지 11개
.nojekyll              Jekyll 처리 없이 정적 파일 제공
```

## GitHub Pages에 올리기

1. GitHub에서 사용할 저장소를 만들거나 선택합니다.
2. **이 폴더 안의 파일과 assets 폴더를 저장소 최상위에** 업로드하고 커밋합니다. 발표용 폴더 자체를 한 단계 아래에 넣지 않습니다.
3. 저장소의 **Settings → Pages → Build and deployment**로 이동합니다.
4. **Source: Deploy from a branch**, **Branch: main**, **Folder: / (root)**를 선택하고 Save를 누릅니다. 기본 브랜치가 main이 아니라면 실제 브랜치를 선택합니다.
5. 배포가 끝나면 Pages에 표시되는 주소를 엽니다.

일반 저장소는 `https://사용자명.github.io/저장소명/` 형태로 열립니다.
모든 이미지와 CSS가 상대경로이므로 저장소 이름을 바꿔도 경로를 수정할 필요가 없습니다.

GitHub 공식 가이드: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## 로컬에서 확인하거나 수정하기

- `index.html`을 브라우저로 열면 됩니다.
- 문구는 `index.html`, 디자인은 `assets/css/style.css`에서 수정합니다.
- 이미지를 교체할 때는 `assets/images`의 파일과 `index.html`의 `src` 경로를 함께 확인합니다.
- 원본 portfolio 폴더와 연결되어 있지 않으므로 여기서 수정한 내용이 원본에 반영되지는 않습니다.
- JavaScript, 접기/펼치기, 애니메이션은 사용하지 않습니다.
