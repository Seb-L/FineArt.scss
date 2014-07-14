FineArt.scss
============

A dynamic &amp; parametric textured photo frame, in SASS.

## Install

In Terminal

```
bower install FineArt.scss
```

## Using

In your html :

```
<figure class="item">
	<div class="inner">
		<img src="http://placekitten.com/g/300/200" />
	</div>
	<figcaption class="title">
		<h1>Title</h1>
		You can change the image source as you want the frame will automaticly adjust, and change the frame width and mask width with the Mixin attributes.
	</figcaption>
</figure>
```

In your main .scss file:

```
@import 'compass';
@import 'bower_components/_fineart.scss';

.item{
	@include fineart(); // 2rem frame & mask by default
	// OR
	@include fineart(3rem, 1rem); // 3rem frame & 1rem mask 
}

```

## Demo

[http://codepen.io/SebL/pen/ACjDg](http://codepen.io/SebL/pen/ACjDg)