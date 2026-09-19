# Functionify

### Image → Mathematics → Art

Functionify is an interactive web project that explores how visual images can be represented using mathematics.

The project takes an uploaded image, analyzes its visual structure, extracts contours and coordinates, and transforms them into mathematical curves that can be visualized on a coordinate plane.

Instead of drawing an image manually, Functionify attempts to reconstruct it using mathematical functions.

---

## ✦ How it works

The project follows several stages:

**1. Upload**

The user uploads a PNG, JPG, or WEBP image.

**2. Analyze**

The image is processed using computer vision techniques. Its edges and contours are detected and converted into coordinate points.

**3. Approximate**

The extracted points are simplified and approximated using mathematical curves.

**4. Reconstruct**

The curves are converted into mathematical representations and displayed on a coordinate plane.

The final result is a mathematical reconstruction of the original image.

---

## ✦ Mathematical idea

The main idea of Functionify is to treat an image as mathematical data.

Instead of thinking about an image as a collection of pixels:

```text
IMAGE
↓
PIXELS
↓
COLORS
```

Functionify transforms it into:

```text
IMAGE
↓
CONTOURS
↓
POINTS
↓
CURVES
↓
EQUATIONS
```

This creates a connection between computer vision, mathematical modeling, and visual art.

---

## ✦ Features

* Upload PNG, JPG and WEBP images
* Automatic contour detection
* Image-to-coordinate conversion
* Mathematical curve approximation
* Interactive mathematical reconstruction
* Adjustable complexity
* Adjustable line thickness
* Generated mathematical equations
* Original image preview
* Mathematical drawing preview
* Processing statistics
* Responsive interface

---

## ✦ Technologies

### Frontend

* HTML
* CSS
* JavaScript

### Computer Vision

* OpenCV.js

### Mathematics

* Coordinate geometry
* Curve approximation
* Parametric curves
* Numerical representation of visual data

---

## ✦ Project concept

Functionify was created around a simple question:

> Can a visual artwork be translated into mathematics?

The project explores the idea that an image can be treated not only as visual information, but also as a mathematical structure.

Every contour contains coordinates.
Coordinates can be represented by curves.
Curves can be described mathematically.

Therefore, an image can be approached as a mathematical model.

---

## ✦ Why this project?

Mathematical graphing can be used not only for solving equations, but also for creating art.

Functionify explores the opposite direction of traditional graphing tools:

**Traditional approach:**

```text
Equation → Graph → Image
```

**Functionify:**

```text
Image → Data → Mathematics → Graph
```

The goal is to experiment with the boundary between mathematics, programming, and visual art.

---

## ✦ Future development

Possible future improvements include:

* More accurate curve fitting
* Bézier curve approximation
* Fourier-based curve reconstruction
* Better handling of complex images
* Color-based mathematical reconstruction
* Interactive equation editing
* Exporting generated equations
* Exporting mathematical drawings
* Direct integration with graphing platforms
* Gallery of mathematical artworks
* Comparison between reconstruction accuracy and number of functions

---

## ✦ Project structure

```text
Functionify/
│
├── index.html
├── style.css
├── script.js
├── README.md
├── LICENSE
│
└── assets/
    └── preview.png
```

---

## ✦ Status

**Prototype / In development**

Functionify is an experimental project focused on mathematical representation of visual information.

---

## Author

Created as an independent mathematics and programming project.
