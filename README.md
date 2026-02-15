# 🧠 NumPy Core Training — Level 1 (Foundations for AI)

## Training Philosophy

This isn't about "finishing the course fast" — it's about **extracting the core skills** that separate AI engineers who struggle with NumPy from those who wield it naturally.

The goal: **Build real AI-engineer muscle through deliberate practice**, not just course completion.

### What Makes This Different

- **Think in shapes first** — Before running code, predict the output shape
- **No more guessing** — Understand `axis` parameter intuitively
- **Stop writing loops** — Learn to think vectorized naturally
- **Avoid silent bugs** — Master views vs copies to prevent ML pipeline disasters

---

## 📚 Table of Contents

### Practice Notebooks

1. **[Array Creation & Inspection](notebooks/01_create_and_inspect_arrays.ipynb)**  
   *Mental Model Training* — Build shape intuition from day one

2. **[Indexing & Subsetting](notebooks/02_indexing_and_subsetting.ipynb)**  
   *Data Control* — Select, slice, and filter like a pro

3. **[Vectorized Operations](notebooks/03_vectorized_operations.ipynb)**  
   *Stop Thinking in Loops* — Learn the NumPy way

4. **[Matrix Arithmetic](notebooks/04_matrix_arithmetic.ipynb)**  
   *2D Arithmetic & Matrix Thinking* — Neural networks are just chained matrix multiplications

5. **[Basic Statistics](notebooks/05_basic_statistics.ipynb)**  
   *Data Intuition* — Every ML pipeline starts here

6. **[Views vs Copies](notebooks/06_views_vs_copies.ipynb)**  
   *Understanding Side Effects* — Prevent silent bugs in production

---

## 🎯 Minimum Competency Goals

By the end of Level 1, you should be able to:

✅ **Think in shapes** — Look at code and instantly know the output shape without running it

✅ **Predict before running** — Train your mental model by predicting outputs, then verifying

✅ **Use axis correctly** — No more trial-and-error with `axis=0` vs `axis=1`

✅ **Avoid loops naturally** — Vectorized thinking becomes your default mode

✅ **Understand memory behavior** — Know when you're working with views vs copies

✅ **Debug shape mismatches** — Read error messages and fix them instantly

---

## 🚀 Setup Instructions

### Prerequisites

- Python 3.7 or higher
- pip (Python package manager)

### Installation

1. **Clone this repository:**
   ```bash
   git clone https://github.com/liya-oz/numpy-core.git
   cd numpy-core
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter:**
   ```bash
   jupyter notebook
   ```

4. **Start with notebook 01** and work through them in order

### Alternative: Using Virtual Environment (Recommended)

```bash
# Create virtual environment
python -m venv venv

# Activate it
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```

---

## 💡 How to Use These Notebooks

1. **Don't rush** — Speed is not the goal, skill-building is
2. **Predict first** — For every "🧠 Predict the Output" challenge, write your prediction before running
3. **Try before checking** — Attempt practice tasks before looking at solutions
4. **Experiment** — Modify the examples, break things, see what happens
5. **Come back** — These are reference materials. Return when you need to refresh

---

## 🤝 Contributing

Found a typo? Have a suggestion for improvement? Feel free to open an issue or submit a pull request.

---

## 📄 License

This project is open source and available under the MIT License.

---

**Remember:** The goal is not to memorize syntax — it's to build intuition. Take your time, experiment, and develop your mental model of how NumPy works. 🚀