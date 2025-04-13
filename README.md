# 📡 Bit Transmission over Noisy Channels – MATLAB Simulation

This project simulates a basic digital communication system where binary bits are transmitted through an **Additive White Gaussian Noise (AWGN)** channel. The simulation focuses on understanding and visualizing the relationship between **SNR (Signal-to-Noise Ratio)** and **BER (Bit Error Rate)** using MATLAB.

---

## 🧪 Project Overview

The simulation performs the following:

- Generates random binary sequences (`0` and `1`)
- Transmits them through a noisy channel
- Applies threshold detection at the receiver
- Calculates **BER** by comparing transmitted and received bits
- Analyzes the impact of **SNR** on BER using:
  - **Trial-and-error noise scaling** (for SNR ≈ 10 dB)
  - **Analytical noise scaling** (for precise SNR control)
- Plots **BER vs SNR** curve

---

## 📁 Files

- `tx_rx_ber.mlx`: MATLAB Live Script containing all simulations, calculations, and plots.
- (Optional) `report.pdf` or `report.docx`: Formal lab report based on this simulation.

---

## 📈 Topics Covered

- Random binary signal generation using `randi`
- Noise simulation using `randn`
- BER calculation
- SNR estimation in dB and linear scale
- Noise power adjustment
- Data visualization (`stem`, `semilogy`, etc.)

---

## 📊 Sample Plot

The following graph is generated:

> **BER vs SNR** (on a logarithmic scale)

Showing the exponential decrease in BER as SNR increases.

---

## ⚙️ Requirements

- MATLAB R2021a or newer (Live Script compatible)
- No toolboxes required

---

## 📚 References

- *Carlson, B. P., Communication Systems, Fifth Edition*
- MATLAB Documentation: [`randn`](https://www.mathworks.com/help/matlab/ref/randn.html), `log10`, `semilogy`

---

## 🧑‍💻 Author

**Amirhossein Jafari Chashmi**  
Electrical Engineering – Digital Communications Lab  
Student ID: 40011910023

---

## 🔗 How to Cite

> If you're using this project for educational purposes, please cite the original author and link to this repo 🙏

---

Feel free to fork, star ⭐, or contribute!
