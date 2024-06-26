# Sleep-Detection
Sleep detection is a project built using Dlib and OpenCV with Python as a backend language.

## Logic of project
The project includes direct working with the 68 facial landmark detector and also the face detector of the Dlib library.
The 68 facial landmark detector is a robustly trained efficient detector which detects the points on the human face using which 
we determine whether the eyes are open or they are closed.</br></br>
<div align = "center">
  <img src="Drowsiness/Screenshot 2023-09-27 230205.png" align="center" height="350"><br><br>
<b>The 68-landmark detector data (.dat) file can be found <a href="https://www.kaggle.com/datasets/sergiovirahonda/shape-predictor-68-face-landmarksdat/"> By clicking here</a></B>
</div>

## The Working of the project
<ul><li>As you can see the<b> below screenshot's</b> where the landmarks are detected using the detector.
<li>Now we are taking the ratio which is described as <i>'Sum of distances of vertical landmarks divided by twice the distance between horizontal landmarks'</i>.
<li>Now this ratio is totally dependent on your system which you may configure accordingly for the thresholds of sleeping, drowsy, active.</ul>
<p><img src="Drowsiness/Screenshot 2023-09-27 230204.png" align="center" height="350">
<img src="Drowsiness/Screenshot 2023-09-27 230336.png" align="center" height="350">
<img src="Drowsiness/Screenshot 2023-09-27 230433.png" align="center" height="350">
