#Week 5 Quiz

In a HTML file write the JavaScript code that will ask a user to enter a number between 1 and 5 and then using if, else if, and else conditionals, report back to the users using an Alert box which number was entered.

```html
<!DOCTYPE html>
<html>
	<head>
		<script>
			num = prompt('Enter an int between 1-5 (inclusive)');
			if (num == 5) {
				alert(5);
			} else if(num == 4) {
				alert(4);
			} else if(num == 3) {
				alert(3);
			} else if(num == 2) {
				alert(2);
			} else if(num == 2) {
				alert(1);
			} else {
				alert('you didn\'t enter a number in range(1,5)')
			}

			// note - this could be rewritten without conditionals as:
			// alert(prompt('Enter a number 1 - 5'));
		</script>
	</head>
</html>
```
