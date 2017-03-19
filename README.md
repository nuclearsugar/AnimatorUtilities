# Animator Utilities
This is a collection of Pure Data patches to convert between timecode/frames, calculate shot duration, and roughly estimate job time on a render farm.

I created these tools to simplify my workflow when creating 3D animation scenes in Maya and After Effects. So these tools use a frame rate of 30fps for their conversions. But the patches can be edited to work at other frame rates, should you need.

### Requires use of Pd-Extended
It's free and open source. Available for Mac, Windows, & Linux.<br>
http://puredata.info/downloads/pd-extended/releases/0.43.4

-----

### Convert timecode into frames / Convert frames into timecode

![Convert timecode/frames](https://thefulldomeblog.files.wordpress.com/2016/03/convert-frames-timecode.gif)

-----

### Calculate shot duration: input as timecode or frames
Especially useful when adjusting timings between two versions of the animatic and need to figure out the exact amount of time added or removed.

![Calculate shot duration](https://thefulldomeblog.files.wordpress.com/2016/03/convert-duration-frames-timecode.gif)

-----

### Estimate Job Render Time on a Farm
Most useful for estimating the min/max time until the render is complete. Which is especially important if you’re worried about bottlenecking your farm and need to prioritize for deadlines.

![Estimate Job Render Time on a Farm](https://thefulldomeblog.files.wordpress.com/2016/03/estimate-render-time.gif)

### More info
https://thefulldomeblog.com/2016/03/25/utilities-for-converting-timecode-frames/
