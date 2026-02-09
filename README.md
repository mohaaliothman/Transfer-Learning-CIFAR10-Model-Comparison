# Transfer-Learning-CIFAR10-Model-Comparison

A transfer learning project that fine-tunes and compares multiple pretrained CNN models (ResNet18, VGG16, MobileNetV2) on the CIFAR-10 dataset using PyTorch.

---

## Project Overview

This project evaluates how different pretrained computer vision models perform on CIFAR-10 when fine-tuned for a 10-class classification task. The workflow includes dataset preprocessing, model modification (replacing classification heads), training, testing, and reporting a final accuracy comparison table.

---

## Models Compared

* ResNet18 (pretrained)
* VGG16 (pretrained)
* MobileNetV2 (pretrained)

---

## Dataset

* CIFAR-10 (60,000 images)
* 10 classes
* Images resized to 224×224 to match pretrained model input requirements

---

## Key Features

* Transfer learning using pretrained ImageNet models
* Fine-tuning model classifiers for CIFAR-10 (10 classes)
* Training and evaluation pipeline in PyTorch
* Test accuracy reporting for each model
* Final comparison table of results

---

## How to Run

### 1) Install dependencies

```bash
pip install -r requirements.txt
```

### 2) Run the notebook / script

Run your Python file or notebook that contains the code.

---

## Output

* Training loss per epoch for each model
* Test accuracy for each model
* A table summarizing accuracy results

---

## Author

**Mohammad Ali Othman**
Data Science Student
Jordan University of Science and Technology

---

## License

Educational use only.
