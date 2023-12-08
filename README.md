# Reels:
This is the repository to convert any Youtube video with captions enabled into useful reels.
## Installation:
```
pip install -r requirements.txt
```
## Steps to run:
1. Change the VideoID to the Youtube Video that you want to convert into reels.
2. Run the following command - 
```
python3 autocropper.py
```
3. The outputs will be the root directory in the format of output_cropped000_final.mp4.

## Notes: 
1. The first run will take few minutes as it will download the pretrained model.
2. This code will only work with youtube videos that have english captions. Please extract the function Reeler3 to convert any video into a smart focus reel.

##Future Works:
1. Change Focus on objects based on Salient Object Detection instead of People Centric Smart Focus.
2. Use Speech Diarization to identify speakers and map them to faces.
