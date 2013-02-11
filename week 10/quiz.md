#Week 10 Quiz

In a html file create the JavaScript code that will allow the user to see an image, mouse over to change the image and mouse out to restore the original image. Both images need to be the same size.

```html
<!DOCTYPE html>
<html>
	<body>
		<style>
			img {
				width: 100%;
			}
		</style>
		<script type="text/javascript">
			img = document.getElementById('img');
			img.onmouseover = function(){
				this.setAttribute("src", 'http://www.google.com/about/datacenters/gallery/images/_3000/CBF_008.jpg');
			};
			img.onmouseout = function(){
				this.setAttribute("src", 'http://www.google.com/about/datacenters/gallery/images/_3000/IDI_012.jpg');
			};
		</script>
		<img id="img" src="http://www.google.com/about/datacenters/gallery/images/_3000/IDI_012.jpg"/>
	</body>
</html>

```
