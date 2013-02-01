#Week 3 Project

Create an html file with the JavaScript code in it that:

1. Asks a user for a number to cube, returns that value cubed and displays the result in an alert box
2. Starts a start timer button and returns some text in a Alert box every four seconds until a stop timer button is clicked.

```html
<!DOCTYPE html>
<html lang="en">
	<body>
		<script type="text/javascript">
			alert(Math.pow(+prompt("what should I cube?"), 3));
			timer = undefined

			start = function() {
				timer = setInterval(function(){alert('blah!')}, 4000);
			}
			stop = function() {
				clearInterval(timer);
			}
		</script>
		<input type="button" value="Start" onClick="start()">
		<input type="button" value="Stop" onClick="stop()">
	</body>
</html>
```
