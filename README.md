# Workshop-1 : Working on Images

## Instructions for submission
1. The image should be a plant, Tree, flower or building
2. The filename should be username.jpg
3. The image should be Converted to gray scale and HSV
4. Display the H, S and V planes

## Program
Developed by: ARSHATHA

Register Number: 212222230012

```py
import cv2
image=cv2.imread('rose.jpeg',1)
image=cv2.resize(image,(400,400))
cv2.imshow('ARSHA',image)
cv2.waitKey(0)
```
### The image should be Converted to gray scale
```py
import cv2
image = cv2.imread('rose.jpeg')
gray = cv2. cvtColor(image, cv2.COLOR_BGR2GRAY)
cv2. imshow('ARSHA', gray)
cv2. waitKey(0)
cv2. destroyAllWindows()
```
### The image should be Converted to HSV
```py
import cv2
image = cv2.imread('rose.jpeg')
gray = cv2. cvtColor(image, cv2.COLOR_BGR2HSV)
cv2. imshow('ARSHA', gray)
cv2. waitKey(0)
cv2. destroyAllWindows()
```
### Display the H, S and V planes
```py
import cv2
image=cv2.imread("rose.jpeg",1)
image= cv2.resize(image,(400,250))
image=cv2.cvtColor(image,cv2.COLOR_RGB2HSV)
H,S,V=cv2.split(image)
cv2.imshow('Hue',H)
cv2.imshow('Saturation',S)
cv2.imshow('Value',V)
```

## Output
### Image
![01](https://github.com/arshatha-palanivel/Workshop/assets/118682484/1cd19271-434d-4f1c-9afb-d06d2abf7869)

### The image should be Converted to gray scale
![02](https://github.com/arshatha-palanivel/Workshop/assets/118682484/d733e2e8-31fa-4aed-9a62-9b80972ea6f8)

### The image should be Converted to HSV
![03](https://github.com/arshatha-palanivel/Workshop/assets/118682484/c82d94da-ccd1-410f-8a51-1d2e26ec10ee)

### Display the H, S and V planes
![04](https://github.com/arshatha-palanivel/Workshop/assets/118682484/4dba9035-86b3-4a4d-93e4-f4b2e12081c7)





## Result
Thus Working on Images has been performed successfully!!
