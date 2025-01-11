# toomuchwork
thanks to abdurrahman huraibi and abdulhadi alfaify (GitHub @Aboodalfaify) for making this possible!

# 1-install anaconda
go to https://anaconda.com and install anaconda

# 2-commands to run
go to cmd.exe and run the following
```bash
pip install matplotlib
pip install scipy
pip install scikit-image
pip install scikit-plot
pip install tensorflow
pip install keras
pip install numpy
```
# 3-manual set-up (skip this for shortcut)
### unpack 7zip archive and go to AnimalFace/Image/
go to each and every folder and delete all the images

### get new images
### what to consider when choosing images
5 files for each folder.
1 image (a single across all of them and not for each) **MUST** be flawed/have problem.
so, choose one single file and replace it with one png file with transparency.
**"Natural"** folder must contain random images, that agrees with the format (jpg/png/jfif(yes it actually works)). cannot be gif or webm etc.

### remove every line that contains
`violations[1]` or `pos2`
they are problematic and are not worth fixing

### fix `scikitplot` issues
in
%userprofile%\anaconda3\Lib\site-packages\scikitplot
Or (it's the same)
C:\Users\USERNAME\anaconda3\Lib\site-packages\scikitplot
(change USERNAME to your username, obviously)

change the text `from scipy import interp` into `interp = np.interp` using find-and-replace in files: **metrics.py** and **plotters.py**

# 4-set up using set-up script
(refer to step 3 this if you prefer to do tit manually)
unpack `scripts.zip` and run the batch scipt `modify.bat` as Adminstrator

# 5-unpack and run
unpack the archive `G12.AI.S2.U4.L1.7z`
after finishing anaconda installation search for jupyter and run it
navigate to the **unpacked** `G12.AI.S2.U4.L1.7z` **within jupyter** and go to
`G12.AI.S2.U4.L1\G12.AI.S2.U4.L1.ipynb`

click run when the status circle on the top left of the page turns blank white
keep running until the end of the notebook

you'll encounter warnings during the execution of the notebook, ignore them.
if you encounter any errors, refer to step 4 and run the script. It should fix all issues. if it failed, run the installation commands in step 2 again then do step 4.
if the issue persists don't hesitate to DM me on discord @ahmdmoadi/@ssparcl
