# PRODIGY_GA_Task3 — Markov Chain Text Generator

## 📌 Task Overview

This project implements a **Markov Chain-based Text Generator** as part of the **Generative AI Internship at Prodigy InfoTech**.

The model learns statistical relationships between consecutive words or characters in a training corpus and uses those learned transitions to generate new text.

Unlike modern Transformer-based language models, this project uses a lightweight statistical approach, making it possible to run entirely on a CPU without requiring a GPU.

---

## 🎯 Objective

The objective of this task is to implement a text generation system using **Markov Chains**.

The model learns:

> Given the previous N tokens, what tokens are likely to come next?

The value of `N` is controlled using the **Markov order**.

---

## ✨ Features

- 🔤 Word-level text generation
- 🔡 Character-level text generation
- ⚙️ Configurable Markov order
- 🎲 Randomized text generation
- 🔁 Reproducible demonstrations using a fixed random seed
- 📊 Comparison of different Markov orders
- 📄 Support for custom text corpora
- 💻 CPU-only implementation
- 🚀 No deep-learning framework or GPU required

---

## 🧠 How It Works

A Markov Chain models a sequence by using a fixed number of previous tokens as the current state.

For example, with an order of `2`:

```text
Previous words:
"machine learning"

Possible next word:
"systems"
