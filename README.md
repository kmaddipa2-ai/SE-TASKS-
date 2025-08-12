## Quadratic Weather Modeling (TASK -3)

This project demonstrates how to model temperature variation over time using a **quadratic equation** and visualize it with **Matplotlib**.

### 📌 How It Works

* The program reads a CSV file containing multiple sets of coefficients `a`, `b`, and `c`.
* For each set, it computes temperatures at times `t = 0` to `10` using:

  ```
  Temperature = a * t² + b * t + c
  ```
* It then plots all temperature curves on a single graph.

### 📂 Files

* **`abc_values.csv`** — CSV file containing the quadratic coefficients.
* **`main.py`** — Python script to read the CSV and plot the results.
* **`README.md`** — Documentation for GitHub.

### 🗒 CSV Format

The CSV should have headers:

```
a,b,c
0.25,1.8,21
-0.3,4.0,15
0.5,-1.5,28
-0.2,2.2,18
0.1,-0.5,25
```

### ▶️ How to Run

1. Install dependencies:

   ```bash
   pip install pandas matplotlib
   ```
2. Place `abc_values.csv` in the same folder as `main.py`.
3. Run:

   ```bash
   python main.py
   ```
4. The plot will display temperature variation for all coefficient sets.

### 📊 Example Output

You will see a graph with **multiple curves**, each representing a different set of quadratic coefficients.

