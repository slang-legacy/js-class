#Week 15 Project

In a html file create the JavaScript code that will:

1. Ask a user for a radius of a circle and report back in an Alert box its area and circumference.
2. Ask a user for the two sides of a rectangle and report back in an Alert box its area and perimeter.
3. Ask a user for the height of a rectangle and report back in an Alert box its area.

```html
<!DOCTYPE html>
<html>
	<body>
		<script type="text/javascript">
			alert('circumference = ' + prompt('radius of a circle?') * 2 * Math.PI);
			alert('perimeter = ' + ((h = +prompt('height of rectangle?'))*2 + (w = +prompt('width too?')))*2 + ' area = ' + h*w);
			alert('area = ' + Math.pow(prompt('height of square?'),2));
		</script>
	</body>
</html>
```
