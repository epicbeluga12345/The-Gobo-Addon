# The Gobo Addon

Turn any spot light in Blender into a gobo projector with a visible haze beam, set up in a few clicks.

A gobo is a stencil placed in front of a light to throw a pattern, like window blinds, foliage, cobblestones or a logo. This addon builds the setup for you and keeps it attached to the light.

<!-- Add screenshots here, for example: -->
<!-- ![Cobblestone gobo with haze](docs/cobblestones.png) -->

## Features

### Gobo
- Project any image from a spot light. White lets light through and black blocks it.
- Scale, rotate and invert the pattern, and set how far in front of the light the mask sits.
- **Clean Edges** slider removes speckle and fuzzy fringes caused by noise in the image.
- The soft edge follows the light's radius, from crisp to blurry.

### Haze
- A volumetric cone fills the beam so you can see the light shafts, including the shapes your gobo cuts into them.
- Controls for thickness, thicker-toward-end, forward glare and glow.
- Eyedropper measures the beam length to the first surface it hits.
- **See Through** slider keeps the haze from darkening what's behind it (Eevee).
- Draft, Good and Best quality presets.

### Easy to manage
- Everything is in the **Light** tab of the Properties editor.
- The mask and haze follow the light. They resize with the spot angle and hide when you hide the light or set its power to 0.
- Duplicating a light gives the copy its own mask and haze.
- A **Remove Leftover Helpers** button cleans up after deleted lights.

Works with Eevee and Cycles.

## Installation

Requires **Blender 4.2 or newer**.

1. Download `the_gobo_addon-3.0.0.zip` from the [Releases](../../releases) page. Don't unzip it.
2. In Blender, go to **Edit > Preferences > Get Extensions**.
3. Open the dropdown in the top right, choose **Install from Disk**, and select the zip.

## Usage

1. Select a spot light.
2. Open the **Light** tab in the Properties editor.
3. Enable **Gobo** and choose an image.
4. Enable **Haze** and adjust it to taste.

## Tips
- Use high-contrast black and white images. Soft grey gradients work, but set Clean Edges to 0 so they aren't snapped to black or white.
- See Through only affects Eevee. Set it to 0 in Cycles, and lower Thickness if the haze darkens the background.
- If the haze looks grainy, raise the Quality preset.

## License

GPL-3.0-or-later
