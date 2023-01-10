### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces.

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function (hungry, availableTime) {
	if (!hungry) {
		console.log("No, I'm not hungry yet. ");
		return;
	}

	if (availableTime < 20) {
		console.log(
			"Please pick up a snack or something directly in the refrigerator. "
		);
	} else if (availableTime >= 20 && availableTime < 30) {
		console.log("Need to take a break and cook something nicely. ");
	} else if (availableTime >= 30)
		console.log("You're in the bootcamp. Have no time to take a nap.");
};
```
