# FL_Challenge
## Getting started
1. Open «MultiWorkerClassification.ipynb»
2. Launch project on Google Colab, by using the button «Open in Colab» at the head of the document.
3. To run press: Runtime → Run all (Ctrl+F9)

## Abstract
This is a classification model to train on the CIFAR-10 dataset realised as a multi-worker distributed training (3 workers). The neural network architecture based on AlexNet. 
## Note
To achieve appropriate accuracy (0.7 or more) set ```epochs=15, steps_per_epoch=300``` (or more). These parameters are placed at the part ```%%writefile main.py``` on the line ```multi_worker_model.fit()```. But the train takes at least an hour in this way.
