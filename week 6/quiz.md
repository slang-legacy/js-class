#Week 6 Quiz

In a html file create the JavaScript code that will create a table that has 3 rows and 6 columns and will put in Cell 1 - Cell 18 in the 18 cells. To be clear, the first cell has Cell 1 in it (notice the space between the letters and the number, the second cell  across will have Cell 2 in it until the final cell in the lower right will have Cell 18 in it. The first cell in row 2 will have Cell 7 in it.

```html
<!DOCTYPE html>
<html>
	<body>
		<style>
			table td {
				border: 1px solid black
			}
		</style>
		<script type="text/javascript">
			num = 1;
			row = 3;
			html = '';
			while (row-- >= 1) {
				html += '<tr>';
				col = 6;
				while (col-- >= 1) {
					html += '<td>Cell ' + num++ + '</td>';
				}
				html += '</tr>';
			}
			document.getElementById('table').innerHTML = html;
		</script>
		<table id="table"></table>
	</body>
</html>
```
