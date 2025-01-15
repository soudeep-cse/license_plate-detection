# License Plate Detection and Vehicle Type Identification  

This project focuses on detecting license plates and identifying vehicle types (e.g., bus, car, motorbike). The system is capable of real-time detection and includes a web-based application for managing the detected license plate data.  

## Key Features  
- **License Plate Detection**  
  - Real-time detection using YOLOv8.  
  - Identification of vehicle types such as buses, cars, and motorbikes.  
- **Data Management**  
  - Storage and retrieval of detected license plate information via a web application.  

## Workflow  

### 1. Data Preparation  
- Combined multiple datasets for better coverage (License plate, VisDrone & COCO dataset).  
- Applied data augmentation techniques to improve model performance and generalization.  

### 2. Model Development  
- Trained YOLOv8 on the prepared dataset for license plate and vehicle type detection.  
- Integrated OpenCV for live detection functionality.  

### 3. Web Application Development  
- **Frontend**:  
  - Built using HTML, CSS, and JavaScript for an intuitive and user-friendly interface.  
- **Backend**:  
  - Developed using FastAPI for handling API requests and backend logic.  
- **Database**:  
  - SQL was used for storing and managing license plate numbers and related information.  

## Collaboration  
This project was a confidential client assignment completed in collaboration with another team member who provided additional support.  
