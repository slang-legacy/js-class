#Week 2 Project 

In an HTML page create JavaScript code that:

1. Creates  an Alert Box with a greeting
2. Secondly Creates a Confirm box asking if the users is ready and willing to learn about JavaScript
3. Finally Creates a Prompt box that multiples two numbers that the user inputs and display that answer in that prompt

```html
<!DOCTYPE html>
<html>
	<body>
		<script type="text/javascript">
			alert('HAI!!!');
			if(!confirm('you ready and willing to learn JS?!?')) alert('I don\'t care!')
			alert('the product is: ' + (prompt('enter number 1') * prompt('enter number 2')));
		</script>
	</body>
</html>
```