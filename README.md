# Custom GRU from Scratch in TensorFlow

This repository contains a complete implementation of a Gated Recurrent Unit (GRU) neural network cell from scratch using TensorFlow. No high-level `tf.keras.layers.GRU` abstraction is used. This project demonstrates how to build custom layers, manually define GRU logic, and integrate them into a sequential deep learning model.

---

## 🔍 Overview

Instead of relying on built-in recurrent layers, this project defines:
- A **custom GRUCell** layer handling update/reset gates manually.
- A **multi-layer feed-forward block** as a custom component before the GRU.
- A complete **model pipeline**, from training to evaluation, including visualization of loss and accuracy.

---

## ✨ Features

- ✅ GRU cell logic implemented from scratch
- ✅ Supports variable number of hidden units
- ✅ Easy to plug into any `tf.keras.Sequential` model
- ✅ Includes loss/accuracy plots
- ✅ Includes confusion matrix visualization
- ✅ Ready for future extension (Bidirectional, Dropout, etc.)

---

## 🧰 Requirements

- Python 3.8+
- TensorFlow 2.x
- NumPy
- scikit-learn
- matplotlib

You can install the requirements using:

```bash
pip install -r requirements.txt
