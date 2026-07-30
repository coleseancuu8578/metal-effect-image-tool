# Metal Effect v - Image Editing Tool 2026

> **Metal Effect is a browser-based, client-side editor that adds chrome or gold finishes to selected image areas through canvas masking and adjustable appearance controls.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Unreleased-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/coleseancuu8578/metal-effect-image-tool?style=flat-square)](https://github.com/coleseancuu8578/metal-effect-image-tool)

---

<p align="center">
  <a href="https://coleseancuu8578.github.io/metal-effect-image-tool/">
    <img src="https://img.shields.io/badge/Download-Metal%20Effect%20Latest-brightgreen?style=for-the-badge" alt="Download Metal Effect">
  </a>
</p>

> **[Download Metal Effect](https://coleseancuu8578.github.io/metal-effect-image-tool/)**

---

[Download Latest Build](https://coleseancuu8578.github.io/metal-effect-image-tool/)

---

## Overview

Metal Effect lets you apply chrome and gold-style finishes to selected portions of an image directly in your web browser. Canvas processing and polygon masks provide control over the exact regions affected by the effect.

All editing takes place locally rather than through an image upload service. While working, you can interactively adjust sheen, contrast, brightness, tint, opacity, feathering, and blending, then save the result as a PNG.

---

## What You Can Do

- Give images chrome or gold metallic treatments
- Define editable regions with polygon masks
- Switch masks between target and protect modes
- Modify opacity, sheen, contrast, brightness, and tint
- Soften mask boundaries with feathering
- Blend the metallic layer with the original image
- Undo changes or return the image to its reset state
- Save masks to JSON and load them again later
- Export finished images in PNG format
- Edit locally in the browser without uploading images

---

## Getting Started

### Open the hosted version

Launch the [latest build](https://coleseancuu8578.github.io/metal-effect-image-tool/) with a modern web browser.

### Work with a local copy

```bash
git clone https://github.com/coleseancuu8578/metal-effect-image-tool.git
cd REPO
```

Next, open the project's primary HTML file in a browser. If local asset access is restricted by your browser, use a basic local web server to serve the project directory.

---

## Editing Workflow

1. Start Metal Effect and load an image.
2. Select either the chrome or gold treatment.
3. Draw a polygon around the region you want to work on.
4. Use target mode to apply the treatment inside the polygon, or protect mode to preserve that region.
5. Refine opacity, sheen, contrast, brightness, tint, feathering, and blending.
6. Undo individual changes or reset the image as needed.
7. Export the mask to a JSON file if it should be used again.
8. Download the final result as a PNG.

---

## Settings and Local Use

There is no separate configuration file for the editor. Its appearance and effect options are controlled from the in-browser interface, and mask information can be stored or recovered using JSON export and import.

When running the project locally, leave the project files in the same directory and open the main HTML entry point directly or through a local web server.

---

## System Requirements

- A current web browser that supports canvas
- JavaScript enabled in the browser
- Access to the project files locally or to the hosted build
- Enough browser memory for the dimensions of the image being edited
- No server-side upload is needed during the editing process

---

## Frequently Asked Questions

### What browser support is needed?

Metal Effect requires a modern browser with JavaScript and HTML canvas support. Chrome is appropriate for this browser-based editor.

### Are both metallic finishes available?

Yes. You can choose between chrome and gold effects and fine-tune either one with the editor's adjustment controls.

### How can I limit the effect to a particular region?

Create a polygon mask, then select target mode or protect mode depending on whether the selected area should receive or retain the effect. Feathering is available to make the boundary more gradual.

### Is mask data reusable?

Yes. Save the current mask as a JSON file and import it later to restore that mask data.

### How do I export my result?

After finishing the adjustments, use the PNG download control.

### What can I try if processing fails?

Check that JavaScript is active, reload the editor, and try resetting the image. If the image is especially large, reducing its dimensions can make browser processing easier.

### Where can I find updates?

New versions are provided through the hosted build and the project repository. Review the latest published version before beginning another editing session.

### How are configuration changes handled?

Use the editor controls for ordinary visual adjustments. Reusable mask information is managed through JSON export and import, not through a separate settings file.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
