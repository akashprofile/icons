# Icons For Personal Use
---
## Font Awesome
Font Awesome has 5 fonts. Four fonts for each icon in four styles and fifth font for brand logos.

|Font Name|Class Name|
|---------|:--------:|
|Font Awesome Light| fal|
|Font Awesome Regular|far|
|Font Awesome Solid|fas|
|Font Awesome Duotone|fad|
|Font Awesome Brands|fab|

__URL - Direct Link__
```url
https://akashprofile.github.io/icons/fontawesome.css
```

__Syntax__
```html
<i class="class_name fa-icon_name"></i>
```
Each icon is an inline-block level element.

---
## Material Icons

```url
https://akashprofile.github.io/icons/material-icons.css
```

It has five fonts for five styles of every icon.

|Font Name|Class Name|
|---|-----|
|Material Icons Outlined|mi-outlined|
|Material Icons Rounded|mi-rounded|
|Material Icons Filled|mi-filled|
|Material Icons Sharp|mi-sharp|
|Material Icons Two Tone|mi-two-tone|

__Syntax__
```html
<i class="class_name">ligature_name</i>
```
Each icon is an inline-block level element.

---

## Material Symbols

```url
https://akashprofile.github.io/icons/material-symbols.css
```

It has three fonts for three styles.

|Font Name|Class Name|
|---|-----|
|Material Symbols Outlined|ms-outlined|
|Material Symbols Rounded|ms-rounded|
|Material Symbols Filled|ms-filled|

__Syntax__
```html
<i class="class_name">ligature_name</i>
```
Each icon is an inline-block level element. Every icon supports four variations
|Variable Axis|Description|
|:---:|-----|
|wght|Modifies thickness of stroke|
|opsz|Modifies optical size of icon|
|FILL|It transits from unfilled to filled state by taking values from 0 to 1|
|GRAD|It modifies the emphasis of icon with respect to background|

```css
/* 'wght' Both will produce same result */
font-variation-settings: 'wght' 24px;
font-weight: 24px;

/* 'opsz' Both will produce same result */
font-variation-settings: 'opsz' 24px;
font-optical-sizing: 24px;

/* FILL */
font-variation-settings: 'FILL' 0.5;

/* GRAD */
font-variation-settings: 'GRAD' 200;
```
