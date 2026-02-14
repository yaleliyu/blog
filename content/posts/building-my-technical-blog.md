---
title: "Building a Quant & ML Blog: A Step-by-Step Guide with Hugo and GitHub"
date: 2026-02-14
draft: false
tags: ["Hugo", "GitHub Pages", "Quant", "ML", "Technical Writing"]
---

Welcome to my first post! As I embark on my journey through **Machine Learning (ML)** and **Quantitative Finance**, I realized that the best way to consolidate my learning is to build a professional "digital garden." 

In this post, I will walk you through the exact steps I took to build this site using **Hugo** and **GitHub Pages**.

## Why Hugo for Quant & ML?
For a technical blog, we need three things: **Speed**, **Math support (LaTeX)**, and **Code clarity**. Hugo, a static site generator written in Go, excels at all of them. It allows me to write in Markdown and renders complex equations and backtesting code in milliseconds.

---

## Step 1: Environment Setup
First, I installed the Hugo extended version on my Windows machine. The "extended" version is crucial for processing SCSS/SASS, which many professional themes use.

```bash
# Using Scoop (recommended for Windows)
scoop install hugo-extended
