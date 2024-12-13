# R-Peak Detection within Electrocardiogram (ECG) Signal
This project implements a Python-based solution to detect R-peaks within ECG signals extracted from Transthoracic Echocardiogram (TTE) video frames. By combining signal processing techniques with cardiac phase alignment, the project aims to enable more accurate analysis of multi-view echocardiography data.

### Key Features
##### ECG Signal Extraction:
Extracted the 1D signal vector from pixel values corresponding to the ECG trace embedded in TTE video frames.

##### R-Peak Detection:
Implemented algorithms to identify R-peaks within the extracted ECG signal, facilitating the segmentation and analysis of cardiac cycles.

![image](https://github.com/user-attachments/assets/a04e2102-e144-44b4-89ca-84e68fc88922)

![image](https://github.com/user-attachments/assets/a19a4e6c-b41a-4743-b7ee-e0e8fb929c71)
This shows signals with challenging segmentations. 

##### Multi-View Alignment:
Aligned cardiac phases across standard echocardiographic views, including Parasternal Long-Axis (PLAX) and Parasternal Short-Axis (PSAX), to ensure consistent temporal representation.

### Applications
Preprocessing for echocardiographic analysis pipelines.
Enhancing synchronization in multi-view echocardiography datasets.
Supporting research in automated heart disease detection using aligned cardiac cycles.

![image](https://github.com/user-attachments/assets/a0f5325f-c964-4396-82c1-488b26ff9c3f)



### Technologies and Tools
Programming Language: Python

Libraries: NumPy, SciPy, Matplotlib, and signal processing modules

Data Source: Extracted from TTE videos with embedded ECG traces.
