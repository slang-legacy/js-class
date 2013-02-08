#Week 8 Quiz

In a html file create the JavaScript code that will prompt a user to enter a series of text into an Array, like family members names, Greatest All Time QB's, Greatest Presidents, what ever you wish to ask for. Then ask the user to enter a number that will retrieve the String value from that Array that corresponds to that Array's key and displays that String in an Alert box.

```html
<!DOCTYPE html>
<html>
	<body>
		<script>
			arr = eval(prompt('enter your favorite FRC teams, identified by their ID\'s, in JSON.'));
			alert('the element @ that index is: ' + arr[prompt('pick a number in range(0, ' + (arr.length - 1) + ')')]);
		</script>
	</body>
</html>
```
