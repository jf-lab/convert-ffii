# convert-ffii

## Requirements
- [ffmpeg](http://ffmpeg.org/download.html)
- Python 3+

## Instructions
1. First check and modify the frame rate as necessary in `ffii2avi_recursive.py` on line 34 (default: `rate = 15`)
2. If you need a different file format, check with ffmpeg if compatible and simply change the file 
format extension   
(default: `of = filename[:-5]+'.avi'`)

In terminal/shell:  
```
$ cd /path/to/folder/with/ffii2avi_recursive.py/
$ python ffii2avi_recursive.py /path/to/ffii/videos/
```

