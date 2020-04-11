# Streaming Wait Screen

Simple bundling of [particles.js](https://vincentgarreau.com/particles.js/) for use as a wait screen via Twitch Browser Source.

## Building the image

Build the image with:

    $ docker build . -t streaming-wait:latest

## Using the image

Run the image with a simple port publish:

    $ docker run -p 5000:5000 streaming-wait:latest