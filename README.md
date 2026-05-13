# image-transformations-using-opencv
## Aim
To develop a Python program using OpenCV to perform various geometric transformations on an image.

The project includes the following image processing operations:

- Image Translation
- Image Scaling (Resizing)
- Image Shearing
- Image Reflection (Flipping)
- Image Rotation

---

## Software Requirements

- Python 3.7
- Anaconda Distribution
- Jupyter Notebook / VS Code

### Python Libraries Used
- OpenCV (`cv2`)
- NumPy
- Matplotlib

---

## Algorithm

### Step 1: Import Required Libraries
Import OpenCV, NumPy, and Matplotlib libraries.

### Step 2: Read the Input Image
Load the input image in color mode using OpenCV.

---

## Image Translation

- Create a translation matrix.
- Shift the image:
  - 50 pixels towards the right
  - 80 pixels downward
- Apply the transformation using `cv2.warpAffine()`.
- Display both original and translated images.

---

## Image Scaling

- Resize the image to:
  - `0.5×` (downscaling)
  - `2×` (upscaling)
- Use `cv2.resize()` for resizing.
- Display the original, downscaled, and upscaled images.

---

## Image Shearing

Create transformation matrices for:

- Horizontal Shearing
- Vertical Shearing

Apply transformations using `cv2.warpAffine()` and display the results.

---

## Image Reflection

Perform image flipping using `cv2.flip()`:

- Horizontal Reflection
- Vertical Reflection
- Reflection across both axes

Display all reflected images.

---

## Image Rotation

Create rotation matrices for:

- `45°` Rotation
- `90°` Rotation

Use:
- `cv2.getRotationMatrix2D()`
- `cv2.warpAffine()`

Display the original and rotated images.


### Image Translation
- Original image displayed
- Translated image displayed

### Image Scaling
- Original image displayed
- Downscaled image displayed
- Upscaled image displayed

### Image Shearing
- Original image displayed
- Horizontally sheared image displayed
- Vertically sheared image displayed

### Image Reflection
- Original image displayed
- Horizontally flipped image displayed
- Vertically flipped image displayed
- Both-axis flipped image displayed

### Image Rotation
- Original image displayed
- 45° rotated image displayed
- 90° rotated image displayed

---

## Result

Thus, various geometric transformations such as translation, scaling, shearing, reflection, and rotation were successfully implemented using OpenCV. These operations demonstrate how images can be spatially manipulated for different computer vision and image processing applications.
