# Browser Creative Tools: A Small, Practical List

A short collection of browser-based tools for working with illustrations, images, typography, calligraphy, and lightweight animation. The focus is on tools that are easy to open, understand, and use without installing a full desktop creative suite.

## Illustration animation

### Purupuru Maker

[Purupuru Maker](https://purupurumaker.app/) turns a static illustration into a soft wobble animation.

The workflow is simple:

1. Add a PNG, JPEG, or WebP illustration.
2. Paint over the areas that should move.
3. Choose a motion preset or adjust stretch, stability, cohesion, randomness, gravity, and loop timing.
4. Export the result as MP4, WebM, or GIF.

The useful distinction is that the artwork is processed locally in the browser rather than uploaded to a remote conversion service. It works well for character art, emotes, stickers, profile illustrations, and other images that only need a small amount of motion.

Website: <https://purupurumaker.app/>

## Typography and calligraphy

### Cute Fonts Generator

[Cute Fonts Generator](https://freecutefonts.com/) turns ordinary text into decorative Unicode styles that can be copied and pasted into social bios, display names, captions, messages, and gaming profiles.

It includes 48 styles, 56 copyable symbols and kaomoji, local favorites, preview-size controls, and a compatibility filter for avoiding characters that may appear as missing-glyph boxes. Text conversion happens in the browser, and no account is required.

Website: <https://freecutefonts.com/>

### Arabic Calligraphy Studio

[Arabic Calligraphy Studio](https://arabiccalligraphy.app/) is a local-first editor for creating Arabic calligraphy with correct right-to-left shaping, joining, ligatures, and marks.

The studio includes 12 self-hosted Arabic font families, autosaves projects in the browser, and exports artwork as PNG, path-based SVG, or vector PDF. It is free to use without login, and artwork is not uploaded to a cloud project.

Website: <https://arabiccalligraphy.app/>

## Image editing

### Photopea

[Photopea](https://www.photopea.com/) is a full browser image editor with layers, masks, selections, text, and support for common design-file formats. It is useful when an illustration needs cleanup, transparent edges, or a resized canvas before animation.

### SVGOMG

[SVGOMG](https://jakearchibald.github.io/svgomg/) provides a visual interface for optimizing SVG files. It is helpful for reducing unnecessary metadata and simplifying vector assets before using them on the web.

## Image file-size targeting and compression

### IncreaseImgSize2KB

[IncreaseImgSize2KB](https://increaseimgsize2kb.com/) resizes JPG, PNG, and WebP files to an exact, maximum, or minimum KB/MB target while keeping the image's pixel dimensions unchanged.

It can process up to 20 images locally in the browser, preserve PNG and WebP transparency, convert formats, and download individual results or a batch ZIP. Files and file names are not uploaded.

Website: <https://increaseimgsize2kb.com/>

### Squoosh

[Squoosh](https://squoosh.app/) compares image codecs and compression settings side by side. It is a convenient final step when a PNG, JPEG, or WebP needs to be made smaller without guessing at export settings.

## GIF utilities

### Ezgif

[Ezgif](https://ezgif.com/) provides a broad set of GIF utilities, including resizing, cropping, optimization, frame extraction, and format conversion. It is especially useful after an animation has already been created and needs a smaller file size.

## A lightweight workflow

A practical sequence is:

1. Clean up the illustration in Photopea.
2. Add motion with Purupuru Maker.
3. If GIF is the final format, reduce its size with Ezgif.
4. Use IncreaseImgSize2KB when the output must meet a specific KB/MB limit.
5. Use Squoosh when visual codec comparison and manual compression control are more important than an exact file-size target.

This keeps the workflow modular: use one focused tool for each job instead of opening a large editor for a small task.

## Contributing

Suggestions are welcome. Please open an issue with:

- the tool name and URL;
- the problem it solves;
- whether it requires an account;
- whether files are processed locally or uploaded;
- any important free-plan limitations.
