---
title: 'Image Headers'
date: '19:26 18-06-2026'
taxonomy:
    category:
        - docs
media_order: 'hero_light.png,standard_header_image.png,hero_dark.png'
published: true
---

Headers are the first information that your visitor will see. This is where you introduce yourself, your site, or put something unforgettable so they will stay on your page.


<h2 id="section">Light Hero Image</h2>
A hero image is an image that fills the visitor's screen. If your image has lighter colors, then the darker background will make your center text stand out.

![Hero image with a dark text background.](hero_dark.png "This helps if you have an image with light colors.")

```html
<!-- Header with Image -->
<header class="w3-display-container" style="height: 100vh; width: 100%; background-image: url('https://picsum.photos/1000/667.jpg'); background-size: cover; background-position: center; background-repeat: no-repeat; display: flex; align-items: center; justify-content: center;">
    <div class="w3-text-white w3-display-middle w3-center w3-padding w3-round" style="background-color: rgba(0, 0, 0, 0.4);">
        <h1 class="w3-wide" style="font-size: clamp(2rem, 5vw, 6rem); margin: 0;">Business Name</h1>
        <h2 class="w3-hide-medium w3-hide-small">Tagline or brief description.</h2>
        <p><a href="#" class="w3-black w3-button w3-margin-top">Info Button</a> <a href="#" class="w3-blue w3-button w3-margin-top">Action Button</a></p>
    </div>
</header>
<!-- End Header with Image -->
```

-----

<h2 id="section">Dark Hero Image</h2>
If your image has darker colors, then the lighter background will make your center text stand out.

![Hero image with a light text background](hero_light.png "This helps if your background image has dark colors.")

```html
<!-- Header with Image -->
<header class="w3-display-container" style="height: 100vh; width: 100%; background-image: url('https://picsum.photos/1000/667.jpg'); background-size: cover; background-position: center; background-repeat: no-repeat; display: flex; align-items: center; justify-content: center;">
    <div class="w3-text-white w3-display-middle w3-center w3-padding w3-round" style="background-color: rgba(255, 255, 255, 0.4);">
        <h1 class="w3-wide" style="font-size: clamp(2rem, 5vw, 6rem); margin: 0;">Business Name</h1>
        <h2 class="w3-hide-medium w3-hide-small">Tagline or brief description.</h2>
        <p><a href="#" class="w3-black w3-button w3-margin-top">Info Button</a> <a href="#" class="w3-blue w3-button w3-margin-top">Action Button</a></p>
    </div>
</header>
<!-- End Header with Image -->
```

-----

<h2 id="section">Standard Header Image</h2>
When you want a header image that is not too big and not too small. Make your image the dimensions that you want before uploading to your site.

![Standard header image with size limitations](standard_header_image.png "This gives your header color and interest without taking up too much room.")

```html
<header class="w3-display-container w3-wide">
     <img class="w3-image" src="https://picsum.photos/1000/300" width="100%">
	   <div class="w3-display-middle w3-margin-top w3-center">
		      <h1 class="w3-text-white w3-xxxlarge">Business Name</h1>
	   </div>
</header>
```