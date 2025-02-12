# Loading Animation


A small, focused project demonstrating lightweight loading animations built with standard web technologies. This repository contains example animations that are easy to reuse, adapt, and learn from — perfect for adding visual polish to web projects or studying CSS animation techniques.

## Preview

![Loading Animation Preview](https://github.com/mihaiapostol14/loading-animation/blob/3afe49a82fae35c7f08b89dde7e276f518b6998d/assets/preview.gif)

## Table of Contents
- [Loading Animation](#loading-animation)
  - [Preview](#preview)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Technologies Used](#technologies-used)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Development Notes](#development-notes)
  - [Contributing](#contributing)
  - [License](#license)
  - [Author](#author)

## Overview

This project showcases a variety of loading animations implemented using semantic HTML, modern CSS (including keyframes, transforms, and custom properties), and small amounts of JavaScript where needed to control or toggle animations. Each example is intended to be portable and simple to integrate into other projects.

## Technologies Used

- HTML
  - Provides semantic structure for each animation example (index or demo files).
  - Accessible markup where applicable (using aria-hidden, visually-hidden techniques, or descriptive text for screen readers).
- CSS
  - Core of the animations: keyframes, transforms (translate/rotate/scale), transitions, and composition techniques.
  - Use of CSS custom properties for easy tuning (colors, sizes, duration).
  - Responsive and scalable shapes using relative units so animations work across device sizes.
- JavaScript
  - Small, unobtrusive scripts to control animation playback or toggle demo states (start/stop/restart).
  - No heavy frameworks — plain vanilla JS for maximum portability.

## Installation

```bash
git clone https://github.com/mihaiapostol14/loading-animation.git
cd loading-animation
```
## Usage

- Browse the examples in the repository (typically index.html or a /demos directory).
- Copy the relevant HTML snippet and CSS rules into your project.
- Adjust CSS custom properties (variables) for colors, size, and duration to match your design system.
- If a demo includes a small JS controller, copy that script or adapt it to your application's lifecycle.

## Development Notes

- Keep animations performant:
  - Prefer transform and opacity changes (GPU-accelerated) over layout-triggering properties.
  - Limit heavy shadows or very large element counts for mobile devices.
- Organize new animations in a dedicated folder and include a short README describing the technique and browser considerations.

## Contributing

Contributions are welcome! If you'd like to add animations, examples, or improvements:
1. Fork the repo.
2. Create a feature branch.
3. Submit a pull request describing your changes.

Please include demo screenshots or a short GIF when adding visually distinct animations.

## License

This project is provided under the MIT License. See the LICENSE file for details.


## Author 
[Mihai Apostol](https://github.com/mihaiapostol14)