**Cascading Style Sheets** (**CSS**) is a [stylesheet](https://developer.mozilla.org/en-US/docs/Web/API/StyleSheet) language used to describe the presentation of a document written in [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) or [XML](https://developer.mozilla.org/en-US/docs/Web/XML/XML_introduction) (including XML dialects such as [SVG](https://developer.mozilla.org/en-US/docs/Web/SVG), [MathML](https://developer.mozilla.org/en-US/docs/Web/MathML) or [XHTML](https://developer.mozilla.org/en-US/docs/Glossary/XHTML)). CSS describes how elements should be rendered on screen, on paper, in speech, or on other media.

**Anatomi CSS:**
```css
selector {
	property: value;
}
```

### Penempatan CSS
**Embed:**
```html
<!DOCTYPE html>
<html lang="en">
	<head>
		<style>
			<!-- CSS goes here -->
		</style>
	</head>
</html>
```

**Inline:**
```html
<!DOCTYPE html>
<html lang="en">
	<body>
		<div style:"CSS goes here"></div>
	</body>
</html>
```

**External:**
```html
<!DOCTYPE html>
<html lang="en">
	<head>
		<link rel="stylesheet" href="CSS path goes here" />
	</head>
</html>
```

Referensi:
1. [WPU: CSS Dasar](https://www.youtube.com/watch?v=CleFk3BZB3g&list=PLFIM0718LjIUBrbm6Gdh6k7ZUvPIAZm7p&pp=iAQB)