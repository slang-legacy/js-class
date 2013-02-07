#Week 7 Quiz

In a html file write the code that will create a create a string that is exactly 22 characters long and show that it is that long in an Alert box. (remember spaces count).

```html
<!DOCTYPE html>
<html>
	<body>
		<script>
			alert((str = Math.pow(Math.random(), 3)).toString(36).substring(2, 24)) + ' is ' + str.length + ' long')
		</script>
	</body>
</html>
```
