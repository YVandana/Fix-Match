# Fix-Match

This repository contains the implementation of Fix-Match, a semi-supervised learning model with consistency regularization techniques. The project aims to investigate the effects of optimization techniques, specifically SGD with Momentum and Nesterov Accelerated Gradient, compared to SGD and AdaGrad regularization techniques when applied to the Fix-Match model on the CIFAR-10 and CIFAR-100 datasets.

## Introduction
Fix-Match is a powerful approach in semi-supervised learning that utilizes both labeled and unlabeled data to train machine learning models. Traditional supervised learning techniques heavily rely on large annotated and labeled datasets, which can be expensive and prone to human errors. In contrast, semi-supervised learning leverages the abundance of unlabeled data to improve model performance.

## Key Features
- Implementation of Fix-Match semi-supervised learning model
- Comparison of optimization techniques: SGD with Momentum, Nesterov Accelerated Gradient, SGD, and AdaGrad
- Evaluation on CIFAR-10 and CIFAR-100 datasets
- Consistency regularization techniques for improving model performance

## Related Work
The project builds upon existing literature and methodologies in the field of semi-supervised learning. Some notable contributions include:

- The ℿ-Model with Temporal Ensembling proposed by Laine, S. and Aila, T.
- Pseudo Labelling method proposed by Lee, D.H. et al.
- Fix-Match, combining concepts from the ℿ-Model, Pseudo Labelling, and Consistency Regularization, proposed by Sohn, K. et al.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/YVandana/Fix-Match.git
   cd Fix-Match
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the experiments and evaluate the model on the CIFAR-10 and CIFAR-100 datasets.

## Usage
1. Prepare the dataset:
   - Download the CIFAR-10 and CIFAR-100 datasets.
   - Preprocess the datasets as per the instructions in the code.
  
2. Configure the model and optimization techniques:
   - Modify the model architecture and hyperparameters in the code to suit your requirements.
   - Choose the desired optimization techniques (SGD with Momentum, Nesterov Accelerated Gradient, SGD, or AdaGrad) by uncommenting the relevant code sections.
   - Set the desired consistency regularization techniques.

3. Train the model:
   - Run the training script to train the Fix-Match model on the prepared dataset.
   ```bash
   python train.py
   ```

4. Evaluate the model:
   - Run the evaluation script to assess the performance of the trained model on the test dataset.
   ```bash
   python evaluate.py
   ```

## Results
The project aims to analyze the effects of different optimization techniques on the Fix-Match model's performance. The evaluation results on the CIFAR-10 and CIFAR-100 datasets will provide insights into the effectiveness of these techniques in improving model accuracy and robustness.

## Conclusion
The Fix-Match project explores the use of Fix-Match, a semi-supervised learning model, with various optimization techniques. By leveraging both labeled and unlabeled data, the model aims to achieve higher accuracy and overcome the limitations of traditional supervised learning. The results and findings of this project contribute to the understanding of semi-supervised learning and optimization strategies in the context of deep learning.

## Contributors
- Vandana Yalla
- Supervisor: Niki Maria Foteinopoulou

For more details, please refer to the [GitHub repository](https://github.com/YVandana/Fix-Match).
