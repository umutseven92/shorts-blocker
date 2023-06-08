# Shorts Blocker

This extension ~~removes~~ hides (see below) Youtube Shorts from your subscriptions page by adding a [short CSS script](./css/blocker.css) to the page. 

## Change in Functionality

Unfortunately, as of writing (2023-06-08), YouTube changed the way thumbnails are displayed, and made it much harder to hide Shorts without breaking the layout. So I've decided to make it so that Shorts thumbnail opacities are lowered to 10%- they are still visible (unfortunately), but they are unobtrusive. 

The alternative is to remove the Shorts but completely break the layout of the page, which is worse, in my opinion.

## Requirements

* Chrome 105 and above (due to the [`:has` selector](https://developer.mozilla.org/en-US/docs/Web/CSS/:has))
