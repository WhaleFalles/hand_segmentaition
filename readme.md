## environment
conda: conda install environment.yml  
or  
virtualenv: pip install -r requirements.txt  

## usage
### run commands
activate your_virtual_env_name  
jupyter notebook
### train
#### data 
Put hand data in the dir "data"  
gain model from dir "model"
gain result from dir "test_rgb_and_mask"  
#### run
main->fcn.ipynb

### predict
#### data 
Put hand data in the dir "data"  
put your advance trained model in the dir "model"
gain result from dir "test_rgb_and_mask"  
#### run
main -> predict.ipynb (run it to predict hand picture)  


## result

![Image](https://github.com/WhaleFalles/hand_segmentaition/blob/master/main/2019-12-20%20175224.png)
## others

#### download
My trained model and result :  
url：https://pan.baidu.com/s/1sYBSJAEVFccRTLGjJzeD0Q   
password：n81z   

#### refer
book：《动手学深度学习》
github：https://github.com/d2l-ai/d2l-zh
```python

```
