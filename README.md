# examples
This repository contains SavviHub examples. If you want to learn more about SavviHub please follow the [quick start documentation](https://docs.savvihub.com/quick-start).

## MNIST
Run MNIST example and save model:
1. PyTorch
* Dataset mount
  1. Create a new dataset with a public S3 bucket directory `s3://savvihub-public-apne2/mnist`.
  2. Mount the dataset to `/input` at the experiment create form.
* Command
  ```bash
  pip install -r mnist/pytorch/requirements.txt && python mnist/pytorch/main.py --save-model
  ```
2. Keras
* No dataset needed.
* Command
  ```bash
  pip install -r mnist/keras/requirements.txt && python mnist/keras/main.py --save-model
  ```

## Detectron2

Run Detectron2 example:
* Dataset mount
  1. Create a new dataset with a public S3 bucket directory `s3://savvihub-public-apne2/detectron2`.
  2. Mount the dataset to `/input` at the experiment create form.
* Command
  ```bash
  pip install -r detectron2/requirements.txt && python detectron2/main.py
  ```
