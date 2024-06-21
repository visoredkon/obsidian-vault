### `@import` rule

`color.css`
```css
:root {
	--main-color: #f9e2af;
	--main-background-color: #1e1e2e;
	--secondary-background-color: #313244;
	--main-text-color: #cdd6f4;
	--secondary-text-color: #11111b;
}
```

`style.css`
```css
body {
    font-size: 17px;
    font-family: "Open Sans";
    background: var(--main-background-color);
}
```