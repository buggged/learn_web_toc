# CSS Table of Content

### 1. What is CSS & why it is needed?

### 2. CSS syntax

```
	property: value;
```

### 3. CSS selector

```
	element/tag selector
	class selector
	id selector
```

### 4. How to add CSS to HTML

```
	inline css
	css in head tag
	css in separate file
```

### 5. CSS Priority order

```
	normal tag vs relational tag
	inline css priority
	important priority
```

### 6. Colors

```
	color: red;               << changes text color to red
	background-color: red;    << changes background color to red
```

```
Color values:

red, white, black   << with name

#fff, #000          << in hex form

rgba(0,0,0,0.5)     << red (0-255), green (0-255), blue (0-255) with opacity(0-1)

hsla(120, 10%, 10%, 0.5) << hue[0-360], saturation(50%), lightness/lux(50%), alpha/opacity[0-1]
```

### 7. Background

```
    background-color
    background-image
    background-repeat
    background-attachment
    background-position
	background-size
    background (shorthand property)
```

### 8. Box-Modal

`The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content`

```
	Border
	Margin
	Padding
	Content
```

### 9. Using Browser Inspector

```
	for chrome
	for firefox
```

### 9. outline

` Outline differs from borders! Unlike border, the outline is drawn outside the element's border, and may overlap other content. Also, the outline is NOT a part of the element's dimensions; the element's total width and height is not affected by the width of the outline.`

```
    outline-style
    outline-color
    outline-width
    outline-offset
    outline
```

### 10. Height/Width

```
	width
	max-width
	min-width
	height
	max-height
	min-height
```

### 11. Fonts

```
	font-family
	font-size
	font-weight
	font-style
```

### 12. Text

```
	text-align
	text-decoration
	text-transform
	letter-spacing
	line-height
```

### 13. Display

`Overriding the default inline/block element display property value`

```
	block
	inline
	inline-block
```

### 14. Measurement Unit

```
	px   << absolute value not related to anything
	%    << relative to parent size
	em   << relative to font size of element)
	rem  << relative to font size of root element)
	vh   << relative to screen viewable height 0-100
	vw   << relative to screen viewable width 0-100
```

### 15. Transforms

`transform: value;`

```
	skew
	translate
	rotate
	scale
```

### 16. Position

```
	relative
	absolute
	fixed
	sticky
```

### 17. Flexbox

```
---- Written on parent element ----
	display: flex;
	justify-content
	align-items

---- Written on child element ----
	justify-self
	align-self
	flex
```

### 18. Advanced Selectors

```
	combined selector (>, +, ~)
	pseudo selector (:hover, :focus, :first-child, :nth-child)
```

### 19. CSS Grid

```
	display: grid;
	grid-template-column
	grid-template-area
```

### 20. Responsiveness & media query

```
	@media
```

### 21. Animations & keyframes

```
	animation
	@keyframes
```
