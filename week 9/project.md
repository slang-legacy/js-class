#Week 9 Project

In a html file create the JavaScript code that will, using four buttons, take an Array of sting items and:

1. delete the last item from the Array and show the contents of the new Array in an Alert box
2. add an item to the end of the Array and show the contents of the new Array in an Alert box
3. delete the first item from the Array and show the contents of the new Array in an Alert box
4. add an item to the beginning of the Array and show the contents of the new Array in an Alert box

```html
<!DOCTYPE html>
<html>
	<body>
		<script>
			arr = [
				'Torus',
				'Riemann surface',
				'Kähler manifold',
				'Tesseract',
			];
			del_last = function() {
				arr.pop();
				alert(arr);
			};
			append = function() {
				arr.push('Klein bottle');
				alert(arr);
			};
			del_first = function() {
				arr.shift();
				alert(arr);
			};
			prepend = function() {
				arr.unshift('Möbius strip');
				alert(arr);
			};
		</script>
		<input type="button" value="del_last" onClick="del_last();">
		<input type="button" value="append" onClick="append();">
		<input type="button" value="del_first" onClick="del_first();">
		<input type="button" value="prepend" onClick="prepend();">
	</body>
</html>
```

