# MC-ID-API
This allows you to import and use all of Minecraft Items and Entities on your website using HTML, PHP, JS, NodeJS, Etc.

##### Installing
1. To install, simply put `<link rel="stylesheet" href="http://cdn.lightwiremc.net/MCIDAPI.css">` in to the `<head></head>` tags.
That's it! You can start using the MC ID API Class

#### Using HTML
By using HTMl, you can simply do `<span class="mc-id"></<span>`. However, thats not all, right after `mc-id` in the `span` tag, you need to tell the css file what item you want to display. For example, if you want to display a Diamond on your site, then you can type in the following code: `<span class="mc-id mc-diamond"></<span>`. If at anytime you want to know what the ID if a block/item is. Then open up the index.html file that came with this, open it up, then once everything loads, you can hover over the item and it will then show you what the ID if that item is. Another Example, if you son't know the ID of the Sunflower, open index.html, find and hover you mouse cursor over the sunflower, then it will tell you `mc-sunflower`.

#### Troubling Shooting
- Try using the SPAN Tag (`<span></span>`)
- Don't forget to put mc-id in the class of the Tag (`<span class="mc-id"></span>`)
- Make sure that you are linking the CSS file in`<head></head>`
- Make sure that you have an internet connection to `cdn.lightwiremc.net`

#### Coming Soon
- [] Add PHP Support for replacing keywords for Forums, etc.
- [] Add JS Support for replacing keywords for Forums, etc.
- [] Add AutoComplete Support for [Materialize CSS](www.materializecss.com)
- [] Add Entity Support

#### Full example
```html
<head>
	<link rel="stylesheet" href="http://cdn.lightwiremc.net/MCIDAPI.css">
</head>
<body>
	<p>The MC-ID-API class is really easy to learn and use. You barely need any HTML programming experience, however, you should need at least just enough to create a static website! But anyways, you need a Cookie! So, here's a Cookie: <span class="mc-id mc-cookie"></<span></p>
</body>
```
See how easy it it?!?!
