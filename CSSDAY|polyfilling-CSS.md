# Houdini & Polyfilling CSS

> Philip Walton

## Polyfilling CSS
```css
	/* random is fake */
	.progress-bar {
		width: calc(random() * 100%)
	}
```

> All polyfills do the same // rewrite to understandable code for a browser
> *browser throws away fake css…  Only lives in your files*
> We need a parser like postCSS to get the bits we want to change
> loop > replace > put in browser // *repeating styles for the win….*
> target individuals
> ends up in performance issues
> fix? // Houdini
