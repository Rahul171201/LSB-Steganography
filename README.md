# What is Steganography?
Steganography is the process of hiding a secret message within a larger one in such a way that someone can not know the presence or contents of the hidden message. The purpose of Steganography is to maintain secret communication between two parties. Unlike cryptography, which conceals the contents of a secret message, steganography conceals the very fact that a message is communicated. 

<img src="https://user-images.githubusercontent.com/70642284/197933153-803ee456-191e-4709-9860-8ffef8468a7c.jpg" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="300" height="200" />

# Least Significant Bit (LSB) Steganography
We can describe a digital image as a finite set of digital values, called pixels. Pixels are the smallest individual element of an image, holding values that represent the brightness of a given color at any specific point. So we can think of an image as a matrix (or a two-dimensional array) of pixels which contains a fixed number of rows and columns. Least Significant Bit (LSB) is a technique in which the last bit of each pixel is modified and replaced with the secret message’s data bit.

<img src="https://user-images.githubusercontent.com/70642284/197933170-27a3b4f8-a217-4328-899a-9c7ba8306c9d.jpg" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="600" height="250" />

<img src="https://user-images.githubusercontent.com/70642284/197933178-ae713347-56b8-4db4-9a77-d1692cb729f1.jpg" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="600" height="250" />

From the above image it is clear that, if we change MSB it will have a larger impact on the final value but if we change the LSB the impact on the final value is minimal, thus we use least significant bit steganography.

# Results
A number of images have been used for testing against our LSB steganography. It has been observed that jpeg images prone to data loss. Hence it ois recommended to use png images. 

## Original Image
<img src="https://user-images.githubusercontent.com/70642284/197934931-35dd9fcc-486b-48c9-ab03-23d7ed864ee0.png" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="400" height="400" />

## Secret Message
"Steganography is a great art!"

## Encrypted Image
<img src="https://user-images.githubusercontent.com/70642284/197935091-392d1159-6a6b-475c-86e3-e661dd74f231.png" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="400" height="400" />

## Output
<img src="https://user-images.githubusercontent.com/70642284/197935145-76566ffb-4b15-4856-910e-12f71fae430a.jpeg" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="600" height="400" />

# References
* https://towardsdatascience.com/hiding-data-in-an-image-image-steganography-using-python-e491b68b1372
* https://towardsdatascience.com/steganography-hiding-an-image-inside-another-77ca66b2acb1
* https://www.edureka.co/blog/steganography-tutorial
* https://www.forbes.com/sites/bernardmarr/2018/05/21/how-much-data-do-we-create-every-day-the-mind-blowing-stats-everyone-should-read/#191d0b0160ba
* https://www.ukessays.com/essays/computer-science/steganography-uses-methods-tools-3250.php
* https://www.thepythoncode.com/article/hide-secret-data-in-images-using-steganography-python
* https://www.youtube.com/watch?v=xepNoHgNj0w&t=1922s

# 
