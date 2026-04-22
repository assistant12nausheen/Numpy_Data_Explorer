# 🔢 NumPy Data Explorer

> **Project - 1** | SyntecxHub Internship Program  
> Exploring NumPy fundamentals through hands-on data analysis and performance benchmarking.

---

## 📌 About the Project

NumPy Data Explorer is a beginner-friendly Python project built during my internship at **SyntecxHub**. It demonstrates core NumPy concepts including array manipulation, mathematical operations, reshaping, broadcasting, file I/O, and performance comparison with standard Python lists.

This project serves as a practical introduction to scientific computing in Python using the NumPy library.

---

## 🎯 Topics Covered

| # | Topic | Description |
|---|-------|-------------|
| 1 | **Array Creation, Indexing & Slicing** | Creating 1D/2D/3D arrays, accessing elements, slicing ranges |
| 2 | **Mathematical & Statistical Operations** | Sum, mean, std deviation, axis-wise operations |
| 3 | **Reshaping & Broadcasting** | Changing array shapes, broadcasting across dimensions |
| 4 | **Save & Load Arrays** | Persisting arrays with `.npy`, `.npz`, and `.csv` formats |
| 5 | **NumPy vs Python Lists** | Benchmarking speed and memory usage |

---

## 📁 Project Structure

```
numpy-data-explorer/
│
├── numpy_data_explorer.ipynb   # Main Jupyter Notebook with all code
├── sales_data.npy              # Sample saved NumPy array
├── both_arrays.npz             # Sample multi-array save file
├── sales.csv                   # Sample CSV export
├── requirements.txt            # Python dependencies
└── README.md                   # Project documentation
```

---

## 🛠️ Technologies Used

- **Python 3.x** — Programming language
- **NumPy** — Core library for numerical computing
- **Jupyter Notebook** — Interactive coding environment
- **Git & GitHub** — Version control and project hosting

---

## 📊 Key Learnings & Highlights

### Array Creation
```python
import numpy as np

arr = np.array([1, 2, 3, 4, 5])
matrix = np.random.randint(1, 100, size=(4, 4))
```

### Performance Benchmark Result
```
Python list time  : 0.1523 seconds
NumPy array time  : 0.0031 seconds
NumPy is ~49x faster!
```

### Save & Load
```python
np.save('data.npy', array)          # Save
loaded = np.load('data.npy')        # Load
```

---

## 📸 Sample Output

```
1D array: [1 2 3 4 5]
Column sums (axis=0): [120 150 180]
Row means  (axis=1): [20. 50. 80.]
NumPy is 49.3x faster than Python lists!
```

---

## 📦 requirements.txt

```
numpy
jupyter
```

To generate this file yourself:
```bash
pip freeze > requirements.txt
```

---

## 🧠 What I Learned

- How NumPy arrays differ from Python lists in terms of speed and memory
- How to perform vectorized operations without using loops
- The concept of broadcasting and how it simplifies computation
- How to persist and reload data using NumPy's file formats
- Real-world performance differences between NumPy and native Python

---

## 🙌 Acknowledgements

- [SyntecxHub](https://syntecxhub.com) — for providing this internship opportunity
- [NumPy Official Documentation](https://numpy.org/doc/) — reference and learning material
- [freeCodeCamp NumPy Tutorial](https://www.youtube.com/watch?v=QUT1VHiLmmI) — video resource

---

## 👤 Author

Nausheen Suhana 
Intern at SyntecxHub  
📧 nausheensuhana@gmail.com 
🔗 [LinkedIn](https://linkedin.com/in/Nausheen Suhana) | [GitHub](https://github.com/assistant12nausheen)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*Made with dedication during my first internship experience 🚀*
