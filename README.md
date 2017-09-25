ckLine.js
===========

Generates random svg Lines

![ckLine.gif](https://gifyu.com/images/ckLine.gif)

Currently, the plugin is only supported in Chrome it will be fixed in the next version

## Installation

Download package and include `jquery.ckLine.min.js` in your document after including jQuery.

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script src="/path/to/jquery.ckLine.min.js"></script>
```

## Usage

You need an empty SVG Element in your HTML
```html
<svg id="ckLine" xmlns="http://www.w3.org/2000/svg"></svg>
```

### Via JavaScript

To call the ckLine plugin, select your target element with jQuery and do the following:

```javascript
$('#ckLine').ckLine();
```

## Options

<table class="table table-bordered table-striped">
	<thead>
		<tr>
			<th style="width: 100px;">Name</th>
			<th style="width: 100px;">type</th>
			<th style="width: 50px;">default</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>svgId</td>
			<td>string</td>
			<td>null</td>
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
			<td>strokeColor</td>
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
		<tr>
			<td>leftRight</td>
			<td>boolean</td>
			<td>true</td>
		</tr>
		<tr>
		    <td>animationTimeRange</td>
		    <td>array</td>
		    <td>[&lt;number&gt;, &lt;number&gt;]</td>
		</tr>
	</tbody>
</table>

## Functions

To Destroy the plugin

```javascript
$('#ckLine').ckLine.destroy();
```
