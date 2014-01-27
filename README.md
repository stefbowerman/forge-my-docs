#Forge My Docs

Use my handwriting and pretend you're me

![alt tag](https://raw.github.com/stefbowerman/forgeMyDocs/master/ex.png)

###Usage
####For the web
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

####For Macs
Double click .otf/.tff file -> 'Install Font'

####Else
You're on your own
