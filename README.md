# Tracking_and_counting_coordinatess_objectSizes_with_yolov8



  1.How to perform video object tracking and annotate the bounding boxes with coordinates and sizes. The annotated frames are then written to a target video file.
**Object tracking**:  The code utilizes the BYTETracker algorithm/library for object tracking in video frames. **Bounding box annotation**: The code draws bounding boxes around the tracked objects and writes the coordinates and sizes of the boxes on each frame.

The four numbers in the coordinates tuple **(x, y, w, h)** represent the following:

**x**: The x-coordinate of the top-left corner of the bounding box. It specifies the horizontal position of the box in the frame.

**y**: The y-coordinate of the top-left corner of the bounding box. It specifies the vertical position of the box in the frame.

**w**: The width of the bounding box. It specifies the horizontal extent of the box.

**h**: The height of the bounding box. It specifies the vertical extent of the box.


![coordinates and the size of bounding boxes](https://github.com/12194916/Tracking_and_counting_coordinatess_objectSizes_with_yolov8/blob/main/coordinates.gif)

