# Image Segmentation using k-means 
Image segmentation is the process of dividing an image into groups in order to appropriately identify the pixels in a decision-making application. It separates a picture into a number of distinct sections with high similarity between pixels in each and high contrast between regions.

There are a variety of image segmentation methods, but clustering is one of the most efficient. It is a widely used technique in the machine learning field.

K-Means Clustering is an unsupervised learning technique

**First, make sure you have all of the required Python libraries loaded on your system**
After importing the needed libraries, you must read in the image as pixel values and get its size.we have to select K points at random from the image to initialize the centers.
Now we’ll use the k-means algorithm. We’ll start by looking for convergence. Calculate the distance between each pixel in the image and assign it to the corresponding centre (from which its distance is the shortest) to generate clusters.Lastly, compute new centers using the sample means of the pixel R, G, B values.
