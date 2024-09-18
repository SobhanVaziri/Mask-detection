- <b><a href="#Live-Face-mask-detection">If you want to run the program live, click here</a></b><br>
- <b><a href="#Video-face-mask-detection">If you have a video, click here</a></b>

1. clone the repositories:

```git
git clone https://github.com/SobhanVaziri/Mask-detection.git
```

2. install requirement:

```cmd
pip install -r requirements.txt
```

# Live Face mask detection

1. Train your dataset with the `TrainingModel.ipynb` file and save its output in the specified `path`
   - Or you can scan your face photo by running `dataCollector.py` and connect your webcam and use them as dataset.
2. Open `cmd` terminal in your directory

3. To run __Live Face mask detection__, type this line of code in `cmd` terminal and run

```cmd
python main.py
```

4. Press the `q` button to exit the program.

<center>
    <hr width=100% size=4 noshade />
</center>

# Video face mask detection

If you want to upload a video in `mp4` format and the program will detect whether it has a mask or not, use the following __link__:
- Go to __Video face mask detection__ folder
- And run the __video-face-mask-detection.ipynb__ file
- Upload your file location in this line of code --> __`cap = cv2.VideoCapture('Your patch file.mp4')`__
