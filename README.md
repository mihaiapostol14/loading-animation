# Loading Animation

## Preview

![Loading Animation Preview](https://github.com/mihaiapostol14/loading-animation/blob/eae4ae9a9fac0e5ac6ff9043c2f901231c49d6a7/assets/preview.gif)

## Repository Overview

- **Owner:** [mihaiapostol14](https://github.com/mihaiapostol14)
- **Language Composition:** 
  - CSS: 58.6%
  - HTML: 41.4%
- **Visibility:** Public
- **Created:** 20 days ago
- **Updated:** 20 days ago
- **Default Branch:** main
- **Topics:** (No topics specified)
- **Size:** 2 KB
- **License:** Not specified
- **Stargazers:** 0
- **Watchers:** 0
- **Forks:** 0
- **Open Issues:** 0

## Repository Description

This repository contains a CSS snippet that creates a spinning loader animation using `@keyframes` and `border` styling. Below is a breakdown of the code:

### Body Styling

- The background color is set to black (`#000`).
- The height is set to `100vh` to occupy the full viewport height.
- The display is set to `flex` to center the spinner easily.
- `Overflow: hidden` ensures no content spills outside the viewport.

### Spinner Styling

- A `div` with the class `.spinner` acts as the main rotating element.
- The width and height are both set to `10em`.
- A top border of `1em solid #0077ff` is used to create a visible arc.
- A right border of `1em solid transparent` ensures a semi-circle effect.
- The element is rounded using `border-radius: 50%`.
- It is centered using `margin: auto`.
- The `animation: spinner 2s linear infinite` applies a continuous rotation effect.

### Circle Element

- A small circle (`.circle`) is created with `width: 1em` and `height: 1em`.
- It has a blue (`#0077ff`) background and `border-radius: 50%` to make it a perfect circle.
- The `border-left: 8.5em` and `border-top: 0.5em` seem to be unintended or misused properties.

### Spinner Animation

- The `@keyframes spinner` animation rotates the `.spinner` by `360deg`.
- The transition is set to `0.4s all ease`, but `transition` inside `@keyframes` is unnecessary.

### Potential Fixes

1. The `.circle` class might need `position: absolute` to correctly place it within `.spinner`.
2. The `transition` inside `@keyframes` should be removed as it does not work there.
3. The `border-left` and `border-top` properties in `.circle` should be reconsidered.

This code produces a simple, visually appealing rotating loader that can be used for loading screens or progress indicators.

## Additional Information

- **Repository Link:** [loading-animation](https://github.com/mihaiapostol14/loading-animation)
- **Owner Profile:** [mihaiapostol14](https://github.com/mihaiapostol14)

## Cloning the Repository

To clone this repository, use the following command:

```bash
git clone https://github.com/mihaiapostol14/loading-animation.git
```