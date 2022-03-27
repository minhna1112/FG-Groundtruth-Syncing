#FG-Groundtruth-Syncing


Ros-noetic skip step 0
0. (Recommended) Use miniconda 3 to install a python>=3.7 interpreter
python3 -m pip install rospkg bagpy

1. python3 -m pip  tqdm pandas matplotlib

2. Edit Line 161 of file prepare-bag-data.py, provide path to your own bag file, and destination folder to save poses (full and interpolated) in text files 
    Run: python3 prepare-bag-data.py

3. Edit path pointing to the recently generated text files in line 10, 14 file viz.py
    Run: python3 viz.py