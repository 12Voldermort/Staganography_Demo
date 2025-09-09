Steganography Tool - by code bites
A simple and educational Java Swing application to demonstrate the basic principles of steganography, where text data is hidden inside an image file. This project is ideal for students and beginners learning about data hiding, image processing, and Java GUI development.

Features
Hide Data: Embed a text message within a .png image file using the Least Significant Bit (LSB) method.

Retrieve Data: Extract the hidden text message from a steganographically modified image.

Graphical User Interface (GUI): A user-friendly interface built with Java Swing for easy interaction.

Portable: The application can be packaged as a single executable .jar file for easy use on any computer with Java installed.

How to Run the Application
Method 1: Using the Executable .jar File (Easiest)
Download the .jar file: Go to the Releases section of this repository and download the latest steganography-tool.jar file.

Run the file: Double-click the .jar file. The application window should open.

Note: Make sure you have the Java Runtime Environment (JRE) installed on your computer.

Method 2: Running with an IDE (for Developers)
Clone the repository: Use the following command to clone the project to your local machine:

Bash

git clone https://github.com/your-username/your-repo-name.git
Open in NetBeans: Open the cloned project in NetBeans (or your preferred Java IDE).

Run the Project: Right-click the project folder in NetBeans and select Run.

How to Use the Application
Load an Image: Click the Load Image button to select a .png image from your computer. The image will appear in the left-hand panel.

Enter Your Message: Type the secret message you want to hide into the text field.

Hide the Data: Click the Hide Data button. A file save dialog will appear, prompting you to save the new image with the hidden data. Choose a name and location.

Retrieve the Data: To retrieve the message, click the Retrieve Data button. Select the image you just created. The hidden message will be displayed in the text area.

Why LSB and .png?
This application uses the Least Significant Bit (LSB) method, which is one of the simplest steganography techniques. It works by replacing the last bit of a pixel's color value with a bit of the hidden data. Since this change is very small, it's virtually undetectable to the human eye.

We use .png images because they use a lossless compression format. This means the pixel data is not altered when the image is saved, ensuring our hidden data remains intact. In contrast, .jpg images use "lossy" compression, which would corrupt the hidden data.

Contribution
If you'd like to improve this project, feel free to open a pull request! Your contributions are welcome.

Created by
This project was created by the code bites channel to help aspiring young developers and students explore the fascinating world of computer science.
