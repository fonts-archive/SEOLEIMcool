# 시원한 설레임체

[배포처 바로가기](https://www.lottewellfood.com/prcenter/seoleim)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `SEOLEIM cool`입니다.

### HTML

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/fonts-archive/SEOLEIMcool/SEOLEIMcool.css"
  type="text/css"
/>
```

### CSS `@Import`

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/SEOLEIMcool/SEOLEIMcool.css");
```

### CSS `@font-face`

```css
@font-face {
  font-family: "SEOLEIM cool";
  font-weight: normal;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/fonts-archive/SEOLEIMcool/SEOLEIMcool.woff2")
      format("woff2"), url("https://cdn.jsdelivr.net/gh/fonts-archive/SEOLEIMcool/SEOLEIMcool.woff")
      format("woff"),
    url("https://cdn.jsdelivr.net/gh/fonts-archive/SEOLEIMcool/SEOLEIMcool.otf")
      format("opentype"), url("https://cdn.jsdelivr.net/gh/fonts-archive/SEOLEIMcool/SEOLEIMcool.ttf")
      format("truetype");
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/fonts-archive/SEOLEIMcool/subsets/SEOLEIMcool-dynamic-subset.css"
  type="text/css"
/>
```

### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/SEOLEIMcool/subsets/SEOLEIMcool-dynamic-subset.css");
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "SEOLEIM cool", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
  Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
가. 사용권
개인 및 기업 사용자를 포함한 모든 사용자에게 "설레임"체를 무료로 사용할 수 있는 권리를 드립니다. 이는 "설레임체의" 소유권에 대한 내용이 아니며, 사용권에 대한 내용입니다.

나. 저작권
설레임체의 지적재산권은 전적으로 롯데제과 주식회사("롯데제과")가 보유하고 있으며 사용자는 다양한 매체에 자유롭게 특별한 절차 없이 사용할 수 있습니다.
단 유료로 설레임체 자체를 양도하거나, 판매하는 등의 행위는 금지합니다.
또한 설레임 제품의 아이덴티티를 위해 패키지 제품에 "설레임체"를 사용하는 것은 제한하고 있습니다.
(패키지에 글씨 사용 x _ 상업용 및 온 오프라인 제품 패키지에 사용을 금합니다) *문의(고객지원센터: 080-024-6060)

다. 기능
롯데제과는 정상적인 사용환경에서 사용하는 통상적인 사용자들이 무리 없이 사용할 수 있도록 설레임체를 개발하고 테스트 하였습니다.
그러나 사용자 개개인의 특수한 사용환경, 현재 또는 미래의 모든 운영 체제 등에서 항상 완벽하게 동작 한다는 보증을 해드리지 못함을 양해해 주시기 바랍니다. 하지만 사용자가 사용상 문제점(버그)를 발견한 다음 롯데제과에 통보해 줄 경우, 문제 해결에 최선을 다해 사용자의 불편을 신속히 해결할 수 있도록 노력할 것을 약속합니다. *문의(고객지원센터: 080-024-6060)

라. 면책
설레임체는 저작권, 특허권, 상표권 및 기타 권리의 비침해성과 특정 목적에의 적합성을 포함한 명시적, 묵시적 보증 없이 "있는 그대로" 제공 됩니다. 어떠한 경우에도 롯데제과는 사용자의 "설레임체"의 사용 및 취급과 관련하여 일반적, 특수적, 간접적, 부차적 혹은 필연적 손해를 포함하는 소송, 손해, 혹은 기타 책임에 대한 의무를 가지지 않습니다.
```
