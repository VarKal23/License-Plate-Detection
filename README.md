# License Plate Detection
A License Plate Detection model that identifies license plates and scans them for image to text conversion for security use cases. Uses Python, Tensorflow, OpenCV, Jupyter Notebook, EasyOCR.

## Steps to use

### Step 1. Clone this repository

### Step 2. Create a new virtual environment
python -m venv lpdsys

### Step 3. Activate virtual environment
.\lpdsys\Scripts\activate

### Step 4. Install dependencies and add virtual environment to the Python Kernel
python -m pip install --upgrade pip <br>
pip install ipykernel <br>
python -m ipykernel install --user --name=lpdsys

### Step 5. Collect images and annotations through the following Kaggle Dataset
https://www.kaggle.com/datasets/andrewmvd/car-plate-detection

### Step 6. Manually divide collected images into two folders train and test
\License-Plate-Detection\Tensorflow\workspace\images\train <br>
\License-Plate-Detection\Tensorflow\workspace\images\test <br>

### Step 7. Begin training process by opening 2. LicensePlateDetection.ipynb, this notebook will walk you through installing Tensorflow Object Detection, and making detections

### Step 8. During this process the Notebook will install Tensorflow Object Detection

### Step 9. Once you get to step 6. Train the model inside of the notebook or in terminal for live loss metrics

### Step 10. You snould now be able to identify license plates, and step through the other Jupyter Notebook steps for image to text conversion through EasyOCR
