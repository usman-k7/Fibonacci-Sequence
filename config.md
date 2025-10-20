# ⚙️ Fibonacci Sequence Configuration Guide

This file explains the adjustable parameters and options available in the Fibonacci Sequence Generator project.

---

## 🔢 Configuration Parameters

| Parameter | Description | Default Value |
|------------|--------------|----------------|
| `num_terms` | Number of Fibonacci terms to generate | `10` |
| `method` | Choose generation method: `iterative` or `recursive` | `iterative` |
| `show_sum` | Display the total sum of generated Fibonacci numbers | `True` |
| `show_ratio` | Show ratio of last two Fibonacci numbers (approx. Golden Ratio) | `False` |
| `save_output` | Save the generated sequence to a `.txt` file | `False` |

---

## 🧮 Example Configuration

```python
config = {
    "num_terms": 15,
    "method": "recursive",
    "show_sum": True,
    "show_ratio": True,
    "save_output": False
}
