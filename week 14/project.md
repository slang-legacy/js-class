#Week 14 Project

In a html file create the JavaScript code that will display the Day & Date in an Alert box in the following format:

`Today is Friday Feb 12th, 2013`

```html
<!DOCTYPE html>
<html>
	<body>
		<script type="text/javascript">
			dayOfWeek = ['Sunday', 'Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday'];
			monthOfYear = ['Jan', 'Feb', 'Mar', 'Apr', 'May', 'June', 'July', 'Aug', 'Sept', 'Nov', 'Dec']
			dt = new Date();

			alert('Today is ' + dayOfWeek[dt.getDay()] + ' ' + monthOfYear[dt.getMonth()] + ' ' + dt.getDate() + 'th, ' + dt.getFullYear());
		</script>
	</body>
</html>
```
