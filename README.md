# ControlX — Control Systems Simulator

<p align="center">
  <b>Interactive Web-Based Control Systems Simulator</b><br/>
  Design • Analyze • Tune — All in One Place
</p>

---

## 🚀 Overview

**ControlX** is an interactive web application designed for control systems students and engineers.
It provides real-time simulation and visualization of classical control concepts directly in the browser.

---

## ✨ Features

* 🎯 Open Loop System Visualization
* ⚙️ Closed Loop PID Control
* 📈 Step Response Analysis
* 📊 Bode Plot (Magnitude & Phase)
* 🔁 Nyquist Plot
* 🌿 Root Locus (based on polynomial root calculation)
* 🤖 Auto PID Tuning (Ziegler–Nichols Method)
* 🧮 Dynamic Transfer Function Rendering (math form)
* 🎛️ Adjustable Second-Order System (ζ, ωₙ)

---

## 🧠 Core Concepts Implemented

* Numerical integration (Runge–Kutta method)
* Polynomial root solving (complex domain)
* Frequency response analysis
* Classical PID control theory
* Root Locus formulation

---

## 🖥️ Usage

1. Open the application:

```bash
index.html
```

2. Select Mode:

* **System Visualizer (Open Loop)** → analyze the raw system
* **PID Tuning (Closed Loop)** → apply controller

3. Enter system transfer function:

```text
Numerator: 1
Denominator: 1,3,2
```

4. Or generate a second-order system:

* Set ζ (damping ratio)
* Set ωₙ (natural frequency)
* Click **Apply 2nd Order**

5. Run analysis and switch between:

* Step
* Bode
* Nyquist
* Root Locus

---

## ⚠️ Important Notes

* Ziegler–Nichols auto-tuning works only for systems with a valid **ultimate gain (Ku)**
* Not all systems support ZN tuning (especially stable low-order systems)
* Transfer functions must be entered in descending powers format:

```text
1,3,2   →  s² + 3s + 2
```

---

## 🧪 Example

Second-order system:

```text
ζ = 0.5
ωₙ = 2
```

Generated transfer function:

```math
G(s) = \frac{4}{s^2 + 2s + 4}
```

---

## 🛠️ Tech Stack

* HTML5
* CSS3
* JavaScript (Vanilla)
* Plotly.js (for visualization)
* Custom-built math engine

---

## 📌 Future Improvements

* Open vs Closed Loop comparison view
* Export plots (PNG / PDF)
* Real-time sliders for parameters
* Save / load system configurations
* Multi-language support

---

## 👨‍💻 Developer

**Mohamad R. Omran**
📧 [Hello@Mohmad.net](mailto:Hello@Mohmad.net)
🌐 Mohmad.net

---

## ⭐ Support

If you found this project useful:

* ⭐ Star the repository
* 🔁 Share it with others
* 💡 Suggest improvements

---
