# starter code for a2

---
Our original report was 21 pages long and we trimmed some part like performance analysis. 
---

Add the corresponding (one) line under the ``[to fill]`` in ``def forward()`` of the class for ffnn.py and rnn.py

Feel free to modify other part of code, they are just for your reference.

---

One example on running the code:

**FFNN**

``python FFNN_FPU.py --hidden_dim 10 --epochs 1 ``
``--train_data ./training.json --val_data ./validation.json``


**RNN**

``python RNN_GPU.py --hidden_dim 32 --epochs 10 ``
``--train_data training.json --val_data validation.json``

