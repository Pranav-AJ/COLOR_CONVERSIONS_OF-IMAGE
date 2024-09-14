# COLOR_CONVERSIONS_OF-IMAGE
## AIM
Write a Python program using OpenCV that performs the following tasks:

i) Read and Display an Image.

ii) Draw Shapes and Add Text.

iii) Image Color Conversion.

iv) Access and Manipulate Image Pixels.

v) Image Resizing

vi) Image Cropping

vii) Image Flipping

viii) Write and Save the Modified Image


## Software Required:
Anaconda - Python 3.7
## Algorithm:
### Step1:
Load an image from your local directory and display it.
### Step2:
o Draw a line from the top-left to the bottom-right of the image. o Draw a circle at the center of the image. o Draw a rectangle around a specific region of interest in the image. o Add the text "OpenCV Drawing" at the top-left corner of the image.
o Convert the image from RGB to HSV and display it. o Convert the image from RGB to GRAY and display it. o Convert the image from RGB to YCrCb and display it. o Convert the HSV image back to RGB and display it.
### Step4:
o Access and print the value of the pixel at coordinates (100, 100). o Modify the color of the pixel at (200, 200) to white.
### Step5:
o Resize the original image to half its size and display it.
### Step6:
o Crop a region of interest (ROI) from the image (e.g., a 100x100 pixel area starting at (50, 50)) and display it.
### Step7:
o Flip the original image horizontally and display it. o Flip the original image vertically and display it.
### Step8:
o Save the final modified image to your local directory.

## Program and Output:

### Developed By: A.J.PRANAV
### Register Number: 212222230107


## 1) Read and display the image
```
image = cv2.imread('tree.jpg')
image_resized = cv2.resize(image, (500,500))
plt.imshow(image_resized)
plt.show()
```

![image](https://github.com/user-attachments/assets/d8a50346-4e0b-4e74-9560-e832440e1347)

<br>
<br>

### 2)Draw Shapes and add text

### a)Draw line from top-left to the bottom-right

```
image1=image_resized.copy()
res = cv2.line(image1,(0,0),(500,500),(200,100,205),10)
cv2.imshow('Image Window', res)
cv2.waitKey(0)
cv2.destroyAllWindows()
```
![image](https://github.com/user-attachments/assets/3d1b91c2-ac96-4140-9c4c-98b0e325d632)

### b) Draw a circle at the centre of the image
```
image2=image_resized.copy()
res1=cv2.circle(image2,(250,225),150,(240,0,0),10)
cv2.imshow('Image Window', res1)
cv2.waitKey(0)
cv2.destroyAllWindows()
```

![image](https://github.com/user-attachments/assets/9ea5d117-6166-491c-8cdc-bf894f8f0329)




## Result:
Thus the images are read, displayed, and written ,and color conversion was performed successfully using the python program.







