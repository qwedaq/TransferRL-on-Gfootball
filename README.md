# TransferRL-on-Gfootball
Trained GFootball environment on different tasks. Trained on 3_vs_1 first from scratch. Then trained 5_vs_3 on parameters from 3_vs_1 and scratch. While there was no difference in the time taken to achieve more than 95% performance, the transfer learned model learned passing from the previous model while the model trained from scratch opted to dribble. The goal of this training was to figure out if there is a way to make RL models learn concepts rather than overfit on the environment. The next step would be to use this learning paradigm to make RL agent learn relations among entites in environment.
# Training results
![alt-text](https://github.com/aveen-d/TransferRL-on-Gfootball/blob/master/gifs/3_v_1.gif)
3_vs_1 scratch
![alt-text](https://github.com/aveen-d/TransferRL-on-Gfootball/blob/master/gifs/5_v_3_scratch.gif)
5_vs_3 scratch
![alt-text](https://github.com/aveen-d/TransferRL-on-Gfootball/blob/master/gifs/5_vs_3_transfer.gif)
5_vs_3 trasfer
![alt-text](https://github.com/aveen-d/TransferRL-on-Gfootball/blob/master/Graphs/1.png)
![alt-text](https://github.com/aveen-d/TransferRL-on-Gfootball/blob/master/Graphs/2.jpg)
![alt-text](https://github.com/aveen-d/TransferRL-on-Gfootball/blob/master/Graphs/3.jpg)
