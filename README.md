# Biscuit Detection using OpenCV

## Project Description
This project detects and classifies biscuits as Intact or Broken using image processing techniques.

## Features
- HSV color segmentation
- Contour detection
- Shape analysis
- Scoring-based classification
- Batch image processing

## Dataset
- 5 circular biscuit images (Marie)
- 5 square biscuit images (Cream Crackers)
- Images captured using mobile camera

## Methodology
1. Convert image to HSV
2. Apply color masking
3. Remove noise using morphology
4. Detect contours
5. Extract features
6. Classify using scoring system

## Output
- Green → Intact biscuit
- Red → Broken biscuit

Results are saved in output_images folder.

## Author
Avishka Yatiwella
