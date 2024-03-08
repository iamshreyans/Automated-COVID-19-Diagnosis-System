# Automated-COVID-19-Diagnosis-System
The purpose of this project is classification of the novel Coronavirus from C-XR and Computed Tomography scan images. A modern deep learning approach will be used to build the models i.e., Convolutional neural networks or CovNet including ResNet 152 v2, Xception, InceptionResNet v2, ResNet 50, Inception v3, NASNetLarge, DenseNet 201, and VGG 16 for the classification of the images to detect whether the patient is corona positive or not. The models will be trained by considering the factors such as FP and FN. 
The proposed models will be trained using the dataset containing the C-XR and Computed Tomography-scan images of both covid and non-covid patients. Also, the comparative analysis of all the proposed models will be performed to determine the best approach using various metrics. And for better visualization of results and diagnosis of covid-19 taking C-XR or Computed Tomography-scan images as input to our web application will be built using the above-mentioned models.


# USAGE
1. Install the requirements for the project, run: pip install -r requirements.txt
2. Download the Data folder from https://drive.google.com/drive/folders/1_5U6Qd7rhMYDo_HX_X21SIa2_d_XEH1t?usp=drive_link
3. Copy the downloaded Data folder inside cloned repo.
4. Download the Models folder from https://drive.google.com/drive/folders/1hOp_rMnxuFYIk5P4zVq_UYGfuDeCd77N?usp=sharing
5. Similarly copy the downloaded Models folder inside cloned repo
6. [optional] If you want to re-configure the models or re-trained the models, run .ipynb files present inside the Jupyter notebooks folder
7. To run the project run python app.py command
8. Open the link: http://127.0.0.1:5000/  in your browser to access the web application.

