# toomuchwork
good luck with this project muahahahahahaha

# what to install
```bash
pip install matplotlib
pip install scipy
pip install scikit-image
pip install scikit-plot
pip install tensorflow
pip install keras
pip install numpy
```

# unpack 7zip archive and go to AnimalFace/Image/
go to each and every folder and delete all the images

# get new images
### what to consider when choosing images
5 files for each folder.
1 image (a single across all of them and not for each) **MUST** be flawed/have problem.
so, choose one single file and replace it with one png file with transparency.
**"Natural"** folder must contain random images, that agrees with the format (jpg/png/jfif(yes it actually works)). cannot be gif or webm etc.

# remove every line that contains
`violations[1]` or `pos2`
they are problematic and are not worth fixing

# fix `scikitplot` issues
in
C:\Users\USERNAME\anaconda3\Lib\site-packages\scikitplot
(change USERNAME to your username, obviously)

change the text `from scipy import interp` into `interp = np.interp` using find-and-replace in files: **metrics.py** and **plotters.py**

