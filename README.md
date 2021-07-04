# Food-Classification-lesson-practice-
NOTICE!! This is a lesson practice. 
The sample code is from Course of <a href="https://speech.ee.ntu.edu.tw/~tlkagk/courses.html">Professor Haungyi Lee in NTU</a>.
This work here is a process of understanding DL model structure and Pytorch API through implementation practice.  
There are some modification of debugging due to version difference.

## Assignment Target - Food classification based on Food-11 data set  
**The 11 Category contains:**  
Bread Dairy product  
Dessert Egg Fried_food  
Meat Noodles/Pasta Rice Seafood  
Soup

Vegetable-Fruit
<p float="left">
<img src="https://user-images.githubusercontent.com/55873158/124389273-fe47bd00-dd18-11eb-8824-b798b43cc48c.jpg" width="150" height="150" >
<img src="https://user-images.githubusercontent.com/55873158/124389304-14557d80-dd19-11eb-904b-7711d6625a82.jpg" width="150" height="150" >
<img src="https://user-images.githubusercontent.com/55873158/124389311-18819b00-dd19-11eb-82b4-6a4719fd2b37.jpg" width="150" height="150" >
<img src="https://user-images.githubusercontent.com/55873158/124389322-21726c80-dd19-11eb-90dc-c4b2a6e40ded.jpg" width="150" height="150" >
<img src="https://user-images.githubusercontent.com/55873158/124389328-27684d80-dd19-11eb-9f27-f46b628ab89c.jpg" width="150" height="150" >
<img src="https://user-images.githubusercontent.com/55873158/124389332-2c2d0180-dd19-11eb-8520-068ddc95093f.jpg" width="150" height="150" >
<img src="https://user-images.githubusercontent.com/55873158/124389338-32bb7900-dd19-11eb-924d-ed660e4ae4d9.jpg" width="150" height="150" >
<img src="https://user-images.githubusercontent.com/55873158/124389342-35b66980-dd19-11eb-9fae-0fde08816f20.jpg" width="150" height="150" >
<img src="https://user-images.githubusercontent.com/55873158/124389377-5979af80-dd19-11eb-9d32-99d1b8a84aef.jpg" width="150" height="150" >
<img src="https://user-images.githubusercontent.com/55873158/124389348-3e0ea480-dd19-11eb-9c41-3d232bae18c1.jpg" width="150" height="150" >
<img src="https://user-images.githubusercontent.com/55873158/124389385-61d1ea80-dd19-11eb-9c7c-6a780d1276d6.jpg" width="150" height="150" >
</p>

## Training process ( Include Validation Data )

    [001/030] 18.61 sec(s) Train Acc: 0.259176 Loss: 0.016821
    [002/030] 18.72 sec(s) Train Acc: 0.370337 Loss: 0.014038
    [003/030] 18.98 sec(s) Train Acc: 0.437274 Loss: 0.012550
    [004/030] 18.89 sec(s) Train Acc: 0.487064 Loss: 0.011392
    [005/030] 18.97 sec(s) Train Acc: 0.523240 Loss: 0.010625
    [006/030] 19.14 sec(s) Train Acc: 0.568066 Loss: 0.009667
    [007/030] 19.40 sec(s) Train Acc: 0.596270 Loss: 0.009078
    [008/030] 19.26 sec(s) Train Acc: 0.618758 Loss: 0.008522
    [009/030] 19.48 sec(s) Train Acc: 0.647638 Loss: 0.007949
    [010/030] 19.36 sec(s) Train Acc: 0.662004 Loss: 0.007582
    [011/030] 19.41 sec(s) Train Acc: 0.694344 Loss: 0.006957
    [012/030] 19.40 sec(s) Train Acc: 0.706077 Loss: 0.006616
    [013/030] 19.43 sec(s) Train Acc: 0.724504 Loss: 0.006242
    [014/030] 19.36 sec(s) Train Acc: 0.735785 Loss: 0.005881
    [015/030] 19.44 sec(s) Train Acc: 0.749925 Loss: 0.005519
    [016/030] 19.56 sec(s) Train Acc: 0.765418 Loss: 0.005245
    [017/030] 19.66 sec(s) Train Acc: 0.782942 Loss: 0.004882
    [018/030] 19.77 sec(s) Train Acc: 0.799564 Loss: 0.004520
    [019/030] 19.67 sec(s) Train Acc: 0.803023 Loss: 0.004465
    [020/030] 19.62 sec(s) Train Acc: 0.818141 Loss: 0.004121
    [021/030] 19.65 sec(s) Train Acc: 0.828595 Loss: 0.003867
    [022/030] 19.71 sec(s) Train Acc: 0.841005 Loss: 0.003558
    [023/030] 19.52 sec(s) Train Acc: 0.850481 Loss: 0.003320
    [024/030] 19.62 sec(s) Train Acc: 0.858830 Loss: 0.003182
    [025/030] 19.48 sec(s) Train Acc: 0.875752 Loss: 0.002769
    [026/030] 19.53 sec(s) Train Acc: 0.885078 Loss: 0.002579
    [027/030] 19.59 sec(s) Train Acc: 0.891245 Loss: 0.002398
    [028/030] 19.60 sec(s) Train Acc: 0.894179 Loss: 0.002336
    [029/030] 19.55 sec(s) Train Acc: 0.905912 Loss: 0.002124
    [030/030] 19.66 sec(s) Train Acc: 0.919149 Loss: 0.001804



