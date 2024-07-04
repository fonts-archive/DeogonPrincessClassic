# 덕온공주옛체

[배포처 바로가기](https://hanfont.hangeul.go.kr/relaxfont/font/deokon.do)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Deogon Princess Classic`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/DeogonPrincessClassic/DeogonPrincessClassic.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/DeogonPrincessClassic/DeogonPrincessClassic.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Deogon Princess Classic';
    font-weight: normal;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/DeogonPrincessClassic/DeogonPrincessClassic.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/DeogonPrincessClassic/DeogonPrincessClassic.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/DeogonPrincessClassic/DeogonPrincessClassic.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/DeogonPrincessClassic/DeogonPrincessClassic.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/DeogonPrincessClassic/subsets/DeogonPrincessClassic-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/DeogonPrincessClassic/subsets/DeogonPrincessClassic-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.



```css
font-family: "Deogon Princess Classic", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
별도의 승인 없이 인쇄, 출발, 영상, 웹 모바일 등 다양한 매체에서 상업적 목적으로도 자유롭게 사용이 가능합니다. 단, 해당 글꼴을 변형할 수 없으며 글꼴 자체를 유료로 판매나 대여할 수 없고 유해매체에서의 사용은 금지합니다. 저작권은 문화체육관광부 국립한글박물관과 (주)윤디자인그룹에 있습니다.
```
