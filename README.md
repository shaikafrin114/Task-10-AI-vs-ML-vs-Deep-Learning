# Task-10-AI-vs-ML-vs-Deep-Learning

## Project Overview
This project explains the differences and relationship between Artificial Intelligence (AI), Machine Learning (ML), and Deep Learning (DL). It includes definitions, a comparison table, real-world examples, and simple Python demonstrations.

## Objectives
- Understand AI as the broad field of intelligent computer systems.
- Explain ML as a subset of AI that learns patterns from data.
- Explain DL as a subset of ML that uses multilayer neural networks.
- Compare their features and applications.
- Demonstrate the concepts with Python.

## Concepts

### Artificial Intelligence (AI)
Artificial Intelligence is the field of building systems that perform tasks that normally require human intelligence, such as reasoning, planning, and decision-making.

**Examples:** Rule-based expert systems, game-playing systems, and virtual assistants.

### Machine Learning (ML)
Machine Learning is a subset of AI that enables computers to learn patterns from data and make predictions or decisions.

**Examples:** Email spam detection, product recommendations, and house-price prediction.

### Deep Learning (DL)
Deep Learning is a subset of ML that uses neural networks with multiple layers to learn complex patterns.

**Examples:** Facial recognition, speech recognition, and image classification.

## Relationship Between AI, ML, and DL

```text
Artificial Intelligence (AI)
└── Machine Learning (ML)
    └── Deep Learning (DL)
```

AI is the broadest field. ML is one approach within AI, and DL is a specialized approach within ML.

## Comparison Table

| Feature | AI | ML | Deep Learning |
|---|---|---|---|
| Meaning | Systems performing intelligent tasks | Learns patterns from data | Uses multilayer neural networks |
| Scope | Broadest field | Subset of AI | Subset of ML |
| Methods | Rules, search, reasoning, and learning | Statistical methods and learning algorithms | Deep neural networks |
| Data needs | Depends on the method | Usually requires training data | Often benefits from large datasets |
| Computing needs | Depends on the application | Low to high | Often high |
| Example | Rule-based expert system | Spam detection | Face recognition |

## Real-World Applications

- **AI:** Rule-based expert systems, planning, and game-playing.
- **ML:** Spam filtering, recommendation systems, and price prediction.
- **Deep Learning:** Image classification, speech recognition, and object detection.

Some applications combine AI, ML, and deep learning techniques.

## Python Demonstration

The following program prints the definitions and relationship:

```python
ai = "AI is the broad field of intelligent computer systems."
ml = "ML learns patterns from data."
dl = "Deep Learning uses multilayer neural networks."

print("AI vs ML vs Deep Learning")
print("-" * 35)
print("\nArtificial Intelligence:")
print(ai)
print("\nMachine Learning:")
print(ml)
print("\nDeep Learning:")
print(dl)
print("\nRelationship:")
print("Deep Learning is a subset of Machine Learning.")
print("Machine Learning is a subset of Artificial Intelligence.")
```

### Optional Machine Learning Example

This example trains a small decision-tree classifier using sample data. No external dataset is required.

```python
from sklearn.tree import DecisionTreeClassifier

X = [[1], [2], [3], [4]]
y = [0, 0, 1, 1]

model = DecisionTreeClassifier(random_state=0)
model.fit(X, y)

prediction = model.predict([[3]])
print("Predicted class:", prediction[0])
```

To run the optional example, install scikit-learn if needed:

```bash
python -m pip install scikit-learn
```

## Tools Used
- Python
- Jupyter Notebook
- Markdown
- Scikit-learn (optional demonstration)

## Dataset
No external dataset is required. The optional ML demonstration uses a small sample dataset defined directly in the code.

## How to Run
1. Install Python.
2. Install Jupyter Notebook with `python -m pip install notebook`.
3. Start Jupyter Notebook with `jupyter notebook`.
4. Open `AI_vs_ML_vs_Deep_Learning.ipynb` and run the cells in order.
5. For the optional ML example, install scikit-learn with `python -m pip install scikit-learn`.

## Conclusion
AI, ML, and Deep Learning are related fields. AI focuses on intelligent behavior, ML learns patterns from data, and DL uses multilayer neural networks to learn complex patterns. They are used in many applications, including chatbots, recommendation systems, and image recognition.
