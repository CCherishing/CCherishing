# Phase 1: Java Execution & Core Algorithmic Patterns

This module contains heavily optimized Java implementations focused on strict time and space execution bounds, serving as the foundational prep for quantitative systems engineering and my upcoming Amazon backend internship.

## 📂 Directory Structure

* ****: Implementations of sliding windows, heaps, and monotonic stacks.
* ****: Manual memory management and graph traversal from *Algorithms Part I & II*.

## ⏱️ Empirical Performance Benchmarks

| Data Structure / Pattern | Time Bound | Space Bound | Empirical Execution (1M inputs) |
| :--- | :--- | :--- | :--- |
| **Custom Priority Queue** | (\log N)$ | (N)$ | ~45ms |
| **KD-Tree**| (\log N)$ | (N)$ | ~58ms |
| **Monotonic Stack** | (N)$ | (N)$ | ~22ms |
| **Sliding Window Max** | (N)$ | (K)$ | ~28ms |
