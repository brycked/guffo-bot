Outputs a vector with the same direction as the input vector, but a length of 1. (Also known as a *unit vector*.)

[[uploads/Normalize.png]]

In the olden days you had to script vector normalization yourself, which would look something like this:

[[uploads/screenshot1.png]]

# Buggy effect
[[Blocks/Vector]] 0,0,0 is where the 2 arrows start. This script can give nan,nan,nan when all of the vector components are 0.