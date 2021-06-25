# mosaic_yolov5
<br>
<br>
## Case2 : Use output YOLOv5 labels and original movie
<br>
1. Simply type commands like yolov5 like below:
  <br>
  &emsp;python .\detect.py --source aaa/bbb.mp4 --save-txt --classes 0
<br>
<br>

## Case2 : Use output YOLOv5 labels and original movie
<br>
1. Create label using yolov5 as follows:
<br>
 python .\detect.py --source aaa/bbb.mp4 --save-txt --classes 0
<br>
<br>
2. Put original movie and label file
<br>
        mosaic_yolov5
        <br>
        &emsp;└─data
        <br>
            &emsp;&emsp;├─labels
            <br>
            &emsp;&emsp;└─original_movie
            <br>
                      &emsp;&emsp;&emsp;└─bbb.mp4
                      <br>
<br>
<br>
3. Change mp4 file name in mosac.py
<br>
&emsp;[9] &emsp;video_path = "./data/original_movie/bbb.mp4" # bbb is your mp4 file name


<br>
<br>
4. python mosaic.py
<br>
