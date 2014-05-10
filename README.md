LESS Entypo Icons
=================

Entypo is a set of 250+ carefully crafted pictograms http://www.entypo.com.

This LESS file includes styles for outputting entypo icons using the :before pseudo element.

Entypo icons: 

```html
<span class="entypo entypo-globe"></span>
```

Social icons: 

```html
<span class="entypo-social entypo-social-github"></span>
```

Or with a mixin in your stylesheet:

```html
<span class="my-existing-class"></span>
```
```less
.my-existing-class {
	.entypo-icon( red, "\2665", 100px );
}
```