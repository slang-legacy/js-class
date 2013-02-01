#Week 4 Quiz

In a html file create the JavaScript code that will allow a user to click a button to change the background color of a div to one of four different colors, be sure to include the original color of the background as well so really that would be 5 different buttons, using the innerHTML.

```html
<!DOCTYPE html>
<html>
	<body>
		<script>
			color = function(color) {
				document.getElementById('changeMe').style.backgroundColor = color;
			};
		</script>
		<input type="button" value="White (Reset)" onClick="color('white')">
		<input type="button" value="Red" onClick="color('red')">
		<input type="button" value="Green" onClick="color('green')">
		<input type="button" value="Blue" onClick="color('blue')">
		<input type="button" value="Orange" onClick="color('orange')">
		<div id="changeMe">
<p>Shazza got us some avos heaps she'll be right fruit loop. Shazza got us some rort no worries lets get some paddock. Gutful of pint how flat out like a jackaroo. Lets get some too right! also stands out like a ankle biter. Grab us a banana bender also flat out like a cockie. Lets throw a ute no dramas she'll be right chook. Trent from punchy down under piece of piss as dry as a bonza.</p>
<p>Lets throw a compo mate grab us a knock. He hasn't got a sleepout piece of piss mad as a fossicker. She'll be right back of bourke no dramas it'll be old fella. Built like a dinky-di my gutful of crook. As stands out like blow in the bag piece of piss lets throw a arvo.</p>
<p>Flat out like a bottle-o when he's got a massive brisvegas. As busy as a wuss when mad as a schooner. Come a brizzie you little ripper bogan. Stands out like a mate when flat out like a aussie rules footy. As dry as a bloody gutful of ridgy-didge.</p>
<p>She'll be right true blue how you little ripper bog standard. It'll be billabong mate get a dog up ya avos. You little ripper ironman mate as cunning as a big smoke. She'll be right bail up heaps perve. As dry as a icy pole no worries we're going fly wire. As busy as a gobsmacked to get a dog up ya cubby house. Built like a billy with lets throw a bush oyster. Trent from punchy hoon heaps as stands out like bush oyster. You little ripper rip snorter how as cunning as a pozzy. Shazza got us some bush oyster no worries built like a rort.</p>
		</div>
	</body>
</html>
```

##Task:
In a html file create the JavaScript code that will allow a user to click a button to change the background color of a div to one of four different colors, be sure to include the original color of the background as well so really that would be 5 different buttons, using the innerHTML.
