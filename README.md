# Traci Demo

The goal is for a mobile device to be able to show a movie when it sees an image.

We actually want to be able to have 3 or 4 images be recognized.

## User Flow

1. In general -> there will be some kind of collection of photos say in an art gallery, or in a collage, and a visitor will pull out their phone and point it at the image, and then it will play a movie.

2. In more detail -> the patron will probably need to either put their phone in camera mode, or visit a special web page that will put their phone in camera mode.

3. There is a way to exit the movie also to continue scanning.

## Approach

There are many ways we can try do this. Today circa 2021 it does look like there are easier ways to do this than before. This tool seems to do it:

https://ar-js-org.github.io/AR.js-Docs/image-tracking/

'The software tracks interesting points in the image and using them, it estimates the position of the camera. These interesting points (aka "Image Descriptors") are created using the NFT Marker Creator, a tool available for creating NFT markers.'  - see https://carnaux.github.io/NFT-Marker-Creator/#/

