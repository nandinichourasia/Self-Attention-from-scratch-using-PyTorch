# Self-Attention from Scratch (PyTorch)

This is a **beginner-friendly implementation of Self-Attention** using PyTorch, coded from scratch without relying on built-in attention modules.

It follows the standard **Key, Query, Value (KQV)** formulation used in Transformers.

---

## 🔎 What is Self-Attention?

Self-Attention is a mechanism that allows each input token (e.g., a word) to **attend to other tokens** in the same sequence in order to capture dependencies and context.

It works by projecting the input into **Query (Q)**, **Key (K)**, and **Value (V)** vectors, and then computing a weighted sum of values based on similarity between queries and keys.

---
