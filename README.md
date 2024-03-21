This script takes a video file (smile.mp4) as input, detects faces using a pre-trained Haar cascade classifier (faces.xml), and blurs the detected faces in real-time. It saves the modified video with blurred faces as blurred_smile.avi in the project folder.

Install OpenCV:

``pip install opencv-python``

Place the video file (smile.mp4) you want to process and a Haar cascade classifier file (faces.xml) in the project folder.

Run the script:

``python real_time_face_blurring.py``

The modified video with blurred faces will be saved as blurred_smile.avi in the project folder.
