# Banner Feature Images

The file "banner-feature-images.csv" is used to generate random images on the full bleed home page featured image.
"banner-feature-images-extras.csv" is a larger list of curated images to choose from to occasionally shuffle the main csv.

Fields:

- title - title of the item where it comes from (not alt, the image is considered decorative, but generates a link with the title)
- src - full url to the image (this might be the full size or small image depending on the collection. try not to use TOO big of images to avoid slow load time)
- position - valid css background position (center, top, bottom)
- link - full url to the Item page

Considerations:

- images should be landscape and work in the stretched and cropped form in a variety of screen sizes
- minimal text to avoid distraction
- some should be colorful (we have a lot of B&W)
- try to curate a variety of collections
- images should highlight items where we have clear rights (e.g. most of the postcards it is a bit sketchy)
- avoid potentially controversial or individually identifying images (vague interesting background is the vibe)
- avoid items with bad metadata (don't necessarily want to show off bad examples)
