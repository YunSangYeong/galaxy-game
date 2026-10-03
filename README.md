# GALAXY 우주 슈팅 게임

브라우저에서 실행하는 고전 아케이드 스타일 우주 슈팅 게임입니다.

## 실행

`index.html`을 브라우저에서 열면 됩니다. 별도 설치나 빌드가 필요 없습니다.

- 방향키 또는 A/D: 이동
- Space: 발사
- Enter: 시작
- P: 일시정지 / 계속하기
- 모바일: 화면을 드래그해 이동하고 발사 버튼을 길게 누릅니다.

적 편대와 급강하 공격, 스테이지 진행, 목숨 3개, 효과음, 브라우저 최고 점수 저장을 지원합니다. 소리는 화면 상단에서 켤 수 있습니다.

## GitHub Pages와 블로그

저장소의 Settings → Pages에서 Deploy from a branch를 선택하고 main 브랜치의 /(root)를 지정합니다.
게시가 완료된 뒤 Pages 주소를 블로그에 링크하거나, HTML 삽입을 지원하는 블로그에서는 아래 코드를 사용할 수 있습니다.

```html
<iframe
  src="여기에-GitHub-Pages-게임-주소"
  title="GALAXY 우주 슈팅 게임"
  width="100%"
  height="1000"
  style="border:0;max-width:860px;display:block;margin:auto;"
  loading="lazy">
</iframe>
```

키보드 조작은 게임 화면을 한 번 클릭한 뒤 사용하세요. 블로그 플랫폼에 따라 iframe 삽입이 제한될 수 있습니다.

## 파일

- index.html: CSS와 JavaScript가 포함된 단일 실행 파일
- dist/: HTML, CSS, JavaScript를 나눈 원본

최고 점수는 브라우저에만 저장됩니다. 온라인 순위표는 제공하지 않습니다.
