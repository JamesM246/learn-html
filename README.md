# learn-html
A trivial hello world website with basic web HTML/CSS/JavaScript

# HTML

## Semantic elements

Semantic elements are HTML 'div' elements which have a name related to the function.

Examples

	nav
	section
	aside
	header
	footer

# Markdown Syntax

# Main Header
## Sub Header
### Sub-Sub Header

*italics*
**bold**
***bold italic***

This is a `highlight` for individual words / blocks of text

> This can be used to quote a whole paragraph (`blockquote`)

We can use regular html for images

<img src="https://www.c-ville.com/wp-content/uploads/2019/09/Cats-660x335.jpg" width="350"/>

We can also 
<span style="text-decoration:underline">underline</span> text

### Code highlighting
```
int x = 1;
```
	this is tabbed in once
	It can also be used for code

```java
int x = 1;
```

```html
<html>
<head>
	<!--head is meta data-->
	<title>My Page</title>
	<style>
		/*CSS goes here*/
	</style>
</head>
<body>
	<h1>Hello World Web Page</h1>
	<p>Sample web page</p>
	<script>
		alert("alert alert alert");
		function runThisSometimes(){
			alert("run this sometimes");
		}
	</script>
	<button onclick="runThisSometimes()">Run This Sometimes</button>
</body>
</html>
```