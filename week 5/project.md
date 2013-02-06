#Week 5 Project

 In a HTML file create the JavaScript code that will create a 5 question math quiz using prompt boxes, keep it simple, I will have to be taking this for each of you, keep track of the number of answers the user gets correct and then use a case switch to put a text message in an Alert box reporting how well the user did. Please be kind in your text message.

```html
<!DOCTYPE html>
<html>
	<head>
		<script type="text/javascript">
			correct = 0;
			check = function(response) {
				response = eval(response);
				if (response < answer + 0.01 && response > answer - 0.01) {
					alert('correct! yay!');
					correct++;
				} else {
					alert("that's wrong!");
				}
			};

			answer = -5;
			check(prompt('What is the determinant of the matrix [[3,4],[2,1]]'));

			answer = -1/6;
			check(prompt('What is the limit of (sin(x) - x)/x^3 as x approaches 0'));

			answer = 9;
			check(prompt('What is the result of the Ackermann function with A(2,3)'));

			answer = 0.738643;
			check(prompt('What is the integration of sin(cos(x)) from x=0 to x=1'));

			answer = 8.763;
			check(prompt('What is the standard deviation of {25, 35, 10, 17, 29, 14, 21, 31}'));

			switch (correct) {
				case 5:
					alert('yay, 100%');
					break;
				case 4:
					alert('eh... ok 4/5');
					break;
				case 3:
					alert("i suppose you got the majority correct...");
					break;
				case 2:
					alert('that was just disappointing, only 2 correct');
					break;
				case 1:
					alert('only 1 correct!? were you even trying?');
					break;
				case 0:
					alert('you got nothing correct! zero. zip. nada. in short: you failed');
					break;
			}

		</script>
	</head>
</html>
```
