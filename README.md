# Neural Network & ML Labs

> **Historical hands-on machine-learning notebooks**
>
> A preserved learning record covering classical ML, neural-network fundamentals, computer vision, NLP and early transformer experiments.

This is intentionally **not** presented as one polished ML product. The notebooks were written while learning and testing ideas directly, and keeping that progression visible is more useful than rewriting them into a synthetic demo years later.

## What is here

### Foundations / classical ML

- `Linear_Regression.ipynb`
- `Logistic_Regression.ipynb`
- `Decision_Tree.ipynb`
- `SVM.ipynb`
- `GradientDescent.ipynb`
- `Backpropagation.ipynb`
- `ClassificationIris.ipynb`

### Neural networks / computer vision

- `ClassificationCIFAR.ipynb`
- `ObjectDetection.ipynb`
- `TFobject_detection.ipynb`
- `detecto.ipynb`

These notebooks include experiments around model training/inference, image classification and object-detection workflows rather than only consuming prebuilt AI APIs.

### NLP / language-model experiments

- `sentiment.ipynb`
- `Sentiments+Scrap.ipynb`
- `HuggingFaceGPT2.ipynb`

### Data / supporting work

- `NumPy.ipynb`
- `Pandas.ipynb`
- `SkLearn_datasets.ipynb`
- `Poker.ipynb`

## Why I keep this public

My current AI work is mostly about agentic software-engineering systems, which can make it easy to assume that my relationship with ML started with LLM chat interfaces.

It did not.

These notebooks preserve an earlier layer of the stack: training, gradients/backpropagation, model evaluation, computer vision and direct experimentation with neural-network tooling.

The later [MLFramework](https://github.com/SzymonZyrek/MLFramework) repository moves one level outward from individual experiments toward reusable model backends, dataset configuration, model packaging and orchestration.

A rough progression is:

```text
direct ML / neural-network experiments
                ↓
reusable model-training infrastructure
                ↓
workflow / orchestration concerns
                ↓
agentic engineering systems
```

## Status

Historical learning repository.

Some notebooks reflect older library versions, Colab environments and exploratory code. They are preserved as a record of the work rather than maintained as current tutorials.
