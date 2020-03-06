# Resnet50 tensrorflow2.0

Dataset
-------
#### Cat vs Dog dataset Download Site : <https://www.kaggle.com/c/dogs-vs-cats/data>
Train dataset을 Train iamge 17000장, vaildation image 4000장, test image 4000장으로 나누어서 실험하였다.(그림1 참조)   
   
>그림1   

<img src="/image/1.JPG" width="80%" height="80%" title="img1" alt="img1"></img>

Resnet50 Architecture
----------------
<img src="/image/2.JPG" width="80%" height="80%" title="img1" alt="img1"></img>
***


Option
------
#### tensorflow version 2+
#### input_shape : [224,224,3], Batch_size : 32,step= 30, epochs = 300
#### compile option : optimizers= SGD(lr = 1e-6,momentum=0.9), loss='binary_crossentropy', metrics=['acc']

Result
------
<img src="/image/3.JPG" width="80%" height="80%" title="img1" alt="img5"></img>

>GradCAM heatmap image   
   
<img src="/image/5.JPG" width="80%" height="80%" title="img1" alt="img5"></img>   
   
>Confustion Matrix   

<img src="/image/4.JPG" width="80%" height="60%" title="img1" alt="img5"></img>   



