# 开心宋体

A webfont repository for KaiXinSong, based on <https://github.com/VdustR/hanamin>. Supports CJK Extensions A through I.

- Original font: <http://www.guoxuedashi.com/zidian/bujian/KaiXinSong.php> (version 4.1)

- Split with [font-splitter](https://github.com/VdustR/font-splitter)

- Minify with [clean-css-cli](https://github.com/jakubpawlowicz/clean-css-cli)

  ```bash
  cleancss --source-map -o KaiXinSong.min.css KaiXinSong.css
  ```

## Online Demo

<https://codesandbox.io/embed/kaixinsong-webfont-demo-2uit3>

## Usage

```css
body {
  font-family: KaiXinSong;
}
```

### With Pre-processor

Install `kaixinsong`:

```sh
npm i kaixinsong
# or install it with yarn
yarn add kaixinsong
```

And import it in js:

```js
import "kaixinsong";
```

or in css:

```css
@import "~kaixinsong";
```


### With CDN

jsDelivr npm:

```html
<link
  rel="stylesheet"
  type="text/css"
  href="https://cdn.jsdelivr.net/npm/kaixinsong/KaiXinSong.min.css"
/>
```

jsDelivr GitHub:

```html
<link
  rel="stylesheet"
  type="text/css"
  href="https://cdn.jsdelivr.net/gh/transfusion/kaixinsong-webfont/KaiXinSong.min.css"
/>
```

UNPKG:

```html
<link rel="stylesheet" type="text/css" href="https://unpkg.com/kaixinsong" />
```
