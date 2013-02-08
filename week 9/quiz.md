#Week 9 Quiz

In a html file create the JavaScript code that sets up a multidimensional Array that is two row and three columns populated by the text for different shapes. (circle, square, etc.)

```html
<!DOCTYPE html>
<html>
	<body>
		<style type="text/css">
			table, tr, td {
				border: 1px solid black;
			}
		</style>
		<script>
			tbl = [
				['Möbius strip', 'Torus', 'Riemann surface'],
				['Kähler manifold', 'Tesseract', 'Klein bottle'],
			]
			tbl_html = '<table>';
			e = 0
			while (e < tbl.length) {
				tbl_html += '<tr>';
				i = 0;
				while (i < tbl[e].length) {
					tbl_html += '<td>' + tbl[e][i] + '</td>';
					i++;
				}
				tbl_html += '</tr>';
				e++;
			}
			document.write(tbl_html + '</tr></table>');
		</script>
	</body>
</html>
```
