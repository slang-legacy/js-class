#Week 4 Project

In a html file create JavaScript code that uses buttons to control the text you have put into a div container using the innerHTML  which:

1. Changes the Font Color to 4 different colors plus the original
2. Changes the Font Size to 4 different sizes plus the original
3. Changes the Font Family to 4 different font types plus the original
4. Changes the Font Alignment to Left, Center or Right

```html
<!DOCTYPE html>
<html>
	<body>
		<script>
			change = function(attr, opts){
				value = prompt('what should the ' + attr + ' be set to?\n(' + opts + ')');
				document.getElementById('changeMe').style[attr] = value;
			};
		</script>
		<input type="button" value="change color" onClick="change('color', 'red, blue, green, purple')">
		<input type="button" value="change fontSize" onClick="change('fontSize', '12px, 14px, 16px, 400px')">
		<input type="button" value="change font!" onClick="change('fontFamily', 'verdana, geneva, arial, helvetica, sans-serif')">
		<input type="button" value="change alignment!" onClick="change('textAlign', 'left, right, center')">
		<div id="changeMe">
<p>Yeah, I like animals better than people sometimes... Especially dogs. Dogs are the best. Every time you come home, they act like they haven't seen you in a year. And the good thing about dogs... is they got different dogs for different people. Like pit bulls. The dog of dogs. Pit bull can be the right man's best friend... or the wrong man's worst enemy. You going to give me a dog for a pet, give me a pit bull. Give me... Raoul. Right, Omar? Give me Raoul.</p>
<p>The lysine contingency - it's intended to prevent the spread of the animals is case they ever got off the island. Dr. Wu inserted a gene that makes a single faulty enzyme in protein metabolism. The animals can't manufacture the amino acid lysine. Unless they're continually supplied with lysine by us, they'll slip into a coma and die.</p>
<p>Like you, I used to think the world was this great place where everybody lived by the same standards I did, then some kid with a nail showed me I was living in his world, a world where chaos rules not order, a world where righteousness is not rewarded. That's Cesar's world, and if you're not willing to play by his rules, then you're gonna have to pay the price.</p>
		</div>
	</body>
</html>
```
