# A4FL-Federated-Adversarial-Defence-via-Adversarial-Training-and-Pruning-Against-Backdoor-Attack
# Federated Adversarial Defense via Adversarial Training and Pruning Against Backdoor Attack

This project demonstrates the use of adversarial defense mechanisms in deep learning models, particularly the adversarial training and pruning strategies to defend against backdoor attacks in a federated learning setup. The code specifically utilizes adversarial attacks and defense methods such as Fast Gradient Sign Method (FGSM) to evaluate the effectiveness of the model under attack conditions.

### Features
- **Simple CNN Model**: A simple Convolutional Neural Network (CNN) model for image classification on the CIFAR-10 dataset.
- **Data Augmentation**: Implemented various data augmentation techniques including random rotations, flips, and brightness adjustments to improve model generalization.
- **Adversarial Attack**: Utilizes FGSM (Fast Gradient Sign Method) to generate adversarial examples.
- **Flame Flair Comparison**: Uses the Structural Similarity Index (SSIM) to compare original and adversarial images, providing a flame flair comparison to assess the effects of adversarial attacks.

### Requirements
The following packages are required to run the code:
- `torch` (PyTorch)
- `torchvision`
- `art` (Adversarial Robustness Toolbox)
- `numpy`
- `matplotlib`
- `scikit-image`
- `PIL` (Pillow)
- `datetime`

You can install these dependencies using pip:
```bash
pip install torch torchvision art numpy matplotlib scikit-image Pillow
