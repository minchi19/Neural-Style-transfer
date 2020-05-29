# Neural-Style-transfer implementation in TF - 2.0
# Overview
Have you ever wondered how smartphones camera filters work?<br>
How do Snapchat or Instagram filters work?<br>
Do you want to paint like Picasso?<br>
<br>
If yes then you should know about The Neural Style Transfer Algorithm.<br><br>
**Style Transfer can be defined as the process of reconstruction of an image in the style of another image.**<br>

### For detailed explanation please visit [this](https://neuralnetwork.codes/neural-style-transfer-using-tf-2-0/) blog

Python Tensorflow implementation of ["A Neural Algorithm of Artistic Style,"](https://arxiv.org/pdf/1508.06576.pdf) Gatys et al.

![Result](https://github.com/minchi19/Neural-Style-transfer/blob/master/results/results/foo%20(4).png)
## Dependices

Python > 3.5 <br>
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
    
![](https://github.com/minchi19/Neural-Style-transfer/blob/master/results/results/monolisa%2Babstract.JPG)
Iterations - 1000 content_weight=1e-1,style_weight=1e2
![nstresult](https://github.com/minchi19/Neural-Style-transfer/blob/master/results/results/result5.png)
Iterations - 500 content_weight=1e-1,style_weight=1e2
## Future work
- [x] Deploying NST model as a Django webapp. <br>
visit [this](https://github.com/minchi19/neural-style-transfer-webapp) link for webapp

## Acknowledgments
[https://github.com/Shashi456/Neural-Style](https://github.com/Shashi456/Neural-Style)<br>
[https://www.tensorflow.org/tutorials/generative/style_transfer](https://www.tensorflow.org/tutorials/generative/style_transfer)<br>
[https://github.com/bhrt-sharma/Neural-Style-Transfer](https://github.com/bhrt-sharma/Neural-Style-Transfer)<br>
