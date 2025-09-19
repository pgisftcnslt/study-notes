# Chapter 4: Generative AI Concepts and Azure Capabilities

## What is Generative AI?

Generative AI is a branch of artificial intelligence focused on creating new content—such as text, images, audio, video, or code—based on input prompts or data. Unlike traditional AI that classifies or predicts, generative models generate novel outputs.

---

## How Generative AI Works

- Takes **natural language inputs** or other data.
- Produces outputs in various formats: natural language, images, videos, code.
- Uses deep learning architectures, especially **transformers** and **GANs (Generative Adversarial Networks)**.

---

## Key Components of Generative AI

### Tokenization

- Converts text into tokens (words or word pieces).
- Each token is mapped to a unique numeric ID.
- Enables language models to "read" and process text.

### Embeddings

- Vector representations of tokens capturing semantic relationships.
- Types:
    - **Word Embeddings** for text.
    - **Patch Embeddings** for images (e.g., Vision Transformers).

### Cosine Similarity

- Measures similarity between embedding vectors.
- Helps models understand relatedness between words or concepts.

---

## Neural Architectures in Generative AI

### Recurrent Neural Networks (RNN)

- Process sequences step-by-step to capture context.
- Now largely replaced by transformers due to inefficiency.

### Transformers and Attention

- Use **self-attention** to relate different parts of input data.
- Attention involves **Query, Key, and Value** matrices.
- **Softmax** function computes weighted importance scores.
- Position encoding adds word order information.

---

## Special Tokens and Training Approaches

- **[MASK] Token:** Used in masked language modeling to predict missing words.  
  *Example:* "Vincent Van Gogh is known for [MASK]."
- **Self-Supervised Learning:** Models learn by predicting parts of data without explicit labels.
- **Masked Language Models (MLM):** Bidirectional, understand context (e.g., BERT).
- **Autoregressive Models (ALM):** Unidirectional, generate content (e.g., GPT).

---

## Categories of Generative AI Applications

1. **Ready-to-Use:** Off-the-shelf AI services.
2. **Extendable:** Existing AI augmented with custom data.
3. **Built-from-Foundation:** Custom AI assistants or agents developed from scratch.

---

## Generative AI in Azure

### Azure AI Foundry

- Platform as a Service (PaaS) for enterprise AI.
- Enables building, fine-tuning, and managing AI models.
- Key customization methods:
    1. **Grounding Data:** Connect AI to reliable data sources for factual accuracy.
    2. **Retrieval Augmented Generation (RAG):** Combines retrieval of relevant info with generation.
    3. **Fine-tuning:** Adapt pretrained models with domain-specific data.
    4. **Security & Governance:** Controls access and data privacy.

### Azure AI Foundry Evaluators

Tools to measure AI response quality:

- **Groundedness:** Consistency with retrieved data.
- **Relevance:** Pertinence to user query.
- **Fluency:** Naturalness and readability.
- **Coherence:** Logical flow.
- **Content Safety:** Checks for inappropriate or unsafe outputs.

### Microsoft Copilot Studio

- Low-code environment for building generative AI apps.
- Integrates tightly with Microsoft 365.

---

## Prompting and Engineering

- **Prompts:** Instructions or inputs guiding AI output.
- **System Messages:** Set context and constraints for AI behavior.
- **Prompt Engineering:** Crafting effective prompts to improve AI responses.

---
