<img src="https://github.com/hayakawa-domi/plankton_dataset/assets/129620031/4d8513b1-8adf-4008-81f1-1200ef0df4fc" width="60%" />

# Plankton_Dataset
Image cropping and dataset creation of individual plankton images using annotation data in CVAT(Computer Vision Annotation Tool).

# Preparation
1. Prepare annotated task data in cvat, such as the zip file in cvat_sample/x(40 or 100). (Select YOLO 1.1 in Export task dataset → Export format)
2. Prepare the following files covering the target tasks and target annotations.

・Task information file (cvat_taskinfo) that includes plankton collection locations, etc.

・Annotation name file (anno_name_list) containing labels for each classification class.

You need to add the data to the downloadable file on [Google Drive](https://drive.google.com/drive/folders/16x4IDIFmGJeLQr1QsCbYQzQU1KGDpJyC?usp=drive_link) or create your own file as necessary.  
3. Crop images and create anno_list can be performed by replacing the path written “PATH” in main.py with the appropriate one.
4. Please refer to the data_sample/x(40 or 100) for a sample of the data generated.


# Dataset
I will post the URL after the datapaper is published.
