# Model training in traffic.py

1. Copy the source code from lecture note, only change the input shape and train, the performance is very low.
2. Update some layer param and do experiments, find when decreace dropout value from 0.5 to 0.1, then satisfied with the training performance, also evaluation accuracy is not bad (above 90%), so not overfitted.
3. Try to update some other layer params, but no significant improvement. When increase the hidden layer dense param, then will take more time to train the model, but performance got slightly improved.