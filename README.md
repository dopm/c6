# c6
Simplify Column of Grid
-------

c6 is simple version of [grill](http://dopm.github.io/grill), six column variation more sensible 
for the needs of typography and certainly very compact and solid. c6 is also very responsive, 
profound and overly lovey-dovey on typography.


## Installation

Install with [component](http://component.github.io/) :

    $ component install dopm/c6

However, you can just grab the [css file](http://dopm.github.io/c6/c6.css) from GitHub. There is no dependency.

## How to bake
First, link to c6.css in your HTML document's head:

	<link rel="stylesheet" href="c6.css">

then, wrap the container with a `.g` class, :

```css
<div class="g">
	<div class="c c-3">

	</div>
	<div class="c c-3">

	</div>
	<div class="c c-6">

	</div>
</div>
```

### Namespace
Grid namespace `g` 
Columns namespace `c`

```css
<div class="g">
	<div class="c c-{X}">
	...
```

### Push and pull columns

```css
<div class="g">
	<div class="c c-{X} c-ph-1">
	...
```

`c-ph-{X}` to push and
`c-pl-{X}` to pull

### Centered

Centers the column in the grid and clears the row of all other columns

```css
<div class="g">
	<div class="c c-{X} c-center">
	...
```

option:
`c-center` to centerd.
`c-first` displays the column as the first in its row.
`c-last` displays the column as the last in its row.
`c-ab` align column to the bottom.
`c-am` align column to the middle.

### Removes gutters from the columns

```css
<div class="g g-no-gutter">
	<div class="c c-{X}-{X}">
	...
```

See also demo [removes gutters from the columns](http://dopm.github.io/c6/c6-no-gutter.html)

### Browser
The c6 can be used on IE7 and modern browsers

