#Week 3 Quiz

In a web page create the code that makes a function that puts your age and name into a div tag using the innerHTML and display this in a table arrangement.

```html
<!DOCTYPE html>
<html lang="en">
	<body>
		<script type="text/javascript">
			meaningless_wrapper_function = function() {
				document.getElementById("age").innerHTML = prompt("what's yo age?");
				document.getElementById("name").innerHTML = prompt("what's yo name?");
			}.call()
		</script>
		<table>
			<tr>
				<td><div id="age"></div></td>
				<td><div id="name"></div></td>
			</tr>
		</table>
	</body>
</html>
```
