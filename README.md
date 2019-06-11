## Dance Skeleton

This repository has been forked from [here](https://github.com/llSourcell/InMyFeelings_Challenge).It has been modified to create pose estimation skeleton from video stored on the desktop.</br>
webM pose detection skelton video can be downloaded.</br>
It uses captureStream method and MediaStream Recording API to capture canvas and record media.</br>

## Demo
![Alt Text](https://github.com/neha01/danceSkeleton/blob/master/skeletal.gif)

## Steps
[Youtube video Tutorial](https://youtu.be/nGal-zhsyEc)
1. Clone the repository </br>
2. Place the video for which you want to create dance Skeleton in same directory</br>
3. Navigate to that folder on commandline and run "python -m http.server 1337" to create local server on port 1337 on your machine</br>
4. Navigate to "localhost:1337/index.html"  on browser. </br>
5. Play the video to start the recording and pause the video to stop the recording.



## Coding Challenge - Due Date, August 1 2018 at 12 PM PST

This is the code for this [this](https://youtu.be/prswDGGmYaE) video on Youtube by Siraj Raval as part of the #InMyFeelingsChallenge dance competition. The challenge is to create your own AI to dance to this song and submit it via Twitter, Facebook, Youtube, Instagram, or LinkedIn (or all of them) using the #InMyFeelingsChallenge hashtag. There are 3 methods to do this

### Method 1 (Hacky way)

1. Run the real-time pose detection model in your browser.
2. Hold up your phone or another screen to the webcam, while a video of a human dancing plays.
3. Record your screen while the real-time pose estimate follows the human dance.
4. In Final Cut Pro, or a video editing program of your choice, apply a color mask so all colors except the color of the pose estimate model are made not visible.
5. Export the video and upload!

### Method 2 (Cleaner programmatic way)

1. Modify the code in this repository so instead of the demo applying pose estimation to webcam video, it applies it to a video on your desktop, records, and saves it.
2. Use a javascript library like [chroma.js](https://github.com/gka/chroma.js/) to apply a color mask programmatically to the video, making all colors except for the pose estimate model color not visible.
3. Upload the final result!

### Method 3 (For the realest Wizards)

1. Train an LSTM Neural network on a dataset of Shiggy dance videos similar to what [carykh](https://www.youtube.com/watch?v=Sc7RiNgHHaE&t=273s) did for trancey dance videos.
2. Upload the result!

### Rewards
I'll definitely give a social media shoutout to some of the best submissions! Good luck Wizards, lets light up this challenge and show the world what AI can do.


Run real-time pose estimation in the browser using TensorFlow.js.

[Try it here!](https://montrealai.github.io/posenet-v3/)

<img src="https://raw.githubusercontent.com/irealva/tfjs-models/master/posenet/demos/camera.gif" alt="cameraDemo" style="width: 600px;"/>

PoseNet can be used to estimate either a single pose or multiple poses, meaning there is a version of the algorithm that can detect only one person in an image/video and one version that can detect multiple persons in an image/video.

This is a Pure Javascript implementation of [PoseNet](https://github.com/tensorflow/tfjs-models/tree/master/posenet). Thank you [TensorFlow.js](https://js.tensorflow.org) for your flexible and intuitive APIs.

[Refer to this blog post](https://medium.com/tensorflow/real-time-human-pose-estimation-in-the-browser-with-tensorflow-js-7dd0bc881cd5) for a high-level description of PoseNet running on Tensorflow.js.

## Credits

Credits for this code go to the Tensorflow team at Google
