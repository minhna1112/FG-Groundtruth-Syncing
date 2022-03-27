# FG-Groundtruth-Syncing


## Ros-noetic skip step 0

0. (Recommended) Use miniconda 3 to install a python>=3.7 interpreter
python3 -m pip install rospkg bagpy

1. python3 -m pip  tqdm pandas matplotlib

2. Edit Line 161 of file prepare-bag-data.py, provide path to your own bag file, and destination folder to save poses (full and interpolated) in text files 
    Run: python3 prepare-bag-data.py

3. Edit path pointing to the recently generated text files in line 10, 14 file viz.py
    Run: python3 viz.py
    
4. Result should be something like this
![Screenshot from 2022-03-27 22-03-38](https://user-images.githubusercontent.com/26354139/160287828-4dd392b0-5828-495e-aa11-e8892a2ed6c3.png)

After zooming in
![Screenshot from 2022-03-27 22-03-57](https://user-images.githubusercontent.com/26354139/160287840-63e874a7-2331-4645-8f02-00bbc84b4c42.png)

![Screenshot from 2022-03-27 22-04-12](https://user-images.githubusercontent.com/26354139/160287847-6600a50c-0def-4c17-9bb8-6f7097e8ecb5.png)
