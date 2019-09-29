# Brand Design

## Our Logo and Background Contrast

Avoid placing the transparent source logo right on top of too dark of a background.

Options:

1. Back the image by an opaque grey disc or square or some other color/shape that provides contrast.
2. Back the entire section that the logo appears on (the header bar for instance) with a semi transparent grey layer to insure that whatever is behind the layer is still mostly visible, but insures that enough contrast is provided to make out the full logo (this is mostly important in situations where we want to use that space to display food options, but the food options might include particularly dark regions). 

> Half of our logo (the chef hat) is visible against any background because it's a bright white hat with a dark black outline. That isn't true for the other half though which is predominantly made up of that same dark black line sketching out a moustache and beard which is nominally filled in with some dark brown. Against a black or very dark background the moustache and beard nearly disappear and all you see is a little bit of the white unbearded jowl surrounding the black outline of the mouth.


## Accessibility

We should keep colorblindness in mind and try to make sure that any text (ideally including our site name if we choose to display it) is legible. 


## Light vs Dark modes?

CSS has introduced a new proposed media query for supporting "dark mode".

```
@media (prefers-color-scheme: dark) {
```

Even though the name seems to suggest it might also be used for general accessibility preferences, the proposal only includes `dark` and `light` options.

One extra suggestion going around for dark mode preferences is not only to go with a dark background, but also to reduce the opacity for images against that dark background so as to dim them. Our entire screen is general covered with images of food, so this is pretty important for us. Would we want to dim the images in such a way? Would we want to go so far as to have separate sets of images for dark and light mode (based on the luminosity of the images)? I think the answer is no as it's a bit of an extreme option, but it could be an interesting thought. 