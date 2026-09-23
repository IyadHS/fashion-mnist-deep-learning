# Fashion-MNIST Deep Learning Benchmark

Image classification project comparing multiple neural network
architectures on the Fashion-MNIST dataset using PyTorch.

## Models
- Multi-Layer Perceptron (MLP)
- Convolutional Neural Network (CNN)
- CNN with Data Augmentation
- Deep CNN

## Methodology
60,000 training images were split into:
- 54,000 training samples
- 6,000 validation samples

The official 10,000-image test set was reserved for final evaluation.

## Results

| Model | Test Accuracy | Macro F1 |
|-------|---------------|----------|
| MLP | 88.22% | 0.8825 |
| CNN | 93.44% | 0.9343 |
| CNN + Augmentation | 92.17% | 0.9204 |
| Deep CNN | 93.26% | 0.9322 |

## Key Findings
- CNN architectures substantially outperformed the MLP baseline.
- The standard CNN achieved 93.44% test accuracy.
- The deeper CNN did not improve test performance despite its additional depth.
- The selected augmentation strategy did not improve performance.
- Shirt remained one of the most difficult classes to classify.

## Technologies
Python · PyTorch · Torchvision · NumPy · Matplotlib · Seaborn · Scikit-learn