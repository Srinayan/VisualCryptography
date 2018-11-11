# Visual Cryptography for Color Images
Visual cryptography, an emerging cryptography technology, uses the characteristics of human vision to decrypt the encrypted images. It does not require the knowledge of cryptography for decryption. For security concerns, it also ensures that hackers cannot perceive any clues about a secret image from individual cover images. Though it has been developed only for binary images, there have been many papers and research articles about its use in grayscale and colored images. Our report explores one such method where an image is color decomposed to Cyan, Magenta, Yellow colors and then the visual cryptography is carried out for the individual decomposition.

# Implementation
There are 4 files in this project
1.CMY_decomposition.py
2.halftone.py
3.main.py
4.output.py

The first py file is to decompose the given in image into three individual C,M,Y monotone images.
The second file converts the monotone images into its respective halftones.
The third file converts the halftone images into respective shares when overlapped should form the actual image.
output.py file merges the 3 shares formed in the main.py file

For theory refer : http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.457.5077&rep=rep1&type=pdf
