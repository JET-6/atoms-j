# Atoms J — Repository Outside Time

An interactive 2D/2.5D browser environment depicting a vast memory archive outside conventional time.

The scene presents a first-person view into a monumental library with towering wooden shelves, subtle embedded circuitry, a distant gold-and-black retro-futurist computer, and a large window overlooking a procedural city that moves through a full day-and-night cycle.

This project is part of the broader **Atoms J** universe.

## Why This Exists

The original idea was a navigable 3D library that would act as the central archive and interface for the Atoms J project.

The complexity of building the full 3D version made it difficult to reach a meaningful visual result quickly, so I shifted the concept into a 2D/2.5D format to create something tangible.

This prototype established the visual language, atmosphere, interaction model, and narrative tone of the larger idea.

## Features

- Interactive repository boot sequence
- Procedural library environment
- First-person framing
- Layered 2.5D parallax
- Gold-and-black diagnostic computer
- Functional lore terminal
- Procedural city window
- Day, dusk, night, and anomaly cycle
- Building-light transitions
- Interior lighting changes
- Web Audio synth ambience and glitch events
- Desktop and tablet support

## Visual Direction

The project combines:

- Classical dark-wood library architecture
- Gold and brass industrial details
- Black glass and amber terminal light
- Cyan, green, violet, and gold system indicators
- Procedural city architecture
- Atmospheric haze and dust
- Restrained glitch effects

The library remains the dominant visual identity. The technology appears embedded within the structure rather than replacing it.

## Technology

- HTML
- CSS
- JavaScript
- PixiJS
- GSAP
- Web Audio API

The main working prototype is contained in `index.html`.

Local copies of PixiJS and GSAP are included in the project.

## Running Locally

From the project folder:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

The script references should use relative paths:

```html
<script src="./lib/pixi.min.js"></script>
<script src="./lib/gsap.min.js"></script>
```

## Development Process

This project was developed through an AI-assisted workflow.

I created and refined the concept, visual direction, interaction requirements, narrative structure, and technical constraints. Replit Agent was used to generate the initial prototype and assist with implementation and debugging.

The process included:

- Designing the scene architecture
- Defining the fixed-camera interaction model
- Testing and refining the environment
- Repairing the terminal hotspot
- Adding the city window and time cycle
- Correcting high-DPI scene scaling
- Fixing reversed parallax direction
- Adjusting lighting and readability
- Exporting the project for independent local use

The project is preserved as both a visual prototype and an exercise in understanding, auditing, and maintaining AI-generated code.

## Current State

The project is considered a completed visual prototype.

The archive books are visible but not currently interactive. For this version, they remain inaccessible records within the environment rather than a blocking defect.

The archives can be seen.

They cannot yet be opened.

## Future Possibilities

- Restore archive-book interactions
- Expand terminal lore
- Add new archive records
- Replace procedural layers with custom artwork
- Add weather controls
- Refactor the standalone file into modular JavaScript
- Return to the original 3D library concept

## Author

Created and directed by **Jimi Thomas** as part of the broader **Atoms J** project.