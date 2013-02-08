#Week 8 Project

In a html file create the JavaScript code that will create an Array with 6 String items in it, different names, and then:

1. Create a button that will put the Array into a var and displays that var in an Alert box
2. Create a button that reverses the Array in to a new Array and then puts that into var and displays that var in an Alert box.
3. Create a button that sorts the original Array and displays the content of this new Array in an Alert box.

```html
<!DOCTYPE html>
<html>
	<body>
		<script>
			arr = ['Drove', 'to', 'Chicago', 'All', 'things', 'know'];
		</script>
		<input type="button" value="show origional arr" onClick="alert(arr);">
		<input type="button" value="reverse arr" onClick="alert(arr.reverse());">
		<input type="button" value="sort arr" onClick="alert(arr.sort());">
	</body>
</html>
```
