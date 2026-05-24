## 100-Days-Of-Machine-Learning
My journey through ML basics to advanced models.

### Day 1: Python Basics & Salary Calculator
- **Concepts:** Variables, Input, F-strings, Arithmetic.
- **Project:** Built a formatted pay slip generator.

### Day 2: Boolean Logic & Decision Engines
**Topic:** Data Types (Boolean, None) and Logical Operators.

**Key Learnings:**
- **Comparison Operators:** Used `==`, `!=`, and chained comparisons (`18 <= age <= 65`).
- **Logical Gates:** Implemented `and`, `or`, and `not` to build complex decision trees.
- **Short-Circuiting:** Leveraged Python's evaluation order to handle empty inputs safely.

**Project: SafePass AI Loan Predictor**
A mini-engine that evaluates loan applicants based on age, credit history, income, and special manager referrals. It demonstrates how AI systems make binary decisions based on multi-factor logic.


###  Day 3: Loops & Collections
**Topic:** Iteration with `for` and `while`, `range()`, and `break/continue`.

**Key Learnings:**
- Used `enumerate()` to track indices during loops.
- Mastered the `for-else` block (executes only if `break` isn't hit).
- Explored **List Comprehensions** for concise data processing.

**Projects:** 
1. Multiplication Table Generator.
2. Extended FizzBuzz (with 'ML' flag for multiples of 7).
3. List Comprehension refactor of the FizzBuzz logic.


###  Day 4: Conditionals (Decision Making)
- **Concepts:** `if`, `elif`, `else`, Ternary operators, and Logical Branching.
- **Project:** **Health-Sync Step Analyzer** - Categorizes daily physical activity levels and awards badges using ternary logic.


###  Day 5: Functions & Modular Programming
- **Concepts:** `def` keywords, parameters vs arguments, local/global scope, and the `math` and `json` modules.
- **Project: Grade Analyzer** - A manual CSV parser that calculates class statistics without using external libraries like Pandas
- 

##  Day 6: Linear Algebra - Vector Operations
**Topic:** Core math principles including Vector Space, Magnitudes, Dot/Cross Products, and Field Visualizations using NumPy and Matplotlib.

### Key Learnings:
- **Element-wise Operations:** Mastered array addition, subtraction, and scalar scaling matrices.
- **Geometric Reductions:** Computed vector magnitudes ($L_2$ norm) using `np.linalg.norm()` and directions using angular trigonometry (`np.arctan2`).
- **Data Similarity:** Explored the **Dot Product**, which forms the backbone of feature matching and structural network layers in ML models.
- **Visual Mapping:** Formulated coordinate grids with `np.meshgrid()` and plotted force fields using `plt.quiver()`.

###  Mini Project: Geometric Vector Space Simulation
Implemented a program to compute geometric relationships between multi-dimensional arrays, alongside an interactive workspace rendering coordinate trajectories mapping individual input paths against their aggregate vector structures.


##  Day 7: Linear Algebra - Matrix Operations & Benchmarking
**Topic:** 2D Grid Spaces, Shape Alignment Rules, Transposition, Matrix Multiplication ($O(n^3)$ Complexity), and Algorithmic Benchmarking.

### Key Learnings:
- **Matrix Dimension Tracking:** Enforced structural compatibility guidelines where inner dimensions must align (e.g., multiplying an $A \times B$ matrix by a $B \times C$ matrix results in an $A \times C$ output shape).
- **Algorithmic Complexity:** Explored the performance degradation of explicit nested looping mechanics down a triple-tier hierarchy ($O(n^3)$ operations).
- **The Power of Vectorization:** Witnessed how NumPy completely bypasses Python interpreter loops by pointing arrays directly toward underlying compiled C structures, running operations over 91x faster.

###  Mini Project: Loop vs. NumPy Performance Profiler
Developed a performance analytics benchmark that constructs a manual matrix multiplication engine from scratch utilizing raw nested loop indexing, profiles its execution speed against optimized NumPy matrix operations on a $100 \times 100$ dimensional grid, and visualizes the stark architectural speed differences via a Matplotlib bar chart.


##  Day 8: Calculus - Derivatives & Gradient Descent
**Topic:** Rates of Change, First-Order Derivatives, Slopes, and Step-Size Optimization via Gradient Descent.

###  Key Learnings:
- **The Power of Slopes:** Explored how the derivative $f'(x)$ functions as a compass, pointing in the direction of the steepest ascent. Moving *against* it allows an algorithm to locate local or global minimums.
- **Learning Rate Dynamics:** Proved how the choice of learning rate ($\alpha$) heavily dictates convergence behavior:
  - **Too Small ($\alpha = 0.01$):** Trapped in an inefficient, slow crawl toward the minimum.
  - **Optimal ($\alpha = 0.1$ / $0.5$):** Smooth and rapid path optimization.
- **Automated Minimization:** Iteratively tracked a parameter from $x = 10$ down to the analytical minimum at $x = -2.5$ for the quadratic function $f(x) = x^2 + 5x + 6$.

###  Mini Project: Gradient Descent Learning Rate Profiler

Coded an interactive mathematical simulation that implements a custom Gradient Descent function from scratch. The system updates parameter values iteratively based on the function's calculated derivative, tests multiple learning rates simultaneously, and plots their comparative pathways toward the true minimum using Matplotlib.

##  Day 9: Basic Statistics - Statistical Foundations & Verification
**Topic:** Central Tendency (Mean, Median, Mode), Dispersion Metrics (Variance, Standard Deviation), and Mathematical Verification Foundations.

###  Key Learnings:Central Tendency:**
  - **Mean:** The arithmetic average, sensitive to extreme outliers.
  - **Median:** The middle value of sorted data, acting as a robust structural middle point against outliers.
  - **Mode:** The most frequent value(s) in a distribution, capable of handling multimodal datasets (as shown by your script identifying both `32` and `18`).
- **Data Dispersion & Spread:**
  - **Variance ($\sigma^2$):** Measures how far data points are spread out from the mean by averaging the squared differences.
  - **Standard Deviation ($\sigma$):** The square root of variance, translating the spread metric back into the original units of your data for realistic mapping.
- **Verification Testing:** Proved that scratch-built loop algorithms generate mathematically identical results to pre-compiled library architectures like `np.var()` and `np.std()`.

###  Mini Project: Descriptive Statistics Verification Engine
Built a dual-engine statistics profile analyzer from scratch. The program takes an arbitrary input list of numbers, processes all descriptive statistics metrics using pure Python algorithmic loops, validates the outputs step-by-step against vectorized NumPy equivalents, and outputs an aligned text-based verification matrix dashboard.