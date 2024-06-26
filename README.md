
# Parallax Website with Scroll-Triggered Animations 

This project demonstrates a parallax website with advanced CSS animations, creating an immersive and dynamic user experience. The key features include background elements moving at different speeds than the foreground content, smooth scroll-triggered animations, and a visually appealing design.

## Key Features

### 1. Parallax Scrolling Effect

The parallax effect is achieved through multiple layered div elements (`.top__layer`) each covering the full viewport (`100vw` by `100vh`). These layers are stacked and positioned fixedly, ensuring they stay in place while the user scrolls through the content.

### 2. Smooth Animations

Each layer is animated using keyframe animations to scale up at different rates:
This scaling effect contributes to the parallax effect by making background elements appear to move slower than the foreground ones, creating a sense of depth.

# Advanced CSS Animation Properties

The animations are fine-tuned with several CSS properties:

- `animation-timing-function: linear;` ensures the animation progresses at a constant speed.
- `animation-timeline: scroll();` ties the animation to the scroll position, making the animation progress as the user scrolls.
- `animation-fill-mode: both;` ensures the animation's styles are applied both before and after the animation's duration.
- `animation-range: 150vh 350vh;` specifies the scroll range over which the animation should play, ensuring the animations are tied to specific sections of the scroll.

 ## 4. Text Animation

Text within the third layer (`.top__text`) is animated to fade in as the user scrolls. This animation ensures that the text only becomes visible when the user scrolls to a certain point, enhancing the interactivity and visual engagement of the site.

## Visual Design and User Interaction

The combination of fixed positioning, varying animation speeds, and timed text reveals creates a visually striking and interactive experience. Users are drawn into the site through smooth, engaging animations that respond to their scrolling behavior. The arrows at the bottom further guide the user to interact with the page, encouraging exploration.

## Technical Implementation

To implement this design, careful attention is given to the stacking order of elements (`z-index`), the timing and scaling of animations, and ensuring cross-browser compatibility. The use of custom fonts from Google Fonts adds to the site's unique visual identity.



[yellowstonetour.webm](https://github.com/VitaliPri/Yellowstone/assets/101225909/194ba380-eb15-499f-b304-65bddf804e5a)
