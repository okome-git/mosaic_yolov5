# mosaic_yolov5

## How to use
<br>
1. Create label using yolov5 as follows:
<br>
 python .\detect.py --source aaa/bbb.mp4 --save-txt --classes 0
<br>
2. Put original movie and label file
<br>
        mosaic_yolov5
        <br>
        └─data
        <br>
            ├─labels
            <br>
            └─original_movie
            <br>
                      └─bbb.mp4
                      <br>
<br>
3. python main.py
<br>
