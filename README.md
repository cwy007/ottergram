# 《Web开发权威指南》

第一个demo

## npm install -g browser-sync

```bash
# 进到项目目录
browser-sync start --server --browser "Google Chrome" --files "stylesheets/*.css, *.hmtl"
```

## 声明新的字体类型

```css
/* 字体源文件放在 stylesheets/fonts/ 文件夹中 */
  font-family: 'lakeshore';
  src: url('fonts/LAKESHOR-webfont.eot');
  src: url('fonts/LAKESHOR-webfont.eot?#iefix') format('embedded-opentype'),
       url('fonts/LAKESHOR-webfont.woff') format('woff'),
       url('fonts/LAKESHOR-webfont.ttf') format('truetype'),
       url('fonts/LAKESHOR-webfont.svg#lakeshore') format('svg');
  font-weight: normal;
  font-style: normal;
}
```
