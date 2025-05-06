# -Valid-Mountain-Array-

 Description:
Given an array `arr`, determine if it is a **valid mountain array**.

A mountain array:
- **Must** have at least 3 elements
- **Strictly increases** to a peak (no duplicates)
- **Strictly decreases** after the peak (no plateaus)

The array should **not** have a flat top or be empty.

---

### 🔍 Approach:

1. **Climb Up** ⛰️: Start at the first element and move **up** until the array starts decreasing.
2. **Check Peak** 🔺: Ensure that the peak is not the first or last element.
3. **Climb Down** ⛷️: After the peak, ensure the array strictly decreases.
4. **Edge Cases** 🚫: Handle cases where the array has fewer than 3 elements or any flat sections.

---

### 🧠 Why This Matters:
- Builds a deep understanding of **array traversal** and **edge case handling**
- Great for **interviews** and **problem-solving interviews** where pattern recognition is key.
