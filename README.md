# Real_Time_TrafficSignal_Detection
Overview:
A CNN-based project to classify speed limit signs (20, 30, 50, 60, 70 km/h) from the GTSRB dataset and detect them in real-time videos using TensorFlow/Keras and OpenCV.


Dataset:
GTSRB (German Traffic Sign Recognition Benchmark), filtered to 5 speed limit classes (Speed Limit 20, 30, 50, 60, 70 km/h).

Results:
Achieved ~90% validation accuracy during training.Successfully detected signs in videos, e.g., "Speed Limit 50" with high confidence (see demo video below).

Demo:
Watch the demo video
Note: Replace the above link with the actual Google Drive shareable link to output_new.mp4 after uploading it.

How to Run
Install Dependencies:
!pip install tensorflow opencv-python numpy pandas matplotlib sklearn

Upload the Dataset:
Download the GTSRB dataset (gtsrb-german-traffic-sign.zip) and upload it to Colab.Or use the dataset already in the notebook if provided.

Run the Notebook:
Open
Traffic_Sign_Detection.ipynb in Google Colab and run the cells sequentially.

Real-Time Detection:
Upload your own video for real-time detection (or use the provided sample video).The notebook will process the video and download the output with predictions overlaid.

Optional:
Download the trained model to skip training: traffic_sign_model.h5

Project Structure
Traffic_Sign_Detection.ipynb:
The main notebook with all code (data preprocessing, model training, evaluation, real-time detection).
traffic_sign_model.h5:
The trained CNN model.

output_new.mp4:
Sample output video with predictions (e.g., "Speed Limit 50").

Future Work:
Record a personal video while running to detect speed limit signs in real-world scenarios.Expand the model to detect more traffic sign classes from the GTSRB dataset.Explore calculating actual running speed using GPS or computer vision techniques.

Acknowledgments:
Built using Google Colab, TensorFlow/Keras, and OpenCV.
Thanks to the GTSRB dataset creators for providing the data.
