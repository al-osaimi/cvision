# Visual Revision README (Questionss & Answers)

This README is designed as a **final-exam visual revision guide**.

---


## Chapter 1: Introduction to Computer Vision

### ❓ Questions
A digital archiving system scans old manuscripts. Some scanned images lose clarity depending on camera setup.

- What is computer vision?
- How does image formation affect captured images?
- Why is this knowledge important?

<details>
<summary>✅ Answer</summary>

- Computer vision is the field of AI that enables machines to **interpret and understand visual data**.

- Image formation depends on **geometry** (projection) and **photometry** (light interaction), affecting clarity and brightness.

- Understanding image formation improves robustness to **lighting, distortion, and noise**.

**Keywords:** image formation, geometry, photometry, illumination
</details>

---

## Chapter 2: Image Representation & Color Models

### ❓ Questions
A marine robot captures images where object colors vary significantly.

- How are digital images represented?
- Why does RGB struggle here?
- How do other color spaces help?

<details>
<summary>✅ Answer</summary>

- Images are represented as **pixel matrices**, typically H × W × C for color images.

- RGB is sensitive to **illumination changes** and color distortion.

- HSV separates **intensity from color**, improving robustness.

**Keywords:** pixel matrix, RGB, HSV, color space
</details>

---

## Chapter 3: Image Classification & Linear Models

### ❓ Questions
A document analysis system fails when layouts vary.

- What is image classification?
- Why does a linear classifier fail?
- Why are non-linear models better?

<details>
<summary>✅ Answer</summary>

- Image classification assigns a **label** to an image.

- Linear classifiers fail due to **non-linear separability**.

- Non-linear models learn **complex decision boundaries**.

**Keywords:** classification, linear boundary, non-linear
</details>

---

## Chapter 4: Loss Functions & Optimization

### ❓ Questions
A CNN shows unstable loss during training.

- What is a loss function?
- Why does instability occur?
- How do modern optimizers help?

<details>
<summary>✅ Answer</summary>

- A loss function measures **prediction error**.

- Instability comes from **poor learning rates** and **gradient issues**.

- Adam improves stability using **adaptive learning rates**.

**Keywords:** loss function, gradients, Adam
</details>

---

## Chapter 5: CNN Fundamentals

### ❓ Questions
A CNN is used to analyze fabric textures.

- Why CNNs over fully connected networks?
- What do convolutional filters do?
- Why is pooling used?

<details>
<summary>✅ Answer</summary>

- CNNs preserve **spatial structure** and reduce parameters.

- Filters detect **local patterns** like edges.

- Pooling reduces dimensions and improves **translation invariance**.

**Keywords:** convolution, filters, pooling
</details>

---

## Chapter 6: Overfitting in CNNs

### ❓ Questions
A CNN performs poorly on unseen satellite images.

- What does this indicate?
- What causes it?
- How can it be reduced?

<details>
<summary>✅ Answer</summary>

- This indicates **overfitting**.

- Caused by **dataset bias** and limited diversity.

- Regularization improves **generalization**.

**Keywords:** overfitting, regularization, generalization
</details>

---

## Chapter 7: Advanced CNN Architectures

### ❓ Questions
A very deep CNN fails to train effectively.

- What problem occurs?
- How does ResNet help?
- Why are deep models powerful?

<details>
<summary>✅ Answer</summary>

- The **vanishing gradient problem** occurs.

- Residual connections enable **gradient flow**.

- Deep models learn **hierarchical features**.

**Keywords:** ResNet, skip connections, hierarchy
</details>

---

## Chapter 8: LSTM & Sequential Models

### ❓ Questions
A system analyzes sequences of thermal images.

- Why CNNs alone are insufficient?
- What does LSTM add?
- Why is memory important?

<details>
<summary>✅ Answer</summary>

- CNNs lack **temporal modeling**.

- LSTM captures **long-term dependencies**.

- Memory preserves **sequence context**.

**Keywords:** LSTM, temporal dependency, memory
</details>

---

## Chapter 9: Generative Models

### ❓ Questions
An AI system generates synthetic terrain images.

- What is a generative model?
- Why is GAN training difficult?
- Why is diversity important?

<details>
<summary>✅ Answer</summary>

- Generative models learn the **data distribution**.

- GANs suffer from **instability and mode collapse**.

- Diversity improves **generalization**.

**Keywords:** GAN, mode collapse, diversity
</details>

---

## Chapter 10: Detection & Segmentation

### ❓ Questions
A robot needs pixel-level scene understanding.

- What is semantic segmentation?
- Why encoder–decoder models?
- Why pixel accuracy matters?

<details>
<summary>✅ Answer</summary>

- Semantic segmentation assigns a **label to each pixel**.

- Encoders extract features, decoders restore resolution.

- Pixel accuracy ensures **precise localization**.

**Keywords:** segmentation, encoder–decoder
</details>

---

## Chapter 11: Feature Visualization

### ❓ Questions
A researcher wants to interpret CNN decisions.

- What is feature visualization?
- What do early vs deep layers learn?
- Why is interpretability important?

<details>
<summary>✅ Answer</summary>

- Feature visualization reveals **internal representations**.

- Early layers learn edges; deep layers learn semantics.

- Interpretability improves **trust and debugging**.

**Keywords:** interpretability, feature hierarchy
</details>

---

## Chapter 12: Video & Scene Understanding

### ❓ Questions
A warehouse robot reasons about object interactions.

- What is a scene graph?
- Why are relationships important?
- How do GNNs help?

<details>
<summary>✅ Answer</summary>

- Scene graphs represent objects and **relationships**.

- Relationships provide **contextual understanding**.

- GNNs enable **relational reasoning**.

**Keywords:** scene graph, GNN, relationships
</details>

