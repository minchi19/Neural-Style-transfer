# Neural-Style-transfer implementation in TF - 2.0
# Overview
### For detailed explanation please visit this blog

Python Tensorflow implementation of ["A Neural Algorithm of Artistic Style,"](https://arxiv.org/pdf/1508.06576.pdf) Gatys et al.

## Dependices

[Numpy](http://www.numpy.org/)
[PIL](https://pypi.org/project/Pillow/2.2.2/)
[Matplotlib](https://matplotlib.org/)
[Tensorflow > 2.0](https://www.tensorflow.org/)
[Keras](https://keras.io/)

If you have dependency version issue use [vnev](https://docs.python.org/3/tutorial/venv.html)

## Running NST
1) Clone or download this repo.
2) Make the vnev (recommended)
3) cd to the directory where requirements.txt is located
   activate your virtualenv
   ```
   run:  pip install -r requirements.txt in your shell
   
   ```
 4) open the 
``` neural_style_transfer.ipynb ```
     (if using Jupyter notebook) or 
 ```neural_style_transfer.py ```file 
    ```change content_path ```variable to path of your content image
    ```style_path variable``` to path of your style image
 5) Run jupyter notebook or ``` python3 neural_style_transfer.py ``` in the shell. 

## Acknowledgments
[https://github.com/Shashi456/Neural-Style](https://github.com/Shashi456/Neural-Style)
[https://www.tensorflow.org/tutorials/generative/style_transfer](https://www.tensorflow.org/tutorials/generative/style_transfer)
[https://github.com/bhrt-sharma/Neural-Style-Transfer](https://github.com/bhrt-sharma/Neural-Style-Transfer)
