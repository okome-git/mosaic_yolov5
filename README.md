# mosaic_yolov5

## How to use
1. Create label using yolov5 as follows:
 python .\detect.py --source aaa/bbb.mp4 --save-txt --classes 0
 
2. Put original movie and label file
        mosaic_yolov5
        └─data
            ├─labels
            └─original_movie
                      └─bbb.mp4
                      
3. python main.py
