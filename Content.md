# 🧠 Deep Learning: Transformers & Large Language Models

>Juan Irving Vásquez, Instituto Politécnico Nacional (IPN),
Centro de Innovación y Desarrollo Tecnológico en Cómputo (CIDETEC)

This course provides a comprehensive journey from the foundations of neural architectures to the cutting-edge world of Generative AI and Large Language Models (LLMs).

---

## 1. Introduction
* **1.1 The Evolution of AI:** Motivation and the rapid advances in Deep Learning.
* **1.2 The Shift to Attention:** Why Transformers replaced RNNs and LSTMs.

---

## 2. Neural Network Foundations
*A review of the essential building blocks required to understand modern architectures.*
* **2.1 Fully Connected Networks:** Multi-layer Perceptrons (MLP).
* **2.2 Backpropagation:** The chain rule and gradient flow.
* **2.3 Optimization:** SGD, Adam, and weight decay.
* **2.4 Convolutional Neural Networks (CNNs):** Spatial feature extraction.
* **2.5 Residual Networks (ResNet):** Skip connections and training stability.
* **2.6 Recurrent Neural Networks (RNNs) & LSTMs:** Sequence modeling basics.
* **2.7 Sequence-to-Sequence (Seq2Seq):** Fundamentals of mapping input sequences to outputs.
* **2.8 The Encoder-Decoder Framework:** Structural breakdown.
---

## 3. The Transformer Architecture
*The core of modern NLP and Computer Vision.*

* **3.3 Data Representation:**
    * **3.3.1 Word Embeddings:** Vectorizing semantics.
    * **3.3.2 Positional Encoding:** Injecting order into non-sequential processing.
* **3.4 The Attention Mechanism:**
    * **3.4.1 Cross-Attention:** Source and target interaction.
    * **3.4.2 Self-Attention:** Understanding context within a single sequence.
    * **3.4.3 Multi-Head Attention:** Learning parallel representation subspaces.
* **3.5 Normalization & Stability:** Residual connections and Layer Normalization.

---

## 4. Encoder-Only Models (BERT)
* **4.1 Bidirectional Representations:** Learning context from both directions.
* **4.2 Training Objectives:** Masked Language Modeling (MLM) and Next Sentence Prediction (NSP).

## 5. Vision Transformers (ViT)
* **5.1 Images as Patches:** Applying Transformer blocks to 2D data.
* **5.2 Global vs. Local context:** Comparison with CNNs.

## 6. Decoder-Only Models (GPT)
* **6.1 Generative Pre-trained Transformers:** Autoregressive language modeling.
* **6.2 Scaling Laws:** The impact of parameters and data size.

---

## 7. Training Methodologies
* **7.1 Pre-training:** Self-supervised learning at scale.
* **7.2 Fine-tuning:** Adapting models for specific downstream tasks.
* **7.3 Instruction Tuning:** Aligning models to follow human commands (RLHF basics).