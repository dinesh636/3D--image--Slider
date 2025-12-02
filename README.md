3D Image Slider
The 3D Image Slider is an interactive front-end project built with HTML5 and CSS3, designed to create an immersive visual experience through smooth, three-dimensional transitions. By combining modern CSS transformations with well-structured HTML, the slider delivers a dynamic and visually engaging interface suitable for portfolios, galleries, and modern web applications.

Features
Multi-image Display
Uses multiple <img> elements to showcase a collection of images within the slider.

3D Visual Effects
Leverages CSS properties such as perspective, transform, and transform-style to create depth and realistic 3D rotation.

Mathematically Driven Animation
Image spacing, rotation angles, and positioning are calculated using CSS-based formulas, ensuring smooth transitions and perfectly distributed elements in 3D space.

Smooth, Continuous Rotation
Images rotate seamlessly around a central axis, producing a modern carousel-like effect.
 
 How It Works
Each image is placed in a circular 3D layout using transform: rotateY() and translateZ().

A global perspective value is applied to the container, giving the illusion of depth and spatial rotation.

CSS animations rotate the entire image set, allowing the slider to cycle through images automatically.

Mathematical formulas determine the angle and distance of each image from the center, ensuring equal spacing and a clean 3D structure.

Technologies Used
HTML5 – for structuring the slider and embedding images.

CSS3 – for creating 3D effects using:

perspective

transform (rotateY, translateZ, etc.)

Advanced selectors and animations
