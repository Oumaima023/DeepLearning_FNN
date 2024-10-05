# DeepLearning_FNN

## Overview
This project involves the development of an application for diagnosing bone fractures of the pelvis and femur using a Feedforward Neural Network (FNN). The application aims to predict the presence of fractures based on various bone parameters.

## Dataset
The model is trained on a database collected from real hospitals, which includes a diverse set of patient records. This ensures a comprehensive representation of various conditions and treatments.

## Parameters Used
The following parameters are utilized in the application:
- **Age**
- **Area/Volume Fraction:**
  - BV (mm³)
  - TV (mm³)
  - BV/TV
- **Connectivity:**
  - Tb.ThMean (mm)
  - Tb.Th Std Dev (mm)
  - Tb.Th Max (mm)
  - Euler Characteristic (x)
  - Corr. Euler
  - Conn.D (mm³)
- **Thickness:**
  - Tb,Sp Mean (mm)
  - Tb.Sp Std Dev (mm)
  - Tb.Sp Max (mm)
- **Bone Mineral Density (BMD)**
- **DA**
- **Result:** 
  - 1: Fracture
  - 0: No Fracture

