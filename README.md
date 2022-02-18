# Create-A-Watermark-On-Images-Using-OpenCV


Topics to be covered:
What is a Watermark?
Resizing images in OpenCV
Creating Watermark using an image
1. What is a Watermark?
A watermark is a logo, signature, text, or pattern that is intentionally superimposed onto different images and is used to protect the copyright of the images.

Its main purpose is to promote a brand and to make it more difficult to copy or use the original image without the owner’s permission.

Watermarks are often used by organizations, professionals to prevent others from using their content after hosting it online.

So, have you ever thought of adding a watermark to your images? Well, I did.

For example, we write blogs and mention the source of external images. But what about the images you create on your own? Wouldn’t it be nice to leave your imprint on them?

Yay! Let’s get started on this exciting task.

2. Resizing images in OpenCV
Resizing is nothing but scaling the image, which means changing the size of the original image. We can either increase or decrease the size of the image as per the business requirement.

Resizing can be done in several ways.

1. Preserve aspect ratio. The aspect ratio of an image is the ratio of its width to its height.

Shrink or upscale the size of the image
2. Not preserving the aspect ratio

Shrink/upscale width only, Shrink/upscale height only
3. Change both width and height to specific values

Sounds great till now, but how do we do it practically? The answer is OpenCV and its resize() function. Read more about the OpenCV resize function from this documentation.

Syntax of cv2.resize() function:
cv2.resize(src, dsize, interpolation)

src – source image
dsize – the desired size of the output image
interpolation – Wikipedia definition: It is a method of constructing (finding) new data points based on the range of a discrete set of known data points.
