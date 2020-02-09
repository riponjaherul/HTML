## Responsive Web Design (RWD)
- **Viewport :**
	- The viewport is the user's visible area of a web page, The viewport varies with the device, and will be smaller on a mobile phone than on a computer screen.
	- HTML5 introduced a method to let web designers take control over the viewport, through the `<meta>` tag. ***`<meta name="viewport"  content="width=device-width, initial-scale=1.0">`***
	- A `<meta>` viewport element gives the browser instructions on how to control the page's dimensions and scaling.
	- The `width=device-width` part sets the width of the page to follow the screen-width of the device (which will vary depending on the device).
	- The `initial-scale=1.0` part sets the initial zoom level when the page is first loaded by the browser.

- **Size Content to The Viewport**
	- **1. Do NOT use large fixed width elements**
	- **2. Do NOT let the content rely on a particular viewport width to render well** - Since screen dimensions and width in CSS pixels vary widely between devices, content should not rely on a particular viewport width to render well.
	- **3. Use CSS media queries to apply different styling for small and large screens**

- **Max-width**: for example : `@media (max-width:768px ) { … }`, It means whatever CSS you write within this { …. } will work till 0px to 768px.
- **Min-width**:for example : `@media (min-width:1024px ) { … }`, It means whatever CSS you write within this { …. }will work till 1024px from any larger.
