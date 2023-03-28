<h1 align="center" id="title">Apparel Detection Web App using YOLOv5</h1>

<p id="description">This web application uses the YOLOv5 deep learning model to detect apparel from an image uploaded by the user. The detected objects are then highlighted with bounding boxes and labeled with the predicted class.</p>

<h2>Project Screenshots:</h2>

<img src="https://github.com/AmitRanjan235/Yolov5_apparel_detection_webApp/blob/main/predicted%20image/predicted%20sample%20image.png" alt="project-screenshot" width="1024" height="624/">

<h2>🛠️ Installation Steps:</h2>

<<<<<<< HEAD
Copy code
pip install -r requirements.txt
Download the YOLOv5 model weights and place them in the yolov5webapp\Yolov5_apparel_detection_webApp\com_warehouse_apparel\predictor_yolo_detector\weights directory.
=======
<p>1. Requirements</p>
>>>>>>> 82f20d2ef24d38a9df1bf328b62dbd5d250d8211

```
To run this web application you need the following:  -f https://download.pytorch.org/whl/lts/1.8/torch_lts.html gdown Cython matplotlib>=3.2.2 numpy>=1.18.5 opencv-contrib-python==4.1.2.30 pillow PyYAML>=5.3 scipy>=1.4.1 tqdm>=4.41.0 flask-cors gunicorn torch==1.8.2+cpu torchvision==0.9.2+cpu
```

<p>2. Installation</p>

```
Clone this repository to your local machine:  bash Copy code git clone https://github.com/AmitRanjan235/Yolov5_apparel_detection_webApp.git Install the required Python packages using pip:  Copy code pip install -r requirements.txt Download the YOLOv5 model weights and place them in the yolov5webapp\Yolov5_apparel_detection_webApp\com_ineuron_apparel\predictor_yolo_detector\weights directory.
```

<p>3. Run the App</p>

<<<<<<< HEAD
clientApp.py: This file contains the Flask application code, including the routing and view functions.
yolov5webapp\Yolov5_apparel_detection_webApp\com_warehouse_apparel\predictor_yolo_detector\detector_test.py: This file contains the code for detecting apparel using the YOLOv5 model.
yolov5webapp\Yolov5_apparel_detection_webApp\templates\index.html: This file contains the HTML code for the web application interface.
=======
```
To run the web application run the following command:  Copy code python clientApp.py This will start the Flask development server on http://127.0.0.1:9500. You can then open this URL in your web browser to access the web application.
```
>>>>>>> 82f20d2ef24d38a9df1bf328b62dbd5d250d8211

<p>4. Use the App for Prediction</p>

```
To use the web application follow these steps:  Click the "Choose File" button to upload an image. Click the "predict" button to detect apparel in the uploaded image. View the detected apparel with bounding boxes and class labels.
```

<p>5. Customization</p>

```
You can customize this web application by modifying the following files:  clientApp.py: This file contains the Flask application code including the routing and view functions. yolov5webapp\Yolov5_apparel_detection_webApp\com_ineuron_apparel\predictor_yolo_detector\detector_test.py: This file contains the code for detecting apparel using the YOLOv5 model. yolov5webapp\Yolov5_apparel_detection_webApp\templates\index.html: This file contains the HTML code for the web application interface.
```

<h2>🍰 Contribution Guidelines:</h2>

This web application is based on the YOLOv5 object detection model developed by Amit Ranjan. The YOLOv5 model is released under the MIT license and more information can be found in the official YOLOv5 repository.

  
  
<h2>💻 Built with</h2>

Technologies used in the project:

*   Python: A high-level programming language used for building the web application and implementing the YOLOv5 object detection model.
*   PyTorch: A popular deep learning framework used for implementing the YOLOv5 object detection model.
*   Flask: A lightweight web framework used for building the web application and serving the YOLOv5 model predictions.
*   YOLOv5: A state-of-the-art object detection model used for detecting apparel in the uploaded images. It is implemented using PyTorch and trained on a large-scale dataset of images.

<h2>🛡️ License:</h2>

This project is licensed under the MIT License
