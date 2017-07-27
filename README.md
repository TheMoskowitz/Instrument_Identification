# Instrument_Identification
A neural network for detecting the dominant instrument in recorded music

This repository holds several different approaches for identifying the dominant instrument. I used the IRMAS dataset and trained the best-performing model up to 50% accuracy (Note: That's not the same accuracy you would get from guessing as there are 11 different classes, so the starting random acccuracy would be ~9%).

The 1-D convolution method worked quite well and had I continued training it, I believe the accuracy could be trained up to the low 60s, which is currently the academic state of the art on this dataset.

I stopped early because I was only testing this network as part of my experiments with achieving Musical Style Transfer through transfer learning. Ultimately I decided that for Musical Style Transfer, this was the wrong approach. But as a standalone network this works relatively well for instrument identification.
