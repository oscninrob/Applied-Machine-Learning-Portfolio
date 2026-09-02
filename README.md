# Applied Machine Learning Portfolio

**Mathematics Graduate · MSc in Artificial Intelligence · Applied Machine Learning**

A portfolio of practical machine learning and AI projects covering **tabular machine learning, deep learning, NLP, Transformers, computer vision, few-shot learning and explainable AI**.

The projects focus on applying models to real datasets, comparing approaches, evaluating performance and understanding model behaviour.

---

## Featured Projects

### Home Credit Default Risk

End-to-end machine learning project for **credit default prediction** on a highly imbalanced dataset.

**Focus:** Data preprocessing, class imbalance, feature selection, model comparison and threshold optimisation.

**Methods:** Logistic Regression, LightGBM, Optuna, PCA, permutation importance.

**Results:** Final held-out test evaluation achieved **0.8232 accuracy** and **0.2673 F1-score for the minority class**.

→ [View notebook](./notebooks/05_home_credit_default_risk.ipynb)

---

### Toxic Comment Classification with BERT

Multi-label NLP classification using a **pretrained BERT model** to detect different types of toxic comments.

**Focus:** Multilabel classification, class imbalance, NLP evaluation and model behaviour.

**Methods:** BERT, KerasNLP, early stopping, macro F1 and ROC-AUC.

**Results:** **0.69 test macro F1** and **0.9562 mean ROC-AUC** across the toxicity labels.

→ [View notebook](./notebooks/04_bert_toxic_comment_classification.ipynb)

---

### Few-Shot & Zero-Shot Learning

Implementation of **Prototypical Networks** for image classification with limited labelled examples, followed by an attribute-based zero-shot learning experiment.

**Focus:** Metric learning, episodic training, prototype-based classification and learning from limited data.

**Results:**

| Setting      |            Accuracy |
| ------------ | ------------------: |
| 3-way 1-shot | **62.36% ± 10.73%** |
| 3-way 5-shot |  **75.69% ± 7.65%** |
| Zero-shot    |  **57.11% ± 3.89%** |

→ [View notebook](./notebooks/07_few_shot_learning.ipynb)

---

## Machine Learning

### Tree-Based Models

Classification using the **UCI Credit Approval** dataset.

The project covers exploratory data analysis, categorical data handling, decision trees, cross-validation, hyperparameter optimisation and model evaluation.

**Test ROC-AUC:** **0.9016**

→ [View notebook](./notebooks/01_tree_based_models.ipynb)

---

### Semi-Supervised Learning

Experiments investigating machine learning with **limited labelled data**.

The notebook explores clustering, neural networks and semi-supervised classification using techniques including **K-Means and Label Spreading**.

A key experiment compares supervised and semi-supervised learning when only a small subset of the available data is labelled.

→ [View notebook](./notebooks/03_semi_supervised_learning_techniques.ipynb)

---

## Deep Learning & Computer Vision

### Neural Network Classification

Deep learning experiments using multilayer neural networks for classification.

The notebook covers preprocessing, feature standardisation, architecture comparison and evaluation using confusion matrices and ROC curves.

**Test accuracy:** **0.94**
**ROC-AUC:** **0.9774**

→ [View notebook](./notebooks/02_deep_learning_neural_networks.ipynb)

---

### Deep Learning Regularization for Facial Expression Classification

Computer vision project exploring how **architecture design, augmentation and regularisation** affect CNN performance on facial-expression classification.

**Methods:** CNNs, Squeeze-and-Excitation blocks, Swish activation, CutMix, data augmentation and early stopping.

**Validation F1-score:** **0.7146**

→ [View notebook](./notebooks/08_deep_learning_regularization.ipynb)

---

### Explainable AI for Computer Vision

A practical study of methods for explaining predictions made by image-classification models.

**Methods:** Integrated Gradients, Guided Integrated Gradients, Grad-CAM, ShapleyCAM and Shapley-based attribution.

The project combines mathematical foundations with practical computer-vision examples to investigate how different attribution methods identify important image regions.

→ [View notebook](./notebooks/06_explainable_ai_computer_vision.ipynb)

---

## NLP & Transformers

### Transformer Text Classification

Implementation of a **Transformer architecture from scratch** for multi-class Reuters news classification.

The project explores token and positional embeddings, multi-head attention, Transformer blocks, focal loss and class imbalance.

**Original 46-class experiment:**

* Accuracy: **0.79**
* Macro F1: **0.61**

A second experiment grouping rare classes achieved:

* Accuracy: **0.84**
* Macro F1: **0.75**

→ [View notebook](./notebooks/09_transformers_example.ipynb)

---

## Technical Skills

**Programming & Data**

Python · NumPy · pandas · SciPy

**Machine Learning**

scikit-learn · Decision Trees · Logistic Regression · LightGBM · Optuna · Semi-Supervised Learning

**Deep Learning**

TensorFlow · Keras · PyTorch · Neural Networks · CNNs · Transfer Learning · Data Augmentation

**NLP**

BERT · KerasNLP · Transformers · Multilabel Classification · Text Classification

**Computer Vision**

CNNs · Image Classification · Facial Expression Recognition · Few-Shot Learning

**Explainable AI**

Integrated Gradients · Grad-CAM · ShapleyCAM · Feature Attribution

**Visualisation & Evaluation**

matplotlib · seaborn · Cross-Validation · ROC-AUC · F1-score · Confusion Matrices

---

## About

I have a **degree in Mathematics** and an **MSc in Artificial Intelligence**, with a focus on applying mathematical and computational methods to machine learning problems.

My projects span classical machine learning and modern AI techniques, including **gradient boosting, deep learning, BERT, Transformers, few-shot learning, computer vision and explainable AI**.

I am particularly interested in **applied Machine Learning, Data Science and AI engineering roles** where strong quantitative foundations can be combined with practical modelling and experimentation.

---

## Contact

**GitHub:** [oscninrob](https://github.com/oscninrob)

**LinkedIn:** [LinkedIn profile](https://www.linkedin.com/in/oscar-nino-robles/)


**Note**: While this repository and documentation are in English, the inline markdown explanations within the older notebooks are written in Spanish. However, the Python logic, data pipelines, and mathematical models are universally readable.


