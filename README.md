## Loop-and-Edges-Detector
Created for use in segemntation of handwritten words.
Loop-and-Edges-Detector is a fast and simple python library to detect loops, outer boundary and edges in binary images. Also available on PyPi.

## Usage
import DetectLoopsEdges as detect <br />
import cv2 <br />
Im = cv2.imread(your_filename)<br />
Loops, Edges, Boundary = detect.DetectLoopsEdges(Im) <br />

## Library Link on PyPi
https://pypi.org/project/pyedgeloop/<br /><br />
Usage: pip install pyedgeloop<br /><br />
Example:<br /><br />
      &nbsp;&nbsp;&nbsp;import pyedgeloop as detect<br />
      &nbsp;&nbsp;&nbsp;import cv2<br />
      &nbsp;&nbsp;&nbsp;Im = cv2.imread(your_filename)<br />
      &nbsp;&nbsp;&nbsp;Loops, Edges, Boundary = detect.DetectLoopsEdges(Im)<br />

## Author
Aditya Dutt

## License
[MIT](https://choosealicense.com/licenses/mit/)
