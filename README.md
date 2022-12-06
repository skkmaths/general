# Converting avi video files to a sequence of .png image files

Install ffmpeg
```
$ffmpeg -i video.avi fig%d.png
```
This will creat a sequence of image like fig1.png, fig2.png ...
