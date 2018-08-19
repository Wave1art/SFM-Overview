# SFM-Overview

Useful SFM / Photogrammetry tools and processing pipelines 



# Tools
ffmpeg - command line tool to extract images from video
vSFM - open source SFM engine
MVE - processing pipeline (including SFM engine sfmrecon)
umve - user interface into MVE for viewing scenes 


# Useful websites & resources
https://github.com/simonfuhrmann/mve/wiki/MVE-Users-Guide
https://pdfs.semanticscholar.org/c9f8/c6ff1c1e52db988fe6b0f6d1bf144fd6be4a.pdf
https://github.com/john-davies/Photogrammetry-examples
https://pfalkingham.wordpress.com/2016/09/14/trying-all-the-free-photogrammetry/
https://3dscanexpert.com/free-3d-scanning-video-smartphone/


# Processing pipelines





## Extracting images from video files

use FFmpeg to output each frame individually:

ffmpeg -i /path/to/video.mkv /path/to/output-%04d.jpg

You can also use png instead of jpg for lossless results, and change the number in %04d if you need more digits when the file is longer.


