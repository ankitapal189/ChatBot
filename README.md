# DEPRECATED
__This project was built in 2016 (the old tensorflow era), and some design choices no longer
make sense under the new tensorflow. You are likely to find better seq2seq tutorial/implementation somewhere else.__

## seq2seq_chatbot
An implementation of Seq2seq chatbot in tensorflow.

### Features
* dynamic rnn with smart loader **(padding free)**
* beam search on prediction **(fast approximation on global optimum)**
* signal indicator for decoder **(partial control on decoder)**

### Instruction
* run "python train.py" and wait (5 minutes on GTX 1080 Ti with cuda 9.0 and cudnn 7.0) until training is completed
* run "python test.py" to enter the interactive session with the chatbot
