## Loop-and-Edges-Detector
Loop-and-Edges-Detector is a fast and simple python library to detect loops, outer boundary and edges in binary images. Also available on PyPi.

## Usage
import DetectLoopsEdges as detect <br />
import cv2 <br />
Im = cv2.imread(your_filename)<br />
Loops, Edges, Boundary = detect.DetectLoopsEdges(Im) <br />

## Author
Aditya Dutt

## Library Link on PyPi
https://pypi.org/project/pyedgeloop/
Usage: pip install pyedgeloop
Example:
      import pyedgeloop as detect
      import cv2
      Im = cv2.imread(your_filename)
      Loops, Edges, Boundary = detect.DetectLoopsEdges(Im)

## License
[MIT](https://choosealicense.com/licenses/mit/)
