#Apparel Detection Web App using YOLOv5
**This web application uses the YOLOv5 deep learning model to detect apparel from an image uploaded by the user. The detected objects are then highlighted with bounding boxes and labeled with the predicted class.**

*Requirements
To run this web application, you need the following:

-f https://download.pytorch.org/whl/lts/1.8/torch_lts.html
gdown
Cython
matplotlib>=3.2.2
numpy>=1.18.5
opencv-contrib-python==4.1.2.30
pillow
PyYAML>=5.3
scipy>=1.4.1
tqdm>=4.41.0
flask-cors
gunicorn
torch==1.8.2+cpu
torchvision==0.9.2+cpu*

YOLOv5 model weights (available here)
Installation
Clone this repository to your local machine:

bash
Copy code
git clone https://github.com/AmitRanjan235/Yolov5_apparel_detection_webApp.git
Install the required Python packages using pip:

Copy code
pip install -r requirements.txt
Download the YOLOv5 model weights and place them in the yolov5webapp\Yolov5_apparel_detection_webApp\com_ineuron_apparel\predictor_yolo_detector\weights directory.

Usage
To run the web application, run the following command:

Copy code
python clientApp.py
This will start the Flask development server on http://127.0.0.1:9500. You can then open this URL in your web browser to access the web application.

To use the web application, follow these steps:

Click the "Choose File" button to upload an image.
Click the "predict" button to detect apparel in the uploaded image.
View the detected apparel with bounding boxes and class labels.
Customization
You can customize this web application by modifying the following files:

clientApp.py: This file contains the Flask application code, including the routing and view functions.
yolov5webapp\Yolov5_apparel_detection_webApp\com_ineuron_apparel\predictor_yolo_detector\detector_test.py: This file contains the code for detecting apparel using the YOLOv5 model.
yolov5webapp\Yolov5_apparel_detection_webApp\templates\index.html: This file contains the HTML code for the web application interface.

This web application is based on the YOLOv5 object detection model developed by Amit Ranjan. The YOLOv5 model is released under the MIT license, and more information can be found in the official YOLOv5 repository.

