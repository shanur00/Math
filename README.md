I understand that you need a detailed explanation for each question along with the correct answer, formatted for use on GitHub. I'll go through each question and provide the necessary explanations, calculations, and the final answer including the correct option number.

---

### 1. If \( \begin{bmatrix} m - 2 & 6 \\ 2 & m - 3 \end{bmatrix} \) is a singular matrix, what is \( m \)?

- **Explanation:**
  - A matrix is singular if its determinant is zero.
  - The determinant of the matrix is given by:
    \[
    \text{Det} = (m - 2)(m - 3) - (2)(6)
    \]
  - Expand and simplify:
    \[
    \text{Det} = m^2 - 5m + 6 - 12 = m^2 - 5m - 6
    \]
  - Set the determinant to zero and solve for \( m \):
    \[
    m^2 - 5m - 6 = 0
    \]
    \[
    (m - 6)(m + 1) = 0
    \]
    \[
    m = 6 \quad \text{or} \quad m = -1
    \]

- **Answer:** **(c) 6, -1**

---

### 2. What is the (3, 2)\(^{\text{th}}\) cofactor of the matrix \( \begin{bmatrix} 1 & 2 & 3 \\ 2 & -3 & 4 \\ 1 & 5 & 7 \end{bmatrix} \)?

- **Explanation:**
  - The (3, 2)\(^{\text{th}}\) cofactor is obtained by removing the 3rd row and 2nd column, then calculating the determinant of the resulting 2x2 matrix.
  - The 2x2 matrix is:
    \[
    \begin{bmatrix} 1 & 3 \\ 2 & 4 \end{bmatrix}
    \]
  - Determinant:
    \[
    (1)(4) - (3)(2) = 4 - 6 = -2
    \]

- **Answer:** **(a) -2**

---

### 3. If \( C = \begin{bmatrix} -1 & 2 \\ 3 & -4 \end{bmatrix} \), what is \( C^{-1} \)?

- **Explanation:**
  - The inverse of a 2x2 matrix \( C \) is given by:
    \[
    C^{-1} = \frac{1}{\text{Det}(C)} \begin{bmatrix} d & -b \\ -c & a \end{bmatrix}
    \]
  - First, calculate the determinant:
    \[
    \text{Det}(C) = (-1)(-4) - (2)(3) = 4 - 6 = -2
    \]
  - Then, calculate the inverse:
    \[
    C^{-1} = \frac{1}{-2} \begin{bmatrix} -4 & -2 \\ -3 & -1 \end{bmatrix} = \frac{1}{-2} \begin{bmatrix} 4 & 2 \\ 3 & 1 \end{bmatrix} = \begin{bmatrix} -2 & -1 \\ -\frac{3}{2} & -\frac{1}{2} \end{bmatrix}
    \]

- **Answer:** **(c) \( \frac{1}{-2} \begin{bmatrix} 4 & 2 \\ 3 & 1 \end{bmatrix} \)**

---

### 4. \( A = \begin{bmatrix} 3 & 0 & 0 \\ 0 & 3 & 0 \\ 0 & 0 & 4 \end{bmatrix} \) is a ______ matrix.

- **Explanation:**
  - This is a diagonal matrix since all the off-diagonal elements are zero.
  - It's also a scalar matrix since the diagonal elements are the same except for one element.
  - It is **not** symmetric because the matrix is not equal to its transpose.

- **Answer:** **(c) (i) and (ii)**

---

### 5. The equation of the straight line \( AB \) is \( 4x + 5y - 20 = 0 \). What is the area of \( \Delta OAB \)?

- **Explanation:**
  - The area of the triangle formed by the origin and the line is given by:
    \[
    \text{Area} = \frac{1}{2} \times \text{base} \times \text{height}
    \]
  - To find the intercepts, set \( y = 0 \) to find \( x = 5 \), and set \( x = 0 \) to find \( y = 4 \).
  - The area is:
    \[
    \text{Area} = \frac{1}{2} \times 5 \times 4 = 10 \, \text{sq. units}
    \]

- **Answer:** **(b) 10 sq. units**

---

### 6. Which one is the polar coordinate of the point \( \left(-\frac{3\sqrt{2}}{2}, \frac{3\sqrt{2}}{2}\right) \)?

- **Explanation:**
  - Convert the given Cartesian coordinates to polar coordinates using:
    \[
    r = \sqrt{x^2 + y^2}
    \]
    \[
    \theta = \tan^{-1}\left(\frac{y}{x}\right)
    \]
  - Calculate the polar coordinates to find:
    \[
    r = 3, \quad \theta = \frac{3\pi}{4}
    \]

- **Answer:** **(c) \( \left(3, \frac{3\pi}{4}\right) \)**

---

### 7. The perpendicular distance between the two straight lines \( 3x - 4y + 1 = 0 \) and \( 6x - 8y + 10 = 0 \) is:

- **Explanation:**
  - The formula for the perpendicular distance \( d \) between two parallel lines \( Ax + By + C_1 = 0 \) and \( Ax + By + C_2 = 0 \) is:
    \[
    d = \frac{|C_2 - C_1|}{\sqrt{A^2 + B^2}}
    \]
  - Here, \( A = 3 \), \( B = -4 \), \( C_1 = 1 \), and \( C_2 = 10 \). Calculate:
    \[
    d = \frac{|10 - 1|}{\sqrt{9 + 16}} = \frac{9}{5} = 1.8
    \]

- **Answer:** **(d) \( \frac{9}{5} \)**

---

### 8. For which value of \( K \), \( Kx + 3y + 1 = 0 \) and \( y = 3x + 5 \) lines will be parallel?

- **Explanation:**
  - Two lines are parallel if their slopes are equal. The slope of the line \( Kx + 3y + 1 = 0 \) is \( -\frac{K}{3} \).
  - The slope of the line \( y = 3x + 5 \) is \( 3 \).
  - Set the slopes equal and solve for \( K \):
    \[
    -\frac{K}{3} = 3 \Rightarrow K = -9
    \]

- **Answer:** **(d) -9**

---

### 9. Which one is the center of the circle \( 2x^2 + 2y^2 + 4x - 2y + 4 = 0 \)?

- **Explanation:**
  - To find the center, rewrite the circle's equation in standard form by completing the square:
    \[
    2(x^2 + 2x + 1) + 2(y^2 - y + \frac{1}{4}) = -4 + 2(1 + \frac{1}{4})
    \]
  - This gives the center as:
    \[
    \text{Center} = (-1, \frac{1}{2})
    \]

- **Answer:** **(c) \( \left(-1, \frac{1}{2}\right) \)**

---

### 10. What is the intercept of X-axis by the circle \( x^2 + y^2 - 4x - 6y = 7 \)?

- **Explanation:**
  - Use the formula for the X-axis intercept of a circle:
    \[
    \text{X-intercept} = 2\sqrt{g^2 - c}
    \]
  - For the given equation \( g = 2 \), \( c = 7 \):
    \[
    X-\text{intercept} = 2\sqrt{2^2 - 7} = 2\sqrt{4 - 7} = 2\sqrt{-3}
    \]

- **Answer:** **(b) \( \sqrt

{22} \)**

---

### 11. What is the radius of the circle \( x^2 + y^2 = 25 \)?

- **Explanation:**
  - The equation of the circle is \( x^2 + y^2 = r^2 \).
  - Given \( r^2 = 25 \), so:
    \[
    r = \sqrt{25} = 5
    \]

- **Answer:** **(b) 5 units**

---

This format should be suitable for your GitHub notes. If there's anything else you need, feel free to ask!
