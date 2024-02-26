---
author: "Peter Zdravecký"
title: "Image Stippling"
date: "2024-02-26"
summary: "Creating an image using stippling technique. By moving the dots and changing their size and color based on the pixel they are covering, it is possible to create astonishing images."
tags: ["p5js", "stippling", "generative art"]
cover:
    image: "stippling/statue_stippled.png"
---

This project was an exploration of the `p5js` library and its capabilities, by converting images into stippled artwork. The concept revolves around forming an image using dots of various sizes and densities. While my focus primarily lay on grayscale images, the method allows for experimentation with color as well.

## Understanding Stippling

Stippling involves strategically placing dots on an image, taking into account the brightness of each pixel. Brighter areas accommodate more dots, resulting in a visually pleasing distribution. However, simply scattering dots randomly isn't sufficient for achieving a polished appearance; it tends to produce a grainy, unrefined effect.

I wanted to try another approach by creating a stippling effect that is more visually appealing and captures the essence of the original image.

To address this, I tried a method where dots are placed randomly on the canvas. They are randomly moved around, and their size and color are adjusted based on the pixels they cover on the original image. Importantly, I chose not to clear the background between redraws. This approach allows for a more organic and natural appearance in the final image.

## Gallery

The following example shows the difference between size of the dots. The first image is created using bigger dots, the second one is created using smaller dots. The second image is more detailed.

Bigger Dots             | Smaller Dots
:-------------------------:|:-------------------------:
![dragon stipple low resolution](/portfolio/stippling/dragon_low_res.gif)  |  ![dragion stipple high resolution](/portfolio/stippling/dragon_high_res.gif)

More examples:

![mona lisa stippled](/portfolio/stippling/mona_stipple.png)
![papagay stippled](/portfolio/stippling/bird_stipple.png)
![statue stippled](/portfolio/stippling/statue_stippled.png)
