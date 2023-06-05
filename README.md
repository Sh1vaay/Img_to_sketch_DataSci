# DataScience_image_to_sketch
1 Load the image into Python using the cv2.imread() function. This reads the image from a file and stores it in a NumPy array.
2 convert the image to grayscale using the cv2.cvtColor() function. This removes all the color information from the image and leaves us with just the brightness values.
3 Use the cv2.GaussianBlur() function to smooth out any noise or details in the image. This helps to create a cleaner sketch effect.
4 After smoothing the image, use the cv2.divide() function to divide the grayscale image by the smoothed image. This creates a high-contrast version of the image that looks like a sketch.
Finally, use the cv2.imwrite() function to save the sketch to a file. And that's it! With just a few lines of code, You can turn any photo into a sketch using Python and cv2.
