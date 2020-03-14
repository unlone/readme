## Implementation of deep learning framework --ERRN, using tensorflow

Here is an enhanced recursive residual network (ERRN) for  MR image 

### Data：

I'm sorry to tell you that you have to use your own data to train. You only need to train with your own data set and pay attention to the path.（Test_data，validation_folder）

You can change the scale factor in the file:

(ERRN_SR_main_Gaussian_x2, ERRN_Cascade_SR_main_Gaussian_X2)to change the subsampling for comparison and others remain unchanged.Similarl,you can change the sample rate to adjust the undersampling rate.

(ERRN_main_Guassian2D10,ERRN_main_Radial2D10)

### Name:

ERRN_main_Guassian1D10.py 	represents  the  main  ERRN  function  of  Cartesian 	undersampling at 10% sampling rate.

ERRN_main_Radial2D10.py 	represents  the  main  ERRN  function  of  radial 	undersampling at 10% sampling rate.



### Model:

![Model1.png]( https://s1.ax1x.com/2020/03/14/8Qs1w6.png )

**ERRN	model	for	cs** 



![Model2.png]( https://s1.ax1x.com/2020/03/14/8Qsjn1.png )

**ERRN	model	for	SR**

#### My version of Python is 3.7 and tensorflow is 1.13.
