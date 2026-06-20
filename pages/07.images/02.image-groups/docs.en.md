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

[ui-accordion independent=false open=0]
[ui-accordion-item title="3 Photos <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="16" height="16" fill="currentColor"><path d="M11.9995 0.499512L16.9492 5.44926L15.535 6.86347L12.9995 4.32794V9.99951H10.9995L10.9995 4.32794L8.46643 6.86099L7.05222 5.44678L11.9995 0.499512ZM10.9995 13.9995L10.9995 19.6704L8.46448 17.1353L7.05026 18.5496L12 23.4995L16.9497 18.5498L15.5355 17.1356L12.9995 19.6716V13.9995H10.9995Z"></path></svg>"]

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
</div>
```

[/ui-accordion-item]
[ui-accordion-item title="4 Photos"]
(Coming Soon)
[/ui-accordion-item]
[/ui-accordion]