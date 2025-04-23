
## gganimate: How to Create Plots with Beautiful Animation in R

This document describes how to create animation in R using the
"gganimate" R package.

gganimate is an extension of the ggplot2 package for creating animated
ggplots. It provides a range of new functionality that can be added to
the plot object in order to customize how it should change with time.

## Key features of gganimate:

-   transition\_\*(): defines how the data should be spread out and how
    it relates to itself across time.

-   view(): defines how the positional scales should change along the
    animation.

-   shadow\_\*(): defines how data from other points in time should be
    presented in the given point in time.

-   enter/exit\_\*(): defines how new data should appear and how old
    data should disappear during the course of the animation.

-   ease_aes(): defines how different aesthetics should be eased during
    transitions.

## Prerequisites

gganimate stable version is available on CRAN and can be installed with
install.packages('gganimate'). The latest development version can be
installed as follow:
