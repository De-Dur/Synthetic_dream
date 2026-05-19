# Synthetic Dream

Interactive browser-based generative particle artwork inspired by Houdini-style procedural systems and hand-controlled motion.

## Play the app

👉 **[Open Synthetic Dream](https://De-Dur.github.io/Synthetic_dream/)**

Replace this link with your final GitHub Pages link after publishing.

## What this project does

Synthetic Dream generates a moving field of particles directly in the browser.  
The visual system reacts to mathematical parameters, time-based motion, random variation, and optional hand-camera interaction.

The app creates abstract digital structures from thousands of animated points, allowing the image to shift between soft organic flow, computational drawing, and procedural spatial form.

## Why this project is useful

This project is useful as both:

- a visual art experiment
- a browser-based generative artwork
- a lightweight interactive app for desktop and mobile
- a study of Houdini-inspired procedural particle behavior
- a playful prototype for hand-controlled digital matter

Instead of creating one fixed rendered image, the app keeps the artwork alive through sliders, movement, randomization, and camera-based hand influence.

## Features

- real-time particle generation
- Houdini-inspired mathematical structure
- adjustable rows, columns, scale, speed, and point size
- editable wave and deformation parameters
- **Randomize** button for fast visual variations
- **Export PNG** button for saving still images
- optional hand-camera interaction using MediaPipe
- two-hand influence for changing particle field behavior
- single-file browser app

## Controls

Use the left control panel to adjust the visual system.

Main actions:

- **Randomize** — creates a new particle variation
- **Export PNG** — saves the current visual as an image
- **Start Hand Camera** — activates camera-based hand tracking

Important sliders:

- **Hand Influence** — controls how strongly the hands affect the particle field
- **Cols / Rows** — changes particle density
- **Speed** — changes animation speed
- **Scale** — changes visual size
- **Point Size** — changes particle thickness
- **X / Y Min and Max** — changes the generated field range
- **Wave controls** — reshape the procedural motion
- **Center X / Center Y** — shifts the visual composition

## Hand interaction

When camera mode is active, the artwork reacts to detected hand movement.

- hand position influences particle displacement
- finger spread changes wave behavior
- two hands can influence the generated range and scale
- fingertip markers are drawn over the artwork as visual feedback

Camera interaction requires browser permission and works best through an HTTPS link, such as GitHub Pages.

## Files

- `index.html` — main interactive app file
- `README.md` — project description and usage guide
- `LICENSE` — license file

## Browser support

For the best experience, use a modern browser such as Chrome, Edge, Safari, or Firefox.

If the camera does not start, check browser permissions and open the app from a secure HTTPS link.

## Maintainer

Created and maintained by **Denisa Durica**.

## Contributing

This repository is primarily an art and interaction design project.  
If you adapt or extend it, please keep the original artistic credit attached.

## License

This project is licensed under the MIT License.

## Attribution

Created by **Denisa Durica**.  
Please keep credit when sharing, remixing, or adapting this project.
