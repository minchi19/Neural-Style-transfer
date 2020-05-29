# Neural-Style-transfer implementation in TF - 2.0
# Overview
### For detailed explanation please visit this blog

Python Tensorflow implementation of ["A Neural Algorithm of Artistic Style,"](https://arxiv.org/pdf/1508.06576.pdf) Gatys et al.

## Dependices

Python > 3.5
[Numpy](http://www.numpy.org/)<br>
[PIL](https://pypi.org/project/Pillow/2.2.2/)<br>
[Matplotlib](https://matplotlib.org/)<br>
[Tensorflow > 2.0](https://www.tensorflow.org/)<br>
[Keras](https://keras.io/)<br>

If you have dependency version issue use [vnev](https://docs.python.org/3/tutorial/venv.html)

## Running NST
1) Clone or download this repo.<br>
2) Make the vnev (recommended) <br>
    ``` virtualenv mypython ```
3) cd to the directory where [requirements.txt](requirements.txt) is located<br>
   activate your virtualenv<br>
   ``` mypthon\Scripts\activate ```<br>
   then<br>
   ```
   run:  pip install -r requirements.txt in your shell
   
   ```
 4) open the <br>
``` neural_style_transfer.ipynb ```<br>
     (if using Jupyter notebook) or<br> 
 ```neural_style_transfer.py ```file <br>
    ```change content_path ```variable to path of your content image<br>
    ```style_path variable``` to path of your style image<br>
 5) Run jupyter notebook or ``` python3 neural_style_transfer.py ``` in the shell.<br> 
 
## Results
    

## Future work
- [x] Deploying NST model as a Django webapp. <br>
visit this link for webapp

## Acknowledgments
[https://github.com/Shashi456/Neural-Style](https://github.com/Shashi456/Neural-Style)<br>
[https://www.tensorflow.org/tutorials/generative/style_transfer](https://www.tensorflow.org/tutorials/generative/style_transfer)<br>
[https://github.com/bhrt-sharma/Neural-Style-Transfer](https://github.com/bhrt-sharma/Neural-Style-Transfer)<br>
