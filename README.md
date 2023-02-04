# audi-dashcam

Simple bash script that does the following:
  1. Extract front and rear video streams from Audi dashcam AVI file.
  2. Convert extracted streams from AVI to MP4, so that it can be opened 
     or processed in by most media players and video editors.
     
Output format is YouTube optimised mp4:
  - Video: H264 1920x1080 30FPS CRF 20
  - Audio: AAC Stereo 44100HZ 1411KB/S

Requires ffpmeg (https://ffmpeg.org/).

