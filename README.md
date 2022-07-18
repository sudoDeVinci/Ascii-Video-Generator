# Ascii-Video-Generator

A script to convert video frames into ascii art and display them in the command line.

I made this for the Adult swim tiktok trend. It downsizes a given video and converts it into ascii art fram by frame.
I have also made it so that the framerate, height and width of the video output can be toggled in real time via trackbars.

This works simply by matching the "pixel density" of a given ascii character to a light intensity range of a pixel within a greyscaled version of the video.

This has no real uses but it was fun to build either way.

## Update (18/07/2022)

To allow for faster playback and higher image resolution in the terminal, The FileVideoStream Class of the [imutils lib](https://github.com/PyImageSearch/imutils/blob/master/imutils/video/filevideostream.py) was used to allow a Queue-Dequeue system for frames.
