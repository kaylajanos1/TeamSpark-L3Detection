# TeamSpark-L3Detection
George Mason University: DAEN Capstone project Spring 2021

Code for Paper: L3 Slice Automated Detection Algorithm Improvement
Authors: Kayla Janos, Nizar Ajhar, Preethi Simha Akula, Reem Alhammad. 
Faculty Advisor: Dr. Issac Gang   
Project Sponsors: Allwyn

**Set Up Notes**
Please note that this project and the code within were established and tested in Google Colab. Users who wish to use this code, should establish a Google Drive location the contents of this project (keeping the folder structure). In addition to the files and folders located within this repository, users should create the following two empty directories on Google Drive in the same drive: 
- Data 
- NII_Data 

  
**Running the code**
If your data is in DICOM format:
  - Upload data to the Data folder 
  - Begin analysis with the Data Prep.ipynb & once that has processed move on to L3 Detection.ipynb 
 If your data is in NII.gz format:
  - Upload data to the NII_Data folder 
  - Begin Analysis with Data Prep.ipynb  

**Abstract**
This project seeks to automate the identification of the L3 vertebra from full-body CT scans. Using image-processing techniques, we will improve on existing open-source algorithms for L3 identification. The goal is to improve the confidence in identification results. The previous iteration of the detection algorithm flagged roughly 40% of output images for review. Our goal is to reduce the number of results required for review, thereby increasing confidence in the results. A large portion of the project’s efforts was focused on improving the code structure and usability, and our preliminary results show some improvement. 

