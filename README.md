This is the implementation of the Temporal Attention-Gated Model, which is proposed in the following paper:
Wenjie Pei, Tadas Baltrušaitis, David M.J. Tax and Louis-Philippe Morency. "Temporal Attention-Gated Model for Robust Sequence Classification", https://arxiv.org/pdf/1612.00385.pdf, which is accepted by CVPR 2017.

The code is implemented in Lua and Torch. It contains mainly the following parts:   
* main.lua:   the starting point of the entire code. 
* train_process.lua: the training process.
* evaluate_process.lua: the evaluation process. 
* package 'model' contains the required models including attention model, TAGM, LSTM, GRU and plain-RNN. 
* package 'util' contains the required small utilities such as data loader. 

Feel free to contact Wenjie Pei (wenjiecoder@gmail.com).

