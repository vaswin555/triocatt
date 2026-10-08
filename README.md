[🇷🇺 Русский](README.ru.md) | 🇬🇧 English

# Triocatt

**Triocatt** is a composite geometric structure consisting of three independent right (Pythagorean) triangles with integer sides, united around a single common leg.

*Etymology:*
*   **EN:** The name is derived from **Trio** + **C.A.T.T.** (**C**atheti **A**ssembled **T**hree **T**riangles).
*   **RU:** Название образовано от **Трио** + **C.A.T.T.** (**C**atheti **A**ssembled **T**hree **T**riangles — Три Объединённых Катета Треугольников).

---

## 🛠️ Structure Anatomy

A Triocatt consists of **7 elements (parameters)**: one base (common) and six unique (derived).

1. **Base (Common leg $a$):** The foundation of the structure. A single segment that serves simultaneously as a leg for all three triangles.
2. **Orthogonal rays (Second legs $b_1, b_2, b_3$):** Three unique integer segments. Each is placed at 90° to the base $a$.
3. **Closing vectors (Hypotenuses $c_1, c_2, c_3$):** Three unique integer segments connecting the ends of the base and the orthogonal rays.

### Mathematical criteria:
* All 7 segments must be strictly **natural numbers** ($\mathbb{Z}^+$).
* Second legs are pairwise distinct: $b_1 \neq b_2$, $b_2 \neq b_3$, $b_1 \neq b_3$.
* Hypotenuses are pairwise distinct: $c_1 \neq c_2$, $c_2 \neq c_3$, $c_1 \neq c_3$.

$$
\begin{cases}
a^2 + b_1^2 = c_1^2 \\
a^2 + b_2^2 = c_2^2 \\
a^2 + b_3^2 = c_3^2
\end{cases}
$$

---

## 💎 Minimal Triocatt

The smallest possible Triocatt in mathematics has a base **$a = 24$**. It consists of the following three Pythagorean triangles:

### 1. Element "Alpha"
*   **Base ($a$):** 24
*   **Second leg ($b_1$):** 7
*   **Hypotenuse ($c_1$):** 25
*   *Formula:* $24^2 + 7^2 = 25^2 \implies 576 + 49 = 625$

### 2. Element "Beta"
*   **Base ($a$):** 24
*   **Second leg ($b_2$):** 10
*   **Hypotenuse ($c_2$):** 26
*   *Formula:* $24^2 + 10^2 = 26^2 \implies 576 + 100 = 676$

### 3. Element "Gamma"
*   **Base ($a$):** 24
*   **Second leg ($b_3$):** 70
*   **Hypotenuse ($c_3$):** 74
*   *Formula:* $24^2 + 70^2 = 74^2 \implies 576 + 4900 = 5476$

---

## 📐 Geometric Layout

![Geometric Layout of Triocatt](image_72e1c8dc.jpg)

---

## 📜 License
This terminology and concept are published under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.
