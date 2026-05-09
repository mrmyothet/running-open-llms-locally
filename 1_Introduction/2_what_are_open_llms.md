# 2. What Are Open LLMs? - Summary Notes

## Core Definition

An LLM is mainly defined by two parts:

1. **Training code / algorithm**
2. **Model weights (parameters)** produced by training

In practice, when people say a model is "open," they usually mean the **weights are available**, not necessarily the training code.

## How LLMs Work (Quick Mental Model)

- Input text is split into **tokens** (whole words or parts of words).
- Each token gets a numeric **token ID**.
- Token IDs are processed by a large neural network.
- Connections in the network have **weights/parameters**.
- The model predicts multiple next-token candidates with probabilities.
- One token is selected, then the process repeats token by token.

## Why Parameters Matter

- Parameters are the learned result of training.
- They determine model behavior for a given input.
- "600B-parameter model" means the model has a very large number of learned weights.

## Open vs Closed Models

### Open LLMs

- Model weights are released publicly (under a license).
- You can download and run them locally (if license permits).

### Closed / Proprietary Models (for example, ChatGPT models)

- Weights are not available.
- Training code is not available.
- You can only access them via app or API, not by running locally.

## License Reminder

Open model weights are still governed by licenses, which define how you can use them.

## 1-Minute Explanation

An open LLM is usually open because its trained weights are released, not because the original training code is public.
LLMs work by turning text into tokens, scoring possible next tokens using learned parameters, and generating output token by token.
If weights are available, you can run the model locally; if they are not, you can only use the provider's app or API.
To run models locally, you do **not** need training code. You mainly need access to the released **model weights** and compatible tooling.

## Memory Hook

**Open LLM usually means open weights, not open training pipeline.**
