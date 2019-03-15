### 💅 Theme

<img src="./theme_screenshot.png" width="450px">

#### Prerequisites
- [FiraFlott](https://github.com/kosimst/FiraFlott/blob/master/TTF/FiraFlott%20FiraCode%20(Medium).ttf) font
- [Script12 BT](https://www.wfonts.com/font/script12-bt) font

#### Setup
- Install and activate [Oceanic Next Italic](https://marketplace.visualstudio.com/items?itemName=SintrumIT.theme-oceanic-next-italic) theme
- Add the following properties into your `settings.json` file
```json
{
  "editor.fontFamily": "FiraFlott",
  "editor.fontSize": 16,
  "editor.fontLigatures": true
}
```
- Open `/Applications/Visual\ Studio\ Code.app/Contents/Resources/app/out/vs/workbench/workbench.main.css`
- Prepend CSS bellow right after the comment

```css
.mtki,.mtk13{font-family:'Fira Code iScript';font-style:italic;font-size:1.17em;font-stretch:ultra-condensed;}
```

- Restart VSCode dismissing the warning about broken setup
