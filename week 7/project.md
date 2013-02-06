#Week 7 Project

In a html file write the JavaScript code that will analyze the following sentence in these 4 ways:

`Do you hear the people sing, singing the song of angry men.`

In the html code write this sentence so it is visible before you start using your JavaScript code.Using 4 different buttons:

1. Display the sentence in all upper case.
2. Display the sentence in all lower case.
3. Find the position where the char f first appears
4. Find the total length of the sentence.

```html
<!DOCTYPE html>
<html>
	<body>
		<script>
			ptag = document.getElementById('str')
			ucase = function(){ptag.innerHTML = ptag.innerHTML.toUpperCase()};
			lcase = function(){ptag.innerHTML = ptag.innerHTML.toLowerCase()};
			where = function(){alert(ptag.innerHTML.indexOf('f'))};
			mylen = function(){alert(ptag.innerHTML.length)};
		</script>
		<p id="str">Do you hear the people sing, singing the song of angry men.</p>
		<input type="button" value="CAP DAT STR!" onClick="ucase();">
		<input type="button" value="get low..." onClick="lcase();">
		<input type="button" value="Where the f is..." onClick="where();">
		<input type="button" value="length" onClick="mylen();">
	</body>
</html>
```