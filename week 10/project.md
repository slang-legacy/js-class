#Week 10 Project

In a html file create the JavaScript code that will pre-load and auto run a minimum 6 image slide show. This is an important skill as many sites will wish to show off samples of their products, houses for sale, products for sale, samples of their work, like landscaping projects. The images need to be all the same size. Submit your finished work here.

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
			imgs = [
				'http://www.google.com/about/datacenters/gallery/images/_3000/CBF_008.jpg',
				'http://www.google.com/about/datacenters/gallery/images/_3000/IDI_012.jpg',
				'http://www.google.com/about/datacenters/gallery/images/_3000/CBF_019.jpg',
				'http://www.google.com/about/datacenters/gallery/images/_3000/DLS_013.jpg',
				'http://www.google.com/about/datacenters/gallery/images/_3000/CBF_013.jpg',
				'http://www.google.com/about/datacenters/gallery/images/_3000/DLS_017.jpg'
			];

			img = document.getElementById('img');
			i = 0;

			setInterval(
				function(){img.setAttribute("src", imgs[i == 6 ? i = 0 : i++]);},
				3000
			);
		</script>
		<img id="img"/>
	</body>
</html>

```
