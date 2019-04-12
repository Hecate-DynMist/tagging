# Text Classification with CNN and RNN

Training based on TensorFlow. 

Origin Github: https://github.com/gaussic/text-classification-cnn-rnn

## Environment

- Python 2/3
- TensorFlow >=1.3
- numpy
- scikit-learn
- scipy

## Dataset

7216 news from Synced Technology

Categories:

```
['产业', '理论', '论文', '深度学习', '机器学习', '计算机视觉', '人工智能', 'NLP', '工程', '谷歌']
```

- cnews.train.txt: training dataset (5772)
- cnews.val.txt: evaluation dataset (722)
- cnews.test.txt: 测试集(722)

### Quick Start

 ```bash
$ python run_rnn.py train # training
$ python run_rnn.py test # testing
 ```



When re-train, delelete tensorboard/textcnn to avoid results overlap. 

### Training Result

```
# Training Result
Configuring CNN model...
Configuring TensorBoard and Saver...
Loading training and validation data...
Time usage: 0:00:04
Training and evaluating...
Epoch: 1                                                                                               
2019-04-12 21:55:38.334335: I tensorflow/stream_executor/dso_loader.cc:152] successfully opened CUDA library libcublas.so.10.0 locally                                          
Iter:      0, Train Loss:    2.3, Train Acc:   6.25%, Val Loss:    2.3, Val Acc:  13.75%, Time: 0:00:02 *
Iter:     50, Train Loss:    2.1, Train Acc:  28.12%, Val Loss:    2.6, Val Acc:   2.64%, Time: 0:00:37
Epoch: 2                                                                                               
Iter:    100, Train Loss:    2.3, Train Acc:  21.88%, Val Loss:    2.5, Val Acc:   2.64%, Time: 0:01:13                                                             
Iter:    150, Train Loss:    2.2, Train Acc:  18.75%, Val Loss:    2.5, Val Acc:   2.64%, Time: 0:01:48
Epoch: 3                       
Iter:    200, Train Loss:    2.1, Train Acc:  26.56%, Val Loss:    2.6, Val Acc:   3.19%, Time: 0:02:23                                                                        
Iter:    250, Train Loss:    2.0, Train Acc:  28.12%, Val Loss:    2.6, Val Acc:   3.33%, Time: 0:02:58
Epoch: 4                                                                                               
Iter:    300, Train Loss:    2.2, Train Acc:  15.62%, Val Loss:    2.6, Val Acc:   3.61%, Time: 0:03:33
Iter:    350, Train Loss:    2.1, Train Acc:  29.69%, Val Loss:    2.7, Val Acc:   3.19%, Time: 0:04:09
Epoch: 5                                                                                               
Iter:    400, Train Loss:    1.9, Train Acc:  31.25%, Val Loss:    2.7, Val Acc:   4.17%, Time: 0:04:44
Iter:    450, Train Loss:    1.8, Train Acc:  35.94%, Val Loss:    2.8, Val Acc:   4.17%, Time: 0:05:19
Epoch: 6                                                                                               
Iter:    500, Train Loss:    1.9, Train Acc:  42.19%, Val Loss:    2.8, Val Acc:   4.17%, Time: 0:05:54                                                                         
Epoch: 7                                                                                               
Iter:    550, Train Loss:    2.1, Train Acc:  31.25%, Val Loss:    2.7, Val Acc:   6.39%, Time: 0:06:29
Iter:    600, Train Loss:    1.8, Train Acc:  32.81%, Val Loss:    2.8, Val Acc:   6.39%, Time: 0:07:05
Epoch: 8                                                                                                                                                                      
Iter:    650, Train Loss:    1.6, Train Acc:  45.31%, Val Loss:    2.9, Val Acc:   4.58%, Time: 0:07:40
Iter:    700, Train Loss:    1.8, Train Acc:  43.75%, Val Loss:    2.9, Val Acc:   5.14%, Time: 0:08:15
Epoch: 9                                                                                                          
Iter:    750, Train Loss:    1.7, Train Acc:  37.50%, Val Loss:    2.9, Val Acc:   6.94%, Time: 0:08:50                                              
Iter:    800, Train Loss:    1.8, Train Acc:  37.50%, Val Loss:    2.9, Val Acc:   6.25%, Time: 0:09:26                            
Epoch: 10                                                                                                                                                                       
Iter:    850, Train Loss:    1.8, Train Acc:  42.19%, Val Loss:    3.1, Val Acc:   6.67%, Time: 0:10:01                                                                         
Iter:    900, Train Loss:    1.7, Train Acc:  43.75%, Val Loss:    2.9, Val Acc:   6.39%, Time: 0:10:36                                              
Epoch: 11                                                                                                                                   
Iter:    950, Train Loss:    1.4, Train Acc:  50.00%, Val Loss:    3.0, Val Acc:   6.39%, Time: 0:11:11             
Iter:   1000, Train Loss:    1.0, Train Acc: 100.00%, Val Loss:    3.0, Val Acc:   6.81%, Time: 0:11:47                                                                         
No optimization for a long time, auto-stopping...
```




### Testing Result

```
Testing...
2019-04-12 22:15:52.926206: I tensorflow/stream_executor/dso_loader.cc:152] successfully opened CUDA library libcublas.so.10.0 locally
Test Loss:    2.3, Test Acc:   7.85%
```

