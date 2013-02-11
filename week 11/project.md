#Week 11 Project

In a html file create the JavaScript code that will set up an auto running pre-loaded slide show of at least six houses and asks the user to submit his or her income, be sure to state no dollar signs or commas, and then uses that value to tell the user which one of the six houses he or she can afford. Add some CSS and HTML code to liven up the look of your "realtor web site".

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
				'http://upload.wikimedia.org/wikipedia/commons/1/12/This_Old_House.jpg',
				'http://4.bp.blogspot.com/-N3Fg_siwG-U/UI9lqDfyDHI/AAAAAAAAURY/HLAkro1KU50/s1600/two-floor-house.jpg',
				'http://mendotadakota.com/mn/wp-content/uploads/2008/11/poor-native-american-indians-shelter-shack-dilapitaed1.jpg',
				'http://4.bp.blogspot.com/_wOq8qYza20s/TCq3tw-0jUI/AAAAAAAAH1Y/CPm9C26X27k/s1600/3387-turf-houses.jpg',
				'http://laughingsquid.com/wp-content/uploads/xdscn3444-640x480.jpg',
				'http://fc06.deviantart.net/fs31/f/2008/216/3/7/Dr_House_Wallpaper_by_mimizz.jpg'
			];

			val = +(prompt("What's your budget?").match(/[0-9\.]+/)[0]);
			val = (val > 10000000 ? 10000000 : val) / 10000001 * imgs.length;
			document.getElementById('img').setAttribute("src", imgs[Math.floor(val)]);
		</script>
		<style type="text/css">
		div {
			background-color: black;
			border: dotted 5px orange;
		}
		h1 {
			font-size: 52px;
			color: green;
		}
		</style>
		<img id="img"/>
	</body>
</html>
```
