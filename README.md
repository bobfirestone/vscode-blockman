<p><strong>Donation</strong> is really appreciated. This VSCode extension is a work of many months. My name is Levan Katsadze (ლევან კაცაძე), 1995-03-03, I'm a student in Tbilisi, Georgia (country). I learn Frontend development (JavaScript, TypeScript, React).</p>

**PayPal**: https://paypal.me/leodevbro

**Buy Me A Coffee**: https://www.buymeacoffee.com/leodevbro

**Bank account (USD)**: GE08TB7774936615100013 (TBCBGE22)

**Bank account (GEL/Lari)**: GE18TB7774936515100011 (TBCBGE22)

<br />
<br />

<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/vscode-blockman/main/demo-media/still-image/icon-prod/blockman-icon-128---png.png"
  alt="VSCode Blockman Icon"
  width="128px"
/></p>
<h3 align="center" style="color: red;">Blockman</h3>
<h6 align="center">(VSCode Extension For Nested Block Highlighting)<h6/>

Repository: https://github.com/leodevbro/vscode-blockman
  
<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/vscode-blockman/main/demo-media/still-image/infograph/intro-before-after---png.png"
  alt="alt text testing"
/></p>
  
`Animated PNG:`
<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/vscode-blockman/main/demo-media/animated-png-aka-apng/main-demo---c2-apng.png"
  alt="alt text testing"
/></p>
  
Supported programming langauges:<br />
Non-indentation based languages: JavaScript, JSX, TypeScript, TSX, C, C#, C++, Java, HTML, XML, CSS, LESS, SCSS, JSON, JSONC and more...<br />
Indentation based language(s): currently Python only.<br />

<br />
<br />

<h1 align="center">!!! IMPORTANT !!!</h1>

<p align="center">First, adjust line height and character frame width manually</p>
<p align="center">(Because currently VSCode API <a href="https://github.com/microsoft/vscode/issues/118994">does not provide</a> them)</p>

<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/vscode-blockman/main/demo-media/animated-png-aka-apng/height-width---c2-apng.png"
  alt="alt text testing"
/></p>
Each line of code must have less than 500 characters, otherwise blocks will not be rendered in entire file.

<br />
<br />
  
<h1 align="center">More Demonstrations</h1>
  
<p align="center">Python code:</p>

<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/vscode-blockman/main/demo-media/animated-png-aka-apng/python-demo---c2-apng.png"
  alt="alt text testing"
/></p>

<h3 align="center">Blockman settings</h3>
  
<p align="center">You can change nesting depth</p>
<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/vscode-blockman/main/demo-media/animated-png-aka-apng/settings/depth---c2-apng.png"
  alt="alt text testing"
/></p>
  
<br />
  
<p align="center">You can choose color combos</p>
<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/vscode-blockman/main/demo-media/animated-png-aka-apng/settings/color-combos---c2-apng.png"
  alt="alt text testing"
/></p>
<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/vscode-blockman/main/demo-media/still-image/infograph/color-combos---png.png"
  alt="alt text testing"
/></p>
  
<br />
  
<p align="center">You can change color of each depth</p>
<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/vscode-blockman/main/demo-media/animated-png-aka-apng/settings/custom-depth-colors---c2-apng.png"
  alt="alt text testing"
/></p>
  
<br />
  
<p align="center">You can change focused block colors and general border color</p>
<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/vscode-blockman/main/demo-media/animated-png-aka-apng/settings/focus-colors-and-general-border-color---c2-apng.png"
  alt="alt text testing"
/></p>

<br />
  
<p align="center">You can change basis of block analysis</p>
<p align="center">(Curly brackets, square brackets, round brackets, tags, indentaion)</p>
<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/vscode-blockman/main/demo-media/animated-png-aka-apng/settings/based-on-bracket-types---c2-apng.png"
  alt="alt text testing"
/></p>
  
<br />
  
<p align="center">Currently only Python is supported from indentation based languages</p>
<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/vscode-blockman/main/demo-media/animated-png-aka-apng/settings/indent-tokens---c2-apng.png"
  alt="alt text testing"
/></p>
  
<br />
  
<p align="center">You can disable rendering single line blocks</p>
<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/vscode-blockman/main/demo-media/animated-png-aka-apng/settings/single-line-block---c2-apng.png"
  alt="alt text testing"
/></p>

<br />

<h1 align="center">Things to consider</h1>
  
1) Each line of code must have less than 500 characters, otherwise blocks will not be rendered in entire file.<br />

2) Please don't use non-monospace font. Use only monospace font like 'Oxygen Mono', '<a href="https://bpgfonts.wordpress.com/2017/12/21/bpg-2017-dejavu-sansmono/">BPG 2017 DejaVu Sans Mono</a>' or other. Block-rendering is based on equal character-frame-widths, because pixel locations of characters <a href="https://github.com/microsoft/vscode/issues/118994">is not accessible</a> through VSCode API.
<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/vscode-blockman/main/demo-media/still-image/infograph/monospace-font---png.png"
  alt="alt text testing"
/></p>

```
Just for the information, the letter "ლ" is Georgian alphabet character,
like: ა, ბ, გ, დ, ე, ვ, ზ, თ, ი, კ, ლ, მ, ნ, ო, პ, ჟ, რ, ს, ტ, უ, ფ, ქ, ღ, ყ, შ, ჩ, ც, ძ, წ, ჭ, ხ, ჯ, ჰ.
```

3) If you want to use mix of multiple fonts (like in the image above), Please don't use any non-monospace font. Use monospace fonts which have at least almost same width of character. For example: 'Oxygen Mono' and '<a href="https://bpgfonts.wordpress.com/2017/12/21/bpg-2017-dejavu-sansmono/">BPG 2017 DejaVu Sans Mono</a>' have not only equal char frame width by themselves alone, but also almost equal char frame width to each other.<br />
  
**For Geogian (ქართული) language oriented developers:** without multiple font mixing, just <a href="https://bpgfonts.wordpress.com/2017/12/21/bpg-2017-dejavu-sansmono/">BPG 2017 DejaVu Sans Mono</a> as a single font seems fine for me, and maybe you can use it too. I think it is the one and only monospace font which has English and Georgian lowercase letters, as well as <a href="https://www.unicode.org/charts/script/chart_Georgian.html">Georgian CAPITAL (uppercase) letters</a>.

**For English language oriented developers:** the same statement above goes here.

<br />

4) If you want to use ligatured monospace font like "Fira Code" (Typographic ligatures are when multiple characters appear to combine into a single character), please make sure that the font maintains the text width on every line with ligatures like there were no ligatures. "Fira Code" seems fine, and maybe most of ligatured monospace fonts are fine.<br />

<br />
  
5) Recommended to turn off word wrap. Blocks will not render properly if there is any word wrapping.
<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/vscode-blockman/main/demo-media/animated-png-aka-apng/word-wrap---c2-apng.png"
  alt="alt text testing"
/></p>
  
<br />

6) Recommended to turn off "Editor: Highlight Active Indent Guide" and "Editor: Render Indent Guides".
<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/vscode-blockman/main/demo-media/animated-png-aka-apng/indent-guide---c2-apng.png"
  alt="alt text testing"
/></p>
  
<br />

6) Recommended to set pale color (e.g. pale blue) to lineHighlightBorder and lineHighlightBackground like this:
<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/vscode-blockman/main/demo-media/animated-png-aka-apng/line-hl---c2-apng.png"
  alt="alt text testing"
/></p>
<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/vscode-blockman/main/demo-media/still-image/infograph/line-hl---png.png"
  alt="alt text testing"
/></p>
  

First, press **F1**

then, type **>settings json**

then, open and edit **settings.json** file:
```jsonc
{
    // ...
    "workbench.colorCustomizations": {
        // ...
        "editor.lineHighlightBorder": "#9fced11f",
        "editor.lineHighlightBackground": "#1073cf2d",

        // Or for specific vscode themes:
        "[Default Dark+]": {
            // "editor.lineHighlightBorder": "#9fced11f"
            // "editor.lineHighlightBackground": "#1073cf2d",
        },
        "[Abyss]": {
            "editor.lineHighlightBorder": "#9fced11f",
            "editor.lineHighlightBackground": "#1073cf2d"
        }
        // ...
    },
    // ...
}
```
  
<br />

7) Inline decorators such as VSCode Color Decorators of styles causes wider text line, some situations are handled, some situations are not handled yet, for example when linear-gradient has three or more colors.
<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/vscode-blockman/main/demo-media/animated-png-aka-apng/color-decorators---c2-apng.png"
  alt="alt text testing"
/></p>

<br />

<h1>Optimization Notes</h1>
Optimization is taken very seriously, half of the work is dedicated just for the optimization. The source code is full of logic which prevents many unnecessary block re-renderings.

<br />
<br />
  
File analisis needs super short time, so it's not a big problem. The main problem is that the vscode block rendering functions (`vscode.window.createTextEditorDecorationType` and `setDecorations`) are very slow, and I cannot touch its internal code, because it's just an API of VSCode. So, almost all optimization algorithms are trying to prevent as many unnececary block renderings as possible. For example, when scrolling, blocks are rendered into only newlly visible code, and the blocks which are already visible, stay there and does not rerender.
