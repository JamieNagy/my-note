
# Indefinite Integral Formulas

## 1. Basic Indefinite Integral Formulas

### Power Rule:
\[
\int x^n \, dx = \frac{x^{n+1}}{n+1} + C \quad \text{(for } n \neq -1\text{)}
\]
- Example: \( \int x^2 \, dx = \frac{x^3}{3} + C \)

### Exponential Functions:
\[
\int e^x \, dx = e^x + C
\]
\[
\int a^x \, dx = \frac{a^x}{\ln a} + C \quad \text{(for any positive constant } a \neq 1\text{)}
\]

### Natural Logarithm:
\[
\int \frac{1}{x} \, dx = \ln |x| + C \quad \text{(for } x \neq 0\text{)}
\]

### Trigonometric Functions:
\[
\int \sin(x) \, dx = -\cos(x) + C
\]
\[
\int \cos(x) \, dx = \sin(x) + C
\]
\[
\int \sec^2(x) \, dx = \tan(x) + C
\]
\[
\int \csc^2(x) \, dx = -\cot(x) + C
\]
\[
\int \sec(x) \tan(x) \, dx = \sec(x) + C
\]
\[
\int \csc(x) \cot(x) \, dx = -\csc(x) + C
\]

### Inverse Trigonometric Functions:
\[
\int \frac{1}{\sqrt{1 - x^2}} \, dx = \sin^{-1}(x) + C
\]
\[
\int \frac{1}{1 + x^2} \, dx = \tan^{-1}(x) + C
\]
\[
\int \frac{1}{x \sqrt{x^2 - 1}} \, dx = \sec^{-1}(x) + C \quad \text{(for } |x| > 1\text{)}
\]

## 2. Special Cases and Constant Multiples:

### Constant:
\[
\int c \, dx = cx + C \quad \text{(where } c \text{ is a constant)}
\]
- Example: \( \int 5 \, dx = 5x + C \)

### Sum Rule:
\[
\int (f(x) + g(x)) \, dx = \int f(x) \, dx + \int g(x) \, dx
\]
- Example: \( \int (2x + 3) \, dx = \int 2x \, dx + \int 3 \, dx = x^2 + 3x + C \)

### Constant Multiple Rule:
\[
\int c \cdot f(x) \, dx = c \int f(x) \, dx
\]
- Example: \( \int 3e^x \, dx = 3 \int e^x \, dx = 3e^x + C \)
