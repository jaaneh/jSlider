# jSlider - A jQuery carousel slider.

### The only carousel slider you'll ever need.

![](jSlider.gif)

# Download

Latest release: **v1.0**<br>
You can download the latest release from our [releases tab.](https://github.com/jaaneh/jSlider/releases)

You can also clone this repo to download the latest jSlider version.<br>
`git clone https://github.com/jaaneh/jSlider.git`

## How to use

```html
<!-- Place your images inside the #slider div as shown. -->
<div class="container">
	<div class="slider-wrapper">
		<span class="arrow">
			<span id="prev-arrow"><i class="fas fa-chevron-left fa-2x"></i></span>
			<span id="next-arrow"><i class="fas fa-chevron-right fa-2x"></i></span>
		</span>
		<div id="slider">
			<!-- Place your images here -->
			<img src="images/slide1.png" class="slider-image" alt="" />
			<img src="images/slide2.png" class="slider-image" alt="" />
			<img src="images/slide3.png" class="slider-image" alt="" />
		</div>
	</div>
</div>
```

For jSlider to function as intended, you need to include these script tags in your HTML code.<br>jSlider uses jQuery to function and Font Awesome for chevrons, so make sure they are included in the following order:

```html
<script src="https://code.jquery.com/jquery-3.4.1.min.js"></script>
<script src="js/fa.min.js"></script>
<script src="js/jslider.min.js"></script>
```

jSlider also comes with styling, so make sure you either include the .css file in your _\<head>_ tag, or copy the contents into your own stylesheet.

```html
<link type="text/css" rel="stylesheet" href="css/jslider.min.css" />
```
