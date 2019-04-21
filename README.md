# Hand_Gesture_Recognition
Hand Gesture Recognition using OpenCV and Python.

</br>
# Detects finger movements of hands and shows appropriate output.
<h3>Steps:</h3>

<h4>Segment hand region from a real-time video sequence</h4>
</br>
<Background Subtraction
Motion Detection and Thresholding
Contour Extraction

<h4>Count fingers</h4>
</br>
Get convex hull of the segmented hand region and compute the most extreme points in the convex hull
Get center of palm using extremes points
Using center of palm, construct a circle with the maximum Euclidean distance as radius
Perform bitwise AND operation on thresholded hand image and the circular ROI
Compute count of fingers using the finger slices obtained in previous step

<h4>To run the file use: python sudo.py</h4>
<br/>
<b>
#f03c15 Memory Intensive Operation
#f03c15 This script creates screenshot for every frame captured and stores it in directory 'screenshots'
#f03c15 Hence, there is a little delay during frame capture
