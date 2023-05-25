# Body-Shape-Silhouette-Biometric
This repository was in partial fulfillment of my MSc Degree. The jupyter notebook contains code that converts an RGB image into a binary image. This binary image contains then contains a silhouette which is used to extract statistical features used to identify the person.

Take an image, for example

![test_colour](https://github.com/jspooons/Body-Shape-Silhouette-Biometric/assets/25199093/2e501ea6-05b9-4a0d-9a47-92c7ae6e9cbd)

Get its silhouette

![person_binary_thresh](https://github.com/jspooons/Body-Shape-Silhouette-Biometric/assets/25199093/b24bff8b-04d6-4c1b-ae0b-845bc2d8555d)

Calculate center of the silhouette

![person_contour_center](https://github.com/jspooons/Body-Shape-Silhouette-Biometric/assets/25199093/9dcd31bd-3baf-45cf-a74c-84f0c42e9b81)

Unwraps the silhouette using the central point and uses this as a predictor (notice this is statistical data for a front-on profile)

![person_front_contour_unwrap](https://github.com/jspooons/Body-Shape-Silhouette-Biometric/assets/25199093/a8009873-6fb0-4fa6-bd7b-d459f8530ba6)

This is an unwrapped solhouette for a side-on profile

![person_side_contour_unwrap](https://github.com/jspooons/Body-Shape-Silhouette-Biometric/assets/25199093/b1c38379-5af3-4516-b1ae-9ff9ce301c81)
