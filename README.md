Here’s a simple yet informative `README.md` file for your project:

---

# NBA Players Slider Animation

This project showcases an NBA-themed slider animation created using just **HTML** and **CSS**, without any JavaScript. The slider highlights NBA players with a dynamic 3D effect, smoothly rotating between images.

## Features

- **3D Slider Animation**: A rotating slider that displays NBA player images in a continuous loop.
- **Fully Responsive**: Designed to adjust to various screen sizes.
- **No JavaScript**: Pure HTML and CSS implementation.
- **Custom Fonts**: Incorporates the fonts *ICA Rubrik* and *Poppins* for stylish text.
- **Background and Overlay**: A blurred basketball court background with a custom NBA logo overlay.

## How It Works

The CSS `@keyframes` property is used to rotate the images in 3D. Each image is positioned using CSS variables for the correct placement and rotation in the slider.

```css
@keyframes autoRun{
    from{
        transform: perspective(900px) rotateX(-15deg) rotateY(0deg);
    }
    to{
        transform: perspective(900px) rotateX(-15deg) rotateY(360deg);
    }
}
```

## Files

- **index.html**: The main HTML file containing the structure of the slider.
- **style.css**: The CSS file where the styles and animations are defined.
- **Images Folder**: A folder that contains images of NBA players used in the slider.

## Installation

1. Clone this repository or download the source files.
2. Ensure that the **images** (e.g., `img_2.jfif`, `Michael Jordan.jfif`) are placed in the correct directory.
3. Open `index.html` in any web browser to view the slider.

## Fonts Used

- [ICA Rubrik Black](https://fonts.cdnfonts.com/css/ica-rubrik-black)
- [Poppins](https://fonts.cdnfonts.com/css/poppins)
