---
🛠️ **1. Installation and Setup**
- Installing NumPy via pip or conda.
- Importing: `import numpy as np`
---

🔢 **2. Array Creation**
  **I. Arrays with Predefined Values**
  - `np.array()`: Creates an array from lists, tuples, or other sequences.
  - `np.zeros()`: Creates an array filled with zeros.
  - `np.ones()`: Creates an array filled with ones.
  - `np.full()`: Creates an array filled with a specified value.
  - `np.eye()`: Creates an identity matrix.
  - `np.diag()`: Creates a diagonal array.
  ---

  **II. Arrays with Sequences**
  - `np.arange()`: Creates an array with evenly spaced values (similar to range).
  - `np.linspace()`: Creates an array with evenly spaced values, including endpoints.
  - `np.logspace()`: Creates an array with logarithmically spaced values.
  ---

  **III. Arrays from Random Numbers**
  - `np.random.rand()`: Creates random floats from uniform distribution [0, 1).
  - `np.random.randn()`: Creates random samples from standard normal distribution.
  - `np.random.randint()`: Creates random integers within a specified range.
  - `np.random.uniform()`: Creates random floats from uniform distribution over an interval.
  - `np.random.normal()`: Creates random samples from normal distribution with mean and std.
  ---

📏 **3. Array Attributes**
- `shape`: Returns the dimensions of the array.
- `dtype`: Returns the data type of array elements.
- `ndim`: Returns the number of dimensions.
- `size`: Returns the total number of elements.
- `itemsize`: Returns the size in bytes of each element.
---

✂️ **4. Array Indexing and Slicing**
  **I. Basic Slicing**
  - `array[start:stop:step]`: Slices arrays with start (inclusive), stop (exclusive), and step.
  ---

  **II. Advanced Indexing**
  - Integer indexing: Uses lists or arrays of indices to select elements.
  - Boolean indexing: Uses boolean masks to filter elements.
---

📡 **5. Broadcasting**
- Automatic alignment of arrays with different shapes for element-wise operations (no explicit functions, but core concept for efficient computations).
---

➕ **6. NumPy Array Mathematical Functions**
  **I. Arithmetic Operations**
  - Basic operators: `+`, `-`, `*`, `/`, `//`, `%`, `**`.
  - `np.add()`, `np.subtract()`, `np.multiply()`, `np.divide()`, `np.floor_divide()`, `np.mod()`, `np.power()`: Element-wise arithmetic.
  - `np.abs()`: Computes absolute values.
  ---

  **II. Trigonometric Functions**
  - `np.sin()`, `np.cos()`, `np.tan()`: Basic trig functions.
  - `np.arcsin()`, `np.arccos()`, `np.arctan()`: Inverse trig functions.
  ---

  **III. Exponential and Logarithmic Functions**
  - `np.exp()`: Computes exponential (e^x).
  - `np.log()`, `np.log10()`, `np.log2()`: Natural, base-10, and base-2 logarithms.
  ---

  **IV. Rounding Functions**
  - `np.round()`: Rounds to nearest integer.
  - `np.floor()`, `np.ceil()`: Floor and ceiling functions.
  ---

📊 **7. Aggregation and Statistical Functions**
- `np.sum()`: Computes sum along axes.
- `np.mean()`: Computes mean.
- `np.median()`: Computes median.
- `np.std()`: Computes standard deviation.
- `np.var()`: Computes variance.
- `np.min()`, `np.max()`: Finds minimum and maximum.
- `np.argmin()`, `np.argmax()`: Indices of min and max.
- `np.prod()`: Computes product.
- `np.cumsum()`, `np.cumprod()`: Cumulative sum and product.
- `np.percentile()`: Computes percentiles.
---

🔄 **8. Array Manipulation Functions**
  **I. Changing Shape**
  - `reshape()`: Reshapes array without changing data.
  - `ravel()`: Flattens to 1D (view if possible).
  - `flatten()`: Flattens to 1D (always copy).
  - `transpose()`: Transposes axes.
  - `swapaxes()`: Swaps two axes.
  ---

  **II. Joining Arrays**
  - `concatenate()`: Joins along existing axis.
  - `vstack()`: Stacks vertically (row-wise).
  - `hstack()`: Stacks horizontally (column-wise).
  - `stack()`: Stacks along new axis.
  ---

  **III. Splitting Arrays**
  - `split()`: Splits into sub-arrays along axis.
  - `hsplit()`: Splits horizontally.
  - `vsplit()`: Splits vertically.
  ---

  **IV. Adding/Removing Elements**
  - `append()`: Appends values to end.
  - `insert()`: Inserts at specific positions.
  - `delete()`: Deletes elements.
  ---

🔢 **9. Linear Algebra Functions**
- `np.dot()`: Dot product (for 1D) or matrix multiplication (for 2D).
- `np.matmul()`: Matrix multiplication (preferred for arrays in NumPy 2.x).
- `np.linalg.inv()`: Computes matrix inverse.
- `np.linalg.det()`: Computes determinant.
- `np.linalg.eig()`: Computes eigenvalues and eigenvectors.
- `np.linalg.svd()`: Singular value decomposition.
- `np.linalg.norm()`: Computes vector or matrix norms.
---

🎲 **10. Random Number Generation Functions**
  **I. Basic Random Number Generation**
  - `np.random.rand()`: Uniform [0,1).
  - `np.random.randn()`: Standard normal.
  - `np.random.randint()`: Random integers.
  - `np.random.uniform()`: Uniform over interval.
  ---

  **II. Permutations**
  - `np.random.shuffle()`: Shuffles in-place.
  - `np.random.permutation()`: Returns permuted array.
  ---

  **III. Distributions**
  - `np.random.normal()`: Normal with mean/std.
  - `np.random.binomial()`: Binomial.
  - `np.random.poisson()`: Poisson.
  ---

  **IV. Random Seed**
  - `np.random.seed()`: Sets seed for reproducibility.
  ---

🔍 **11. Searching and Sorting Functions**
  **I. Sorting Functions**
  - `np.sort()`: Returns sorted copy.
  - `np.argsort()`: Returns indices for sorted array.
  - `array.sort()`: Sorts in-place.
  ---

  **II. Searching Functions**
  - `np.argmax()`, `np.argmin()`: Indices of max/min.
  - `np.where()`: Returns indices where condition is true.
  - `np.searchsorted()`: Finds insertion points in sorted array.
  ---

🛡️ **12. Data Type Handling (Basics)**
- `dtype`: Inspects array data type.
- `astype()`: Converts to specified dtype.
- `np.issubdtype()`: Checks subtype relationships.
---