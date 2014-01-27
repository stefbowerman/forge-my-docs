Forge My Docs
===========

Use my handwriting and pretend you're me

### Usage

Add the fonts to your project.

Add the following to your CSS
```css
@font-face{ 
	font-family: 'Stefan';
	src: url('<path to>/stefan.eot');
	src: url('<path to>/stefan.eot?#iefix') format('embedded-opentype'),
	     url('<path to>/stefan.woff') format('woff'),
	     url('<path to>/stefan.ttf') format('truetype'),
	     url('<path to>/stefan.svg#webfont') format('svg');
	font-weight: normal;
	font-style: normal;
}
```

Use it somewhere
```css
body { font-family: 'Stefan'; }
```
