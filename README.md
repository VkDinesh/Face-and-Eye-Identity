# automated-attendance-system-using-computer-vision

# What dataset are we using?
'sourceimg.jpeg' is the [Bill Gate](https://www.google.com/url?sa=i&source=images&cd=&ved=2ahUKEwiypdCsqt7iAhXLKY8KHZoEA74QjRx6BAgBEAU&url=http%3A%2F%2Ftime.com%2F5341036%2Fbill-gates-alzheimers-disease-research%2F&psig=AOvVaw1CeuLo5ELn5kn1nJ1ycWSj&ust=1560236036277953) image from Time website , we will be using this image for our future face identity.

# What are the libraries we are using?
We’ll be using the below libraries in this section:

OpenCV: For detecting faces and eyes by the inbuilt eye and face cascade classifiers.
Matplotlib: For reading and plotting both the images.
NumPy:  “Complementary” – an all-time classic library!

# What are the variables used in this code?
we use Face and Eye cascade Classifiers to get the coordinates of top and bottom corners of both the face and eyes respectively. Those coordinates/points are stored in variables:

# ‘x‘, ‘y‘, ‘w‘, ‘h‘ (for face cascade)
# ‘ew‘, ‘ey‘, ‘ex‘, ‘eh‘ (for eye cascade)

