# Image to ASCII Art Using Pure Python

## 📌 Project Overview
This project converts a digital image into ASCII art using pure Python logic, without relying on external image-processing libraries. The goal is to understand how images are represented internally as pixel data and how they can be transformed into a text-based visual output.

## 🎯 Project Objectives
- Understand pixel-level image representation
- Convert RGB pixels to grayscale
- Normalize brightness for better contrast
- Map grayscale values to ASCII characters
- Generate ASCII art without using libraries

## ⚙️ How the Code Works
1. Reads a PPM (P3) image file
2. Stores pixel data as RGB tuples
3. Converts RGB values to grayscale
4. Normalizes brightness values
5. Maps grayscale intensity to ASCII characters
6. Writes the ASCII output to a text file

## ▶️ How to Run the Project
1. Select any image with a clear subject
2. Convert the image to **PPM (P3)** format
3. Rename the file as `face.ppm`
4. Place it in the project folder
5. Open terminal in the folder
6. Run:
   python ascii_art.py
7. Output will be saved in `ascii_output.txt`

## 📄 Output
The output is a text-based ASCII representation of the input image. For best results, view the output using a monospaced font.

## ⚠️ Limitations
- No face detection or background removal
- ASCII quality depends on the input image
- Large images may produce large output files

## 📚 Learning Outcomes
- Understanding pixel representation in images
- Grayscale conversion and contrast normalization
- ASCII mapping logic
- Importance of image processing libraries

## 👤 Author
Sudheer kumar valeti

## 🏁 Conclusion
This project demonstrates image-to-ASCII conversion using pure Python logic and provides a strong foundation for learning basic image processing concepts.
