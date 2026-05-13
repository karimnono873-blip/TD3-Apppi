# Interactive Grafcet Forcing Simulator ⚙️

![Status](https://img.shields.io/badge/Status-Complete-success)
![Subject](https://img.shields.io/badge/Subject-Industrial_Automation-blue)
![Topic](https://img.shields.io/badge/Topic-Grafcet_API-violet)

## 📌 Description

[cite_start]This repository contains an interactive web-based visualization solving **Exercice 10** from the "Série de TD N°3 : Programmation des APIs (Grafcet)"[cite: 4, 173]. The project focuses on the advanced control concept of hierarchical Grafcet forcing (Ordres de Forçage). 

It demonstrates how a master control system (G1) dictates the behavior of a slave system (G2) through specific forcing commands, a crucial aspect of designing robust safety and operational architectures in modern automation.

## 🚀 Features

* **Interactive Chronograms:** Time-slider functionality to visualize signal propagation and state changes in real-time.
* **Dual-Scenario Analysis:**
    * [cite_start]**Cas 1 : Forçage d'état (`F/G2 {12}`)** - Demonstrates forcing the slave Grafcet into a specific active step (X12) [cite: 191] and analyzing the holding state.
    * [cite_start]**Cas 2 : Forçage à vide (`F/G2 { }`)** - Illustrates the emergency stop protocol by completely deactivating the slave Grafcet[cite: 204], along with the structural modifications required for system recovery (Reprise).
* **Modern UI/UX:** Styled with a sleek "astronomic violet blue" theme for clean, professional academic presentations.
* **Zero Dependencies:** Built entirely with raw HTML, CSS, and Vanilla JavaScript. No frameworks required.

## 🛠️ Usage

To view the interactive simulation:
1. Clone this repository to your local machine.
2. Open the `index.html` file in any modern web browser.
3. [cite_start]Use the range sliders below each graph to simulate the progression of time ($t$) and observe the logical states of variables $X_0, X_1, X_{10}, X_{11},$ and $X_{12}$[cite: 175, 176, 180, 184, 187, 189, 190, 196, 197, 206, 210, 214].

## 🏫 Academic Context

[cite_start]This simulation was developed as part of a Master's level curriculum focusing on Programmable Logic Controllers (APIs) and discrete event systems[cite: 1, 2, 12]. It provides a bridge between theoretical paper-based chronograms and dynamic system behavior.

---
*Developed by Dahane Ahmed Lamine & [Nom de ton Binôme]*
