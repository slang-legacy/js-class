#Week 13 Quiz

In an html file create a simple Forms section of your choosing, a simple quiz. Make one field Name. Create an alert that asks the user if they are ready to start the quiz? Then upon the OK of the Alert are you ready to start the quiz, set the focus to the first field which is the users name.

```html
<!DOCTYPE html>
<html>
	<body>
		<script type="text/javascript">
			alert('you ready, bro?');
			document.quiz.name.focus();
		</script>
		<form name="quiz">
			<input id="name" value="">
		</form>
	</body>
</html>
```
