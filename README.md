# color_detectio-of-Images-Using-KNN
Project at University of Haripur

# Abstract:
The main objective of this application is the methodology for identifying the shades of colors with an exact prediction with their names. A study says, a normal human can able to clearly identify nearly 1 million shades of colors. But human is able to see only 1% (i.e.10,000 colors) from the normal humans. While painting pictures, a painter needs to identify the color patterns exactly or else the reality of image is not clear.
# I.	INTRODUCTION:
Three different colors Red, Green and Blue are being tracked by utilizing the fundamentals of computer vision. After successful compilation when we execute the code a window redirects to the image displayed on it whose path is given as an argument.
Additionally, we obtain the color name of the pixel along with the composition of three different colors red, blue and green values. It is helpful in recognizing colors and in robotics. One of the applications of color detection by computer vision is in driver less cars. This system is useful in detecting traffic and vehicle backlights and takes decision to stop, start and continue driving. This also have much application in industry to pick and place different colored object by the robotic arm. Color detection is also used as a tool in various image editing and drawing apps.

# II.	 METHODOLOGY:
# 1.	Image Capture: 
The first step is to fetch a high-quality image with resolution. To load an image from a file we use.
2.	Extraction of RGB Colors: 
In this phase, the 3 layered colors are extracted from the input image. All the color images on screens such as televisions, computer, monitors, laptops and mobile screens are produced by the combination of Red, Green and Blue light. 
Index=[ "color", "color_name", "hex", "R", "G", "B"] 
3.	Calculate minimum distance from coordinates:
The minimum distance is calculated by considering moving towards the origin point from all colors to get the most matching color.
4.	Image Display with Shades of Color:

![image](https://user-images.githubusercontent.com/76808385/191727968-783a0054-0add-40a4-b729-f9107021cc8d.png)

The rectangle window is used to display the image with shades of color. After the double-click is triggered, the RGB values and color name is updated.
 
The above architecture shows the capability for the project. It consists of a well-defined sequence diagram that is abstracted from the source code. It leverages the rich capabilities of the technology such as OpenCv library in python.
# III.	RESULT:

![image](https://user-images.githubusercontent.com/76808385/191728009-4f3a1112-3b45-45de-bb5c-ea027a94a67d.png)
 
a.	Original input image of nature (b) Output image with Color intensity RGB values as R=49 G=52 B=21 for Olive Drop (c) Output image with Color intensity RGB values as R=18 G=88 B=186 for Sapphire
 
 ![Uploading image.png…]()

b.	Original input image of Salt Lake (b) Output image with Color intensity RGB values as R=3 G=9 B=97 for Royal Blue (c) Output image with Color intensity RGB values as R=252 G=229 B=13 for Golden Yellow
IV.	CONCLUSION:
In this project we defined to get the required color field from an RGB image. In this various steps are implemented using OpenCV platform. The main positive point of this method is its color differentiation of a mono color.
In the future scope, the detection of the edge detection techniques has different other applications like facial detection, color conversion for grey scale image etc. that can also be implemented.
