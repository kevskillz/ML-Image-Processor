# ML Image Processor
Given a set images, point out where objects are in a few images and let ML handle the rest! 


# Features
- Mass Image/Video Input
- UI for mapping out few initial points
- Scaling to convert pixels->another unit (useful for distances)
- Multi-object differentiation
- Numerous data variables to record (distance, position, variance, number of objects, etc.)
- Outlier alerts, data visualization, time lapse creation
- Variety in data output


# Audience/Accessibility
- Useful in a lab setting given lots of images. Burdening to track out point/distance between two objects at every frame.
- Adaptable to your given inputs! Distuingish between objects, see outliers, etc. without spending hours going through every image/video!


# Why I created this?
- During my time in a lab at program called TRIP, I had to find the distance between flies given a set of hundreds of images with various scales, each with 5 flies each. This amounts to (5 2) = 10 pairs * ~150 images = 1500 distance calculations! Using Fiji, I had to draw out and record the distance of each one of these pairs by hand, as there was no function to get distances between all pairs! I want to solve this problem others throughout the scientific community may have and also add ML to reduce the number of images I have to go through drastically, just providing a few points to assist in the object detection.


# Next steps
- Fiji/ImageJ Integration
- More data variables
