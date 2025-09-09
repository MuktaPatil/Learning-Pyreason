## Causal Chatbot with PyReason Simulation
### 📌 Overview

This project is a simple rule-based causal chatbot that simulates reasoning using PyReason-style rules, along with support from PyTorch and Numba for demonstration of ML integration and performance optimization.

The chatbot can handle natural questions like “what if it rains?” and respond with outcomes based on defined causal rules. While not a full implementation of PyReason, it shows how natural language queries can be parsed, converted to a reasoning-friendly format, and matched against rules.

### 🛠️ Technologies Used

* Python: Core chatbot logic

* PyReason (simulated): Rule-based causal reasoning

* PyTorch: Simple neural network for outcome prediction

* Numba: JIT compilation for fast array operations

* Pandas, NumPy, scikit-learn, statsmodels, networkx, matplotlib, seaborn: Installed for potential extensions


### 🚀 Features

* Parse natural “what if” questions into a structured dictionary

* Convert parsed queries into a PyReason-style format

* Match against pre-defined causal rules (causal_rules.pyreason)

* Simple neural network demo for probabilistic outcomes

* Optimized array operations using Numba

### 🧪 Test Questions

Here are some example queries you can try in the chatbot:

```
You: what if it rains
Chatbot: If rain, then the ground becomes wet.

You: what if not watering plants
Chatbot: If not watering plants, then plants may wither.

You: what if not doing homework
Chatbot: If not doing homework, then you might get in trouble.

You: what if sleep late
Chatbot: If sleep late, then you will be tired.

You: what if eat healthy
Chatbot: If eat healthy, then you gain energy.

```
To exit:

```
You: quit
Chatbot: Goodbye!
```


⚠️ Note: The parser is currently literal, so phrasing must match the rules. Example: “what if not watering plants” will work, but “what if I don’t water my plants” won’t yet.

### 🔮 Next Steps

To take this project to the next level:

* Natural Language Expansion: Add smarter parsing (e.g., synonym handling, negation detection, lemmatization).

* Dynamic Rule Loading: Instead of hardcoding rules in Python, load and evaluate them directly from causal_rules.pyreason.

* Integration with Real PyReason: Run actual PyReason inference instead of simulated reasoning.

I* nteractive Web App: Deploy the chatbot with Streamlit or Flask for easier use.

* Learning Extension: Connect ML models to estimate causal effects when no explicit rule exists.

### 🎯 Why PyReason?

I started learning PyReason because it allows combining logical rules with probabilistic reasoning, a very powerful idea for building explainable AI systems. This project is my first step toward experimenting with causal inference + natural language understanding.

### 💡 Why This Matters

This project reflects my curiosity in causal inference, reasoning systems, and explainable AI. It shows how I explore new tools like PyReason, combine them with ML, and build practical prototypes. Including this repo in my application demonstrates initiative, technical ability, and interest in AI systems beyond coursework.
