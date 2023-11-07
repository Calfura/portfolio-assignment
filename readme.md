# Portfolio Assignment

## Overview

Create a mockup website designed for an potential employer to show off info, skills etc, about yourself.

## Components

Component parts to be used on each of the website pages. Will sort out styling and other pieces that are required to be used for displays.

### Header

```scss
@import "../defaults/colors";
@import "../defaults/breakpoints";

// Header main space allocation
header {
    display: flex;
    background-color: $primary-background;
    padding: 16px;
    height: 100px;

    // Setting the location of the name-bar and styling of the font
    .name-bar {
        background-color: $secondary-color;
        width: 400px;
        height: 50px;
        font-size: 36px;
        font-weight: bold;
        // font-family: ;
    }

}
```

### Footer

```scss
@import "../defaults/breakpoints";
@import "../defaults/colors";

// Creating footer styling base for pages
footer {
    background-color: $primary-background;
    align-items: center;

    // Links to Github and LinkedIn accounts
    .social-links {
        background-color: $primary-color;
        display: flex;
        width: 50%;
        justify-content: space-around;
        margin-bottom: 15px;
        margin-left: auto;
        margin-right: auto;
    }

    // Alignment for Contact link for bottem of pages
    .info {
        align-self: center;
        text-align: center;
        margin: 15px;
    }
}
```

## Defaults

Libary containing colour schemes and differing breakpoints for displays (ie. Desktop vesus phone displays) and when to use pre-defined settings.

### Breakpoints

### Colours

## Pages

Folder containing all the SCSS files for how each webpage is setup, what information is displayed, how each page is linked together, layouts.

## Images

Gives a directory for pages to grab images from and keeps it in an organized location away from other files (ease of read).

## Files

Downloadable content (ie. Resume). May use outside downloadable link in future.
