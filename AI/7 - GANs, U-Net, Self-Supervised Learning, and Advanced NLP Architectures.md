# Chapter 7: GANs, U-Net, Self-Supervised Learning, and Advanced NLP Architectures

## Generative Adversarial Networks (GANs)

- **Architecture:** Consists of two neural networks competing against each other:
    - **Generator:** Creates synthetic data (e.g., images).
    - **Discriminator (Judge):** Evaluates if data is real or fake.
- **Use case:** Widely used in image generation tasks.

## U-Net Architecture

- Designed primarily for image segmentation.
- Consists of an encoder (contracting path) and decoder (expanding path).
- Captures both context and precise localization for pixel-level classification.

---

## History of NLP Architectures

1. **N-grams:** Statistical models based on contiguous sequences of n words.
2. **Recurrent Neural Networks (RNNs):** Process sequences step-by-step, capturing context over time.
3. **Long Short-Term Memory (LSTM):** Special type of RNN designed to remember longer sequences effectively.
4. **Transformers:** Use self-attention to process all words in parallel, enabling better scalability and context understanding.

---

## Self-Supervised Learning

- A subset of unsupervised learning where the model learns to predict part of the input from other parts.
- Provides a defined task to guide learning without labeled data.
- Highly effective for tasks such as language modeling and prediction.

---

## Masked Language Model (MLM)

- **Goal:** Predict a missing token based on surrounding tokens.
- **Reading:** Bidirectional (looks at context from both sides).
- **Example:** "Vincent Van Gogh is a painter known for [MASK]."
- **Common Model:** BERT (Bidirectional Encoder Representations from Transformers).
- **Use Case:** Understanding tasks such as classification, named entity recognition.

---

## Autoregressive Language Model (ALM)

- **Goal:** Predict the next token based on previous tokens.
- **Reading:** Unidirectional (left-to-right).
- **Common Model:** GPT (Generative Pre-trained Transformer).
- **Use Case:** Text generation, chatbots, and creative writing.

---
