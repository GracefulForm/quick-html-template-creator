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

<button class="pure-button pure-button-primary" onclick="document.getElementById('nativeModal').showModal()">
  Open Native Modal
</button>

<dialog id="nativeModal" style="border: none; border-radius: 6px; padding: 20px; box-shadow: 0 4px 20px rgba(0,0,0,0.25); max-width: 600px; width: 100%;">
  <h3>Code Snippet Example</h3>

  <!-- Standard safe method for HTML blocks inside raw elements -->
  <pre><code>&lt;div class="test-element"&gt;
  &lt;p&gt;Hello World&lt;/p&gt;
&lt;/div&gt;</code></pre>

  <form method="dialog" style="text-align: right; margin-top: 20px;">
    <button class="pure-button">Close</button>
  </form>
</dialog>
