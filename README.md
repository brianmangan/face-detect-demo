# Face Detection Micro Service Demo

The [Visual Recognition][visual_recognition_service] Service uses deep learning algorithms to analyze images for scenes, objects, faces.

This demo builds deploys a  micro service in which a developer can POST an image to and recieve a confirmation if a face is detected in the image.  


Click the button below to fork into IBM DevOps Services and deploy your own copy of this application on Bluemix.

[![Deploy to Bluemix](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy?repository=https://github.com/brianmangan/face-detect-demo)

## Getting Started

1. You need a Bluemix account. If you don't have one, [sign up][sign_up]. Experimental Watson Services are free to use.
1. Click the 'Deploy to Bluemix' button above.


## Usage
1. After deploying to bluemix
2. POST to /api/facedetect 
3. an image via multipart/form-data, with element named 'sampleFile'
   1. example: face-detect-demo.mybluemix.net/api/facedetect
   
Response will be JSON formatted true/false.

 
