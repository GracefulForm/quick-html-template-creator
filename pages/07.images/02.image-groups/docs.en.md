---
title: 'Image Groups'
date: '20:39 18-06-2026'
taxonomy:
    category:
        - docs
---

There are times when you want to display groups of images, such as a photo album, a portfolio, or even just decoration.

## Employee or Labeled Gallery

```html
<div class="w3-container w3-content">
	<div class="w3-center">
		<div class="w3-row-padding">
			<div class="w3-col l3 m6 w3-margin-bottom">
				<div class="w3-display-container">
					<div class="w3-display-topleft w3-black w3-padding">President</div>
					<img src="https://picsum.photos/id/91/400/300" style="width:100%">
				</div>
			</div>
			<div class="w3-col l3 m6 w3-margin-bottom">
				<div class="w3-display-container">
					<div class="w3-display-topleft w3-black w3-padding">Deputy</div>
					<img src="https://picsum.photos/id/175/400/300" style="width:100%">
				</div>
			</div>
			<div class="w3-col l3 m6 w3-margin-bottom">
				<div class="w3-display-container">
					<div class="w3-display-topleft w3-black w3-padding">Queen</div>
					<img src="https://picsum.photos/id/177/400/300" style="width:100%">
				</div>
			</div>
			<div class="w3-col l3 m6 w3-margin-bottom">
				<div class="w3-display-container">
					<div class="w3-display-topleft w3-black w3-padding">Aaron</div>
					<img src="https://picsum.photos/id/237/400/300" style="width:100%">
				</div>
			</div>
		</div>
	</div>
</div>
```


-----

## Photo Gallery

```html
<div class="container w3-content">
	<div class="w3-row-padding w3-margin-top">
		<div class="w3-third">
			<div class="w3-card">
				<img src="https://picsum.photos/400/300?random=1" style="width:100%">
				<div class="w3-container">
					<h5>Trip</h5>
				</div>
			</div>
		</div>
		<div class="w3-third">
			<div class="w3-card">
				<img src="https://picsum.photos/400/300?random=2" style="width:100%">
				<div class="w3-container">
					<h5>Summer</h5>
				</div>
			</div>
		</div>
		<div class="w3-third">
			<div class="w3-card">
				<img src="https://picsum.photos/400/300?random=3" style="width:100%">
				<div class="w3-container">
					<h5>Project</h5>
				</div>
			</div>
		</div>
	</div>
	<div class="w3-row-padding w3-margin-top">
		<div class="w3-third">
			<div class="w3-card">
				<img src="https://picsum.photos/400/300?random=4" style="width:100%">
				<div class="w3-container">
					<h5>Birthday</h5>
				</div>
			</div>
		</div>
		<div class="w3-third">
			<div class="w3-card">
				<img src="https://picsum.photos/400/300?random=5" style="width:100%">
				<div class="w3-container">
					<h5>Graduation</h5>
				</div>
			</div>
		</div>
		<div class="w3-third">
			<div class="w3-card">
				<img src="https://picsum.photos/400/300?random=6" style="width:100%">
				<div class="w3-container">
					<h5>Vacation</h5>
				</div>
			</div>
		</div>
	</div>
</div>
```

---

<!-- Button: Opens modal and triggers Prism coloring -->
<button class="button" style="background-color: #FA5F55; color: #ffffff; border: none; padding: 10px 20px; display: inline-block; text-decoration: none;" onclick="document.getElementById('nativeModal').showModal(); if(window.Prism) { Prism.highlightAllUnder(document.getElementById('nativeModal')); }">
  View &amp; Copy Code
</button>

<dialog id="nativeModal" style="border: none; border-radius: 6px; padding: 20px; box-shadow: 0 4px 20px rgba(0,0,0,0.25); max-width: 600px; width: 100%;">

  <!-- 1. The visible code block stays clean and empty -->
  <pre><code id="modal-code-block" class="language-html"></code></pre>

  <!-- 2. The <template> tag keeps all raw HTML completely intact without losing the trailing tags -->
  <template id="raw-code-template">
<div class="w3-container w3-content">
    <div class="w3-center">
        <div class="w3-row-padding">
            <div class="w3-col l3 m6 w3-margin-bottom">
                <div class="w3-display-container">
                    <div class="w3-display-topleft w3-black w3-padding">President</div>
                    <img src="https://picsum.photos/id/91/400/300" style="width:100%">
                </div>
            </div>
            <div class="w3-col l3 m6 w3-margin-bottom">
                <div class="w3-display-container">
                    <div class="w3-display-topleft w3-black w3-padding">Deputy</div>
                    <img src="https://picsum.photos/id/175/400/300" style="width:100%">
                </div>
            </div>
            <div class="w3-col l3 m6 w3-margin-bottom">
                <div class="w3-display-container">
                    <div class="w3-display-topleft w3-black w3-padding">Queen</div>
                    <img src="https://picsum.photos/id/177/400/300" style="width:100%">
                </div>
            </div>
            <div class="w3-col l3 m6 w3-margin-bottom">
                <div class="w3-display-container">
                    <div class="w3-display-topleft w3-black w3-padding">Aaron</div>
                    <img src="https://picsum.photos/id/237/400/300" style="width:100%">
                </div>
            </div>
        </div>
    </div>
</div>
  </template>

  <!-- 3. Safe script injection pulls the template's innerHTML cleanly -->
  <script>
    document.getElementById('modal-code-block').textContent = document.getElementById('raw-code-template').innerHTML.trim();
  </script>

  <form method="dialog" style="text-align: right; margin-top: 20px;">
    <button class="pure-button">Close</button>
  </form>
</dialog>
