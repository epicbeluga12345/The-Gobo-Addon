# The Gobo Addon v3.1.0

Turn any spot light in Blender into a gobo projector with a visible haze beam. Controls live in the Light tab of the Properties editor.

<img width="1920" height="1080" alt="gobocover" src="https://github.com/user-attachments/assets/2f6d04ca-ef4d-4222-8efb-a26531e0e239" />

## What's new
- **Glow haze** (default): a soft glow that never dims what's behind it. Use the **Brightness** slider to make it brighter or darker. The original **Lit** haze is still there.
- **Haze follows the gobo.** The dark parts of your gobo appear as dark streaks in the beam, using the same scale, rotation, invert and Clean Edges settings.
- **Follow Light Power:** the haze fades when the light's Power fades.
- **Fade Out:** the far end of the beam fades smoothly instead of cutting off.
- **Keyframes:** gobo and haze sliders can be animated.
- A gobo with no image now blocks all light, so the beam is blank.
- Fixed haze clipping away during animation, and stray cones left behind by hidden or deleted lights.

## Features
- **Gobo:** project any image from a spot light. White lets light through, black blocks it. Scale, rotate and invert the pattern, set the mask distance, and clean up noisy images with **Clean Edges**.
- **Haze:** a cone of haze that fills the beam. Controls for brightness, thicker toward the end, fade out and beam length, plus an eyedropper to measure the distance to the first surface. Draft, Good and Best quality presets.
- The mask and haze follow the light, resize with the spot angle, and hide when you hide the light or set its power to 0.
- Duplicating a light gives the copy its own mask and haze.

Works with Eevee and Cycles.

## Installation
1. Download `the_gobo_addon-3.1.0.zip` below. Don't unzip it.
2. In Blender, go to **Edit > Preferences > Get Extensions**.
3. Open the dropdown in the top right, choose **Install from Disk**, and select the zip.
4. Select a spot light, open the **Light** tab, and enable **Gobo** and **Haze**.

**Requires Blender 4.2 or newer.**

## Notes
- Haze Type, the image and the on/off ticks can't be keyframed.
- Older setups update automatically the next time you change a gobo or haze setting.

## License
GPL-3.0-or-later
