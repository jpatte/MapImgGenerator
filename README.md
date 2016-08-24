# FeatureMap Image Generator

This is a simple image generator for [FeatureMap](https://www.featuremap.co). See the generator in action [here](https://jpatte.github.io/MapImgGenerator/).

While FeatureMap has a built-in feature to export a map as an image, it doesn't provide any option to indicate the desired image resolution (yet). The exported image might be too small for printing, so this script relies on the JSON export of a map to generate an image at any resolution.

## Implemented

- Draw all the cards of a map at the specified resolution
- Respect cards color
- Show cards label, due date, estimate and status
- If the generated image is too big to be downloaded at once, split the image into two parts

## Not implemented (yet?)
- Show aggregate statuses and estimates
- Show estimate units
- Let user force the size of cards
- Provide a menu with usual image resolutions for printing (A3, A2 etc).

This code is free to use and can be copied/transformed/used without restriction.