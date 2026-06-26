---
title: 'Image and Text Together'
date: '22:03 26-06-2026'
taxonomy:
    category:
        - docs
media_order: image-text-columns.jpg
---

Text and images can go side by side.

## Left Image with Right Text
On small screens, the left column will appear first and the right column below it.

![HTML Left Image with Right Text.](image-text-columns.jpg "This works on articles, a heading, or special section.")

```html
<div class="w3-row w3-content">
	<div class="w3-col m6 w3-padding-large">
		<img class="w3-image" src="https://picsum.photos/600">
	</div>
	<div class="w3-col m6 w3-padding">
		<h2>Paragraph Title</h2>
		<p class="w3-large">
			Lorem ipsum dolor sit amet, consectetur adipiscing elit. Anim exercitation consectetur cillum animi adipisci incididunt reprehenderit ea quas ipsa veritatis. Occaecat cupidatat laboris elit ea enim iusto in dolores provident fugit fugiat ipsam. Quisquam enim do dolor accusamus proident voluptatum elit aliqua numquam excepteur nemo eiusmod ex. Fugiat animi proident odio beatae illo. Eius enim occaecat dolore nostrud sequi veritatis.
		</p>
	</div>
</div>
```

---

## Left Text with Right Image
```html
<div class="w3-row w3-content">
	<div class="w3-col m6 w3-padding">
		<h2>Paragraph Title</h2>
		<p class="w3-large">
			Lorem ipsum dolor sit amet, consectetur adipiscing elit. Anim exercitation consectetur cillum animi adipisci incididunt reprehenderit ea quas ipsa veritatis. Occaecat cupidatat laboris elit ea enim iusto in dolores provident fugit fugiat ipsam. Quisquam enim do dolor accusamus proident voluptatum elit aliqua numquam excepteur nemo eiusmod ex. Fugiat animi proident odio beatae illo. Eius enim occaecat dolore nostrud sequi veritatis.
		</p>
	</div>
	<div class="w3-col m6 w3-padding-large">
		<img class="w3-image" src="https://picsum.photos/600">
	</div>
</div>
```