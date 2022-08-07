<p align="center">
  <img src="https://user-images.githubusercontent.com/6490641/183305469-e6a95246-b0c9-4816-8df5-2b92bdb03742.gif" alt="animated-favicon" />
</p>
<h2 align="center">Animated Favicon</h2>
<h3 align="center">Simply code to make your favicon animated</h3>

<br/>

### [🎮 Demo / Example](https://orsifrancesco.github.io/animated-favicon)
### ⚖️ Licensed under MIT
### 🤓 Author [@orsifrancesco](https://twitter.com/orsifrancesco)
### ☕ [Offer me a coffee](https://www.paypal.com/donate/?business=5EL4L2LDYVH96)
<!--### ☕ [Offer me a coffee](https://paypal.me/orsifrancesco)-->

<hr/>

## 📦 Just a snippet of code

```js
function animatedIcon() {

	const faviconAnimation = [
		"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"
	]

	if(!document.querySelector("head link[rel='icon']")) document.querySelector("head").innerHTML = document.querySelector("head").innerHTML + '<link rel="icon" type="image/png" sizes="32x32" href="">';
	
	document.querySelector("head link[rel='icon']").setAttribute('href', 'data:image/png;base64,' + faviconAnimation[0] + '');

	let animCount = 1;
	function animFoo() {
		if (animCount >= 4) { animCount = 1; }
		document.querySelector("head link[rel='icon']").setAttribute('href', 'data:image/png;base64,' + faviconAnimation[animCount] + '');
		animCount++;
	}

	setInterval(() => { animFoo() }, 500);

}

animatedIcon();
```

## ⚖️ License

Licensed under MIT


## ☕ About

Any feedback to [@orsifrancesco](https://twitter.com/orsifrancesco) and/or [coffee](https://www.paypal.com/donate/?business=5EL4L2LDYVH96) is welcome :) 