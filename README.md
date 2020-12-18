# 开心宋体

A webfont repository for KaiXinSong, based on <https://github.com/VdustR/hanamin>.

- Original font: <http://www.guoxuedashi.com/zidian/bujian/KaiXinSong.php>

- As sourced from: <https://github.com/yuleshow/chinese-fonts>

- Split with [font-splitter](https://github.com/VdustR/font-splitter)

- Minify with [clean-css-cli](https://github.com/jakubpawlowicz/clean-css-cli)

  ```bash
  cleancss --source-map -o KaiXinSong.min.css KaiXinSong.css
  ```

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
