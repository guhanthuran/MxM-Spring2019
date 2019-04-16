# MxM LSTM creation

LSTM creation sampling from texts 

## Requirements

Python 3, Keras, Tensorflow

## How to use

Train the model with default settings:
```bash
$ python train.py --input tiny-shakespeare.txt
```

To sample the model at epoch 100:
```bash
$ python sample.py 100
```

Training loss/accuracy is stored in `logs/training_log.csv`.
