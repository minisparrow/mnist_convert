# User Guide 


## 1.  下载mnist 数据集

http://yann.lecun.com/exdb/mnist/

## 2.  放在某个位置

```
 mnist/data/Image/
      train-images.idx3-ubyte
      train-labels.idx1-ubyte
      t10k-images.idx3-ubyte
      t10k-labels.idx1-ubyte
```   
     
 ## 3. 下载本仓代码
 
 放在某个位置
```
mnist/data/mnist_convert
     convert_test.py
     convert_train.py
```

 
 ## 4. 运行脚本，将ubyte数据生成为png

```
 python convert_test.py
 python convert_train.py
```
 
      
