# Responsive Web Design Project


https://stevene98.github.io/responsive-webdesign/

This repository contains a sample responsive web page demonstrating product presentation for hiking poles. It is written in plain HTML and CSS and includes a small script for basic animations.

## Usage

1. Clone or download this repository.
2. Make sure all image files are placed inside the `Bilder` directory in the project root. The `hiking_poles.glb` 3D model should remain next to `index.html`.
3. Open `index.html` in your web browser to view the page. For best results you can serve the files using a local web server.

## Required Assets

The page expects several images stored in the `Bilder` folder and a glTF binary (`.glb`) model in the project root:

- `Bilder/nikelogo.jpeg`
- `Bilder/Gemini_Generated_Image_frau.jpeg`
- `Bilder/Gemini_Generated_Image_man.jpeg`
- `Bilder/Gemini_Generated_Image_kind.jpeg`
- `Bilder/resized_rei1.jpeg`, `Bilder/resized_rei2.jpg`, `Bilder/resized_rei3.jpeg`, `Bilder/resized_rei4.jpeg`, `Bilder/resized_rei5.jpeg`, `Bilder/resized_rei6.jpeg`
- `hiking_poles.glb` (3D hiking pole model)

These files must be present for the web page to render correctly.

## Binary Assets

All images, PDFs, DOCX, PPTX files and the `.glb` 3D model are stored directly in this repository. The total project size is under 100&nbsp;MB, so using Git LFS is unnecessary. Keeping the assets in Git allows the page to work out-of-the-box when cloning the repo.
