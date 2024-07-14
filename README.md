# computer_vision
# canny_edge_detector
In this section, I implemented the Canny edge detector. The Canny edge detection algorithm can be broken down into five steps, and I wrote code for each one:
1. Smoothing
2. Finding gradients
3. Non-maximum suppression
4. Double thresholding
5. Edge tracking by hysteresis
# morphological_knowledge
In this section, without using the built-in library functions and by applying morphological knowledge, I extracted the skeletons of the images. Then, by saving the steps of skeleton extraction, I reconstructed the original images from the skeletons.
# SAM
The SAM (Segment Anything Model) is a model for image segmentation that produces high-quality masks of objects within an image. It is used for various segmentation applications. In the SAM notebook, you can see examples of the masks generated for an image.
# classified_images
In this section, I classified images of various handwritten digits from the MNIST dataset using shape descriptors (Hu moments) and a machine learning model.
# enhancement_methods
In this section, I examined different image enhancement methods:
1. Histogram equalization
2. The first and second method for ACE
3. CLAHE (not using opencv)
4. CLAHE (using opencv)
# salt-and-pepper_noise
In this section, I first added salt-and-pepper noise to the input image. Then, I tried to remove the noise using three filters:
1. Averaging Blurring
2. Median Blurring
3. Gaussian Blurring
