# frame_grabber
<h1> Save frames from a video using Python and OpenCV </h1>
<b>Purpose :</b> the aim of this simple is to set up a simple application for extracting some frames form a video.<br />
<b>Features: </b> The path of the video will be passed as command line parameter. The user will be able to navigate through the video, select a frame and save it.<br />
<b>Keywords :</b> Frame, Video, extract, OpenCV, Python, HighGUI <br />
<b>Tested on:</b> Intel Core i7 @1.7GHz, 8 GB RAM, Ubuntu 14.04 LTS, Python 2.7.9, OpenCV 2.4.8 <br />
<pre>
Script: frame_grabber.py
Usage: python frame_grabber.py path/to/video
Requires: OpenCV 2.4.8+
Purpose: Select and save frames from a given video.
Commands:
    Key             Function
    a               previous frame
    d               next frame
    q               exit
    SHIFT + a       skip 10 frames forward
    SHIFT + d       skip 10 frames backwards
    s               saves current frame
    dbl click       saves current frame

Controls:
    Slider          Navigate through the video

More info: http://giusedroid.blogspot.com
</pre>
