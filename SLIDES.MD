---
marp: true
title: Product Documentation Presentation
paginate: true
footer: "Product Docs | 23f2003825@ds.study.iitm.ac.in"
theme: custom
---

<!--
==================================================
CUSTOM THEME
==================================================
-->
<style>
/* Custom theme called 'custom' */
section {
  font-family: 'Segoe UI', sans-serif;
  padding: 40px;
}

h1 {
  color: #0077ff;
  font-weight: 700;
}

h2 {
  color: #333;
}

.custom-box {
  background: #e8f0ff;
  padding: 15px;
  border-left: 6px solid #0077ff;
  border-radius: 8px;
  font-size: 20px;
}
</style>

---

# Product Documentation  
## Using Marp for Engineering Teams

**Email:** 23f2003825@ds.study.iitm.ac.in

---

# Why Marp?

<div class="custom-box">
Marp allows developers to use Markdown to create presentations  
that stay version-controlled and exportable to PDF, PPTX, and HTML.
</div>

---

# Background Image Example

![bg](https://images.unsplash.com/photo-1527443154391-507e9dc6c5cc)

# Our Architecture Overview

---

# Algorithmic Complexity

Here is an example using LaTeX math:

---

## Time Complexity Formula

$$
T(n) = n \log n + 2n + 5
$$

Where:  
- \( n \): Input size  
- \( n \log n \): Dominant term  
- Final complexity:  
  \[
  T(n) = O(n \log n)
  \]

---

# Sample Code Block

```python
def process(items):
    for i in items:      # O(n)
        binary_search(i) # O(log n)
