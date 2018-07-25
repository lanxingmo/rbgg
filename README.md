# rbgg

Isolate and remove the background gradient from images of paper.

![Example](https://i.imgur.com/UorlQ7X.png)

![Steps](https://i.imgur.com/HePbtgy.jpg)

### Motivation

One of my hobbies is using a pen plotter to make [computer-generated drawings](https://www.michaelfogleman.com/plotter/).
I often take pictures of these drawings to post online, but it's hard to get even, consistent lighting across the entire photo.
Instead of trying to perfect the lighting, I wrote this software to clean up the images for me.

### Installation

    $ go get -u github.com/fogleman/rbgg

### Usage

    $ rbgg input.jpg
