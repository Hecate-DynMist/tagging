## Text Classification with CNN and RNN

####Description
News:31019
Categories:3684
Top 20 tags
产业       1503
理论       1003
论文        851
深度学习    708
机器学习    656
计算机视觉  529
人工智能    523
NLP         520
工程        504
谷歌        419


####Train Results
Training and evaluating...                                                                                                                                            [126/1254]
Epoch: 1                                                                                                                                                                       
2019-04-09 20:04:55.042449: I tensorflow/stream_executor/dso_loader.cc:152] successfully opened CUDA library libcublas.so.10.0 locally
Iter:      0, Train Loss:    8.2, Train Acc:   0.00%, Val Loss:    8.2, Val Acc:   0.03%, Time: 0:00:14 *                                                                       
Iter:    100, Train Loss:    6.0, Train Acc:   7.03%, Val Loss:    7.3, Val Acc:   0.30%, Time: 0:01:36 *                             
Epoch: 2                                                        
Iter:    200, Train Loss:    5.8, Train Acc:  10.16%, Val Loss:    7.3, Val Acc:   0.30%, Time: 0:02:58
Iter:    300, Train Loss:    6.0, Train Acc:   5.47%, Val Loss:    7.4, Val Acc:   0.30%, Time: 0:04:19                                                             
Epoch: 3                                         
Iter:    400, Train Loss:    5.8, Train Acc:   5.47%, Val Loss:    7.6, Val Acc:   0.30%, Time: 0:05:41
Epoch: 4                                                                                                                                                                        Iter:    500, Train Loss:    5.8, Train Acc:   7.03%, Val Loss:    7.5, Val Acc:   0.30%, Time: 0:07:03
Iter:    600, Train Loss:    5.9, Train Acc:   7.81%, Val Loss:    7.5, Val Acc:   0.30%, Time: 0:08:25 *             
Epoch: 5                                              
Iter:    700, Train Loss:    5.9, Train Acc:   5.47%, Val Loss:    7.5, Val Acc:   0.30%, Time: 0:09:47            
Epoch: 6                                                                                                          
Iter:    800, Train Loss:    5.5, Train Acc:   8.59%, Val Loss:    7.6, Val Acc:   0.30%, Time: 0:11:09                                                          
Iter:    900, Train Loss:    6.0, Train Acc:   5.47%, Val Loss:    7.6, Val Acc:   0.30%, Time: 0:12:31                            
Epoch: 7                                                                                                                                                                        Iter:   1000, Train Loss:    6.0, Train Acc:   5.47%, Val Loss:    7.7, Val Acc:   0.30%, Time: 0:13:52                                                                         
Epoch: 8                                                                                                                                             
Iter:   1100, Train Loss:    6.1, Train Acc:   6.25%, Val Loss:    7.8, Val Acc:   0.30%, Time: 0:15:14                                                                         
Iter:   1200, Train Loss:    5.5, Train Acc:  11.72%, Val Loss:    7.7, Val Acc:   0.30%, Time: 0:16:36             
Epoch: 9                                                    
Iter:   1300, Train Loss:    6.1, Train Acc:   5.47%, Val Loss:    7.6, Val Acc:   0.30%, Time: 0:17:57           
Iter:   1400, Train Loss:    6.0, Train Acc:   7.03%, Val Loss:    7.8, Val Acc:   0.30%, Time: 0:19:19                                                                         
Epoch: 10                                                                                                                          
Iter:   1500, Train Loss:    5.9, Train Acc:   7.03%, Val Loss:    7.7, Val Acc:   0.30%, Time: 0:20:41        

####Test Results
Test Loss:    5.9, Test Acc:   7.38%
Time usage: 0:01:17

Low accuracy due to large categories number without sufficient dataset.
