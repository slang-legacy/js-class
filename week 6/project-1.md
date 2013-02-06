#Week 6 Project 1

In a html file write the JavaScript code that uses a for loop to write "How many times do I love thee" in a div 5 times with a number and a Times at the end. For example the first line should say. How many times do I love thee? 1 Time. Make the for loop write that 5 times on 5 different lines. How many times do I love thee? 1 Time  How many times do I love thee? 2 Time and so on.

```html
<!DOCTYPE html>
<html>
	<body>
		<script type="text/javascript">
			plural = ''
			for (i = 1; i < 6; i++) {
				document.getElementById('write').innerHTML += 'Home many times do I love thee? ' + i + ' time' + plural + '<br/>';
				plural = 's'
			}
		</script>
		<p id="write"></p>
	</body>
</html>
```
