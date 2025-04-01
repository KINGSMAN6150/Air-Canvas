# Air-Canvas
Here's a refined version of your text with improved clarity and structure:  

---

# Air Canvas Project  
**Computer Vision Project Using OpenCV**  

Have you ever wanted to draw in the air using just your finger? This project lets you do exactly that! The **Air Canvas** allows you to create digital drawings by tracking the movement of a **colored marker** using a camera.  

## Overview  
By leveraging **computer vision techniques** in OpenCV, we can detect and track a colored object (such as a marker placed on the fingertip) to draw on a virtual canvas. **Python** is the preferred language for this project due to its extensive libraries and ease of use, but the core concept can be implemented in any OpenCV-supported language.  

### Key Techniques  
We utilize **color detection and tracking** to achieve marker-based drawing. A mask is generated to isolate the marker's color, followed by **morphological operations** such as **erosion** (to remove noise) and **dilation** (to restore the refined mask).  

## Algorithm  
1. Capture video frames and convert them to **HSV color space** for easier color detection.  
2. Initialize a **canvas** frame and overlay drawing buttons.  
3. Adjust **trackbar values** to accurately detect the marker color.  
4. Apply **morphological operations** (erosion and dilation) to refine the mask.  
5. Identify **contours** in the mask, find the **largest contour’s center**, and store its coordinates in an array for continuous tracking.  
6. Draw the stored points on both the frame and the canvas.  

## Requirements  
- **Python 3**  
- **NumPy**  
- **OpenCV**  

This project is a great way to explore **computer vision** and interactive drawing using OpenCV. 🚀
