# Synthetic Dream

Interactive browser-based generative particle artwork inspired by Houdini-style procedural systems, digital matter, and camera-based hand control.

## Play the app

👉 **[Open Synthetic Dream](https://De-Dur.github.io/Synthetic_dream/)**

Replace this link with your final GitHub Pages link after publishing.

## What this project does

Synthetic Dream generates a moving field of particles directly in the browser.  
The visual system reacts to mathematical parameters, time-based motion, random variation, symmetry, inner glow, and optional hand-camera interaction.

The app creates abstract digital structures from thousands of animated points, allowing the image to shift between soft organic flow, computational drawing, and procedural spatial form.

## Why this project is useful

This project is useful as both:

- a visual art experiment
- a browser-based generative artwork
- a lightweight interactive app for desktop and mobile
- a study of Houdini-inspired procedural particle behavior
- a playful prototype for hand-controlled digital matter

Instead of creating one fixed rendered image, the app keeps the artwork alive through sliders, movement, randomization, symmetry, glow, and camera-based hand influence.

## Features

- real-time particle generation
- Houdini-inspired mathematical structure
- adjustable rows, columns, scale, speed, and point size
- editable wave and deformation parameters
- symmetry on/off control
- movable symmetry center
- inner orange glow control
- glow size control
- **Randomize** button for fast visual variations
- **Export PNG** button for saving still images
- optional camera-based hand interaction using MediaPipe
- fingertip tracking markers as visual feedback
- mobile-friendly bottom control panel
- single-file browser app

## Controls

Use the control panel to adjust the visual system.

Main actions:

- **Export PNG** — saves the current visual as an image
- **Randomize** — creates a new particle variation
- **Start Camera** — activates camera-based hand tracking

Important sliders:

- **Hand Influence** — controls how strongly the hands affect selected parameters
- **Symmetry On / Off** — enables or disables mirrored particle structure
- **Symmetry Center** — moves the axis of symmetry
- **Inner Orange Glow** — adds warm glowing energy inside the particle form
- **Glow Size** — changes the size of the orange glow
- **Scale** — changes visual size
- **Center X / Center Y** — shifts the visual composition
- **Cols / Rows** — changes particle density
- **Speed** — changes animation speed
- **Point Size** — changes particle thickness
- **X / Y Min and Max** — changes the generated field range
- **K Divide, K Subtract, Y Wave Divide, Q Add, Wave Power** — reshape the procedural motion and structure

## Hand interaction

Click **Start Camera** and allow camera permission to control the particle structure with your hands.

### One-hand control

When one hand is detected:

- **Move hand left / right** — changes **X Max**
- **Move hand up / down** — changes **Y Max**
- **Open / close fingers** — changes **Q Add**

### Two-hand control

When two hands are detected:

- **Left hand moves left / right** — changes **X Max**
- **Right hand moves up / down** — changes **Y Max**
- **Move both hands closer together or farther apart** — changes **Q Add**

### Visual hand feedback

When the camera is active, small pink and white fingertip circles appear over the artwork.  
These markers show that the app is detecting your hands and reading fingertip positions.

Camera interaction requires browser permission and works best through an HTTPS link, such as GitHub Pages.

## Files

- `index.html` — main interactive app file
- `README.md` — project description and usage guide
- `LICENSE` — license file

## Browser support

For the best experience, use a modern browser such as Chrome, Edge, Safari, or Firefox.

If the camera does not start:

- check browser camera permissions
- open the app from a secure HTTPS link
- try refreshing the page after permission is allowed
- try Chrome or Safari if another browser blocks the camera

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
