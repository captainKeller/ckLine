JnLine.js
===========

Generate random svg Lines

## Installation

Download package or install with Bower and include `jnLine.min.js` in your document after including jQuery.

```bash
$ bower i --save jnLine.js
```

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script src="/path/to/jquery.jnLine.min.js"></script>
```

## Usage

You need a SVG Element in your HTML
```html
<svg id="jnLine" xmlns="http://www.w3.org/2000/svg"></svg>
```

### Via JavaScript

To call the jnLine plugin manually, simply select your target element with jQuery and do the following:

```javascript
$('#jnLine').jnLine();
```

## Options

<table class="table table-bordered table-striped">
	<thead>
		<tr>
			<th style="width: 100px;">Name</th>
			<th style="width: 100px;">type</th>
			<th style="width: 50px;">default</th>
			<th>description</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>scgId</td>
			<td>string</td>
			<td>jnLine</td>
		</tr>
		<tr>
			<td>width</td>
			<td>number</td>
			<td>SvgWidth</td>
		</tr>
		<tr>
			<td>height</td>
			<td>number</td>
			<td>SvgHeight</td>
		</tr>
		<tr>
			<td>strokeColo</td>
			<td>string</td>
			<td>#000</td>
		</tr>
		<tr>
			<td>strokeWidth</td>
			<td>number</td>
			<td>2</td>
		</tr>
		<tr>
			<td>animateTime</td>
			<td>number</td>
			<td>1000</td>
		</tr>
		<tr>
			<td>interval</td>
			<td>number</td>
			<td>600</td>
		</tr>
		<tr>
			<td>fadeOut</td>
			<td>number</td>
			<td>800</td>
		</tr>
		<tr>
			<td>lifeTime</td>
			<td>number</td>
			<td>2000</td>
		</tr>
		<tr>
			<td>easing</td>
			<td>string</td>
			<td>swing</td>
		</tr>
	</tbody>
</table>
