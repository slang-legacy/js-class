#Week 13 Project

In a html file create a forms section that asks for the users name and then has a radio box section. After each radio box has been selected create a button that uses JavaScript to check and verify which radio box was selected. Then create a series of check boxes that are followed by radio boxes for selecting items from some sort of list. Like favorite cars, Ford GM Chrysler,  and so on. The check boxes are the company types, like Ford, and the radio boxes are types of cars, Avenger, Taurus, and so on. The purpose to this is to have the car types disabled until the company type of check box is selected. You can do this for any type of list: Favorite Food, anything you wish. Just be sure that when the checked box is not checked, the radio boxes under it are disabled.

```html
<!DOCTYPE html>
<html>
<body>
<style>
	input[type=radio]:checked ~ ul,
	input[type=radio]:checked ~ label {
		display: block;
	}
	input[type=radio] ~ ul,
	input[type=radio] ~ label {
		display: none;
	}
</style>
<script type="text/javascript">
	//you don't need any JS for a simple project like this
</script>
<form name="stuff">
	<label>Name</label>
	<input id="userName" value="">
	<br>
	<br>
	<label>Favorite Map Projection?</label>
	<ul>
		<li>
			<label>Van Der Grinten: </label>
			<input type="radio" name="primary">
			<br>
			<label>Reason:</label>
			<ul>
				<li>
					<input type="checkbox">
					You're not a complicated person   you like circles.
				</li>
				<li>
					<input type="checkbox">
					You just wish it weren't square.
				</li>
				<li>
					<input type="checkbox">
					The Earth's not a square, it's a circle.
				</li>
				<li>
					<input type="checkbox">
					Today is gonna be a good day!
				</li>
			</ul>
		</li>
		<li>
			<label>Hobo-Dyer: </label>
			<input type="radio" name="primary">
			<br>
			<label>Reason:</label>
			<ul>
				<li>
					<input type="checkbox">
					You want to avoid cultural imperialism, but you've heard bad things about Gall-Peters.
				</li>
				<li>
					<input type="checkbox">
					You're conflict-averse and buy organic.
				</li>
				<li>
					<input type="checkbox">
					You use a recently-invented set of gender-neutral pronouns and think that what the world needs is a revolution in consciousness.
				</li>
			</ul>
		</li>
		<li>
			<label>Dymaxion: </label>
			<input type="radio" name="primary">
			<br>
			<label>Reason:</label>
			<ul>
				<li>
					<input type="checkbox">
					You like Isaac Asimov, XML, and shoes with toes.
				</li>
				<li>
					<input type="checkbox">
					You think the Segway got a bad rap.
				</li>
				<li>
					<input type="checkbox">
					You own 3D goggles, which you use to view rotating models of better 3D goggles.
				</li>
				<li>
					<input type="checkbox">
					You type in Dvorak.
				</li>
			</ul>
		</li>
	</ul>
</form>
</body>
</html>
```
