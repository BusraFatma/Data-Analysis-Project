**FOR VISUAL ANALYSIS;**

*Tools to be used:*

- PLC: To control the production line and sensors (including cameras).
- Optical Cameras: To take images of products or the production process.
- Python and OpenCV: To process and analyse images.
  

*System Components and Functions:*

**1- Optical Cameras:** 

**2-Image Processing Software (Python/OpenCV):** Processes incoming images, checks that products are the correct size and shape, detects colour errors or other visual defects.

**3-PLC:** Using the information from the cameras and image processing software, it controls the machines on the production line, rejects faulty products and stops or changes the settings of the production line when necessary.


**Visual Capture:**

- Cameras capture images of products at set intervals or continuously.
  
**Visual Processing:**

- Images are analysed according to certain criteria (e.g. size, shape, colour, etc.).
  
- Quality control tests are performed for each product using Python and OpenCV.
  
- Signals are generated for defective products.

**PLC Control:**

- The PLC acts according to the signals from the image processing software.
  
- It activates separator mechanisms to separate defective products.
  
- If necessary, it adjusts or stops the speed of the production line.
  
**Reporting and Monitoring:**

- The system logs production data and quality control results.
  
- It generates reports on production efficiency and quality level.

**FOR SOUND ANALYSIS;**
