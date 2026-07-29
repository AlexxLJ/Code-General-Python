# 🧮 Python GUI Calculator (Dark Mode & History)

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![GUI](https://img.shields.io/badge/GUI-Tkinter-00BCD4.svg)](https://docs.python.org/3/library/tkinter.html)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Una calculadora de escritorio **moderna, limpia y minimalista** desarrollada en **Python** y **Tkinter**. Presenta un diseño de estilo *Flat UI* con paleta de tonos oscuros y cian, soporte para **Modo Oscuro 🌙** e **Historial de Operaciones**.

---

## 📸 Vista Previa & Diseño

* **Diseño Flat / Moderno:** Botones cuadrados con alto contraste entre números (azul oscuro) y operadores principales (azul cian/turquesa).
* **Modo Oscuro 🌙:** Selector superior para alternar o indicar el estado del tema visual.
* **Historial Integrado:** Registro en tiempo real de todos los cálculos realizados durante la sesión.
 <img src="calculadora actual.jpg" width="200">
---

## ✨ Características Principales

- 🌙 **Modo Oscuro / Tema Moderno:** Interfaz estilizada tipo flat con contraste optimizado para reducir la fatiga visual.
- 📜 **Historial de Operaciones:** Almacena y muestra cada cálculo completado (`ej. 8 * 9 = 72`) para consultar resultados anteriores. **Agregado 30/07/26**.
- ⌫ **Control de Corrección:**
  - **`C`**: Limpia la pantalla por completo.
  - **`<`**: Borra el último carácter introducido.
- 🧮 **Operaciones Esenciales:** Suma (`+`), Resta (`-`), Multiplicación (`*`), División (`/`) y Porcentaje (`%`).
- 📐 **Distribución Adaptable:** Cuadrícula proporcional que mantiene los botones centrados y bien alineados.

---

## 📁 Estructura del Proyecto

```text
calculadora-dark/
│
├── main.py                 # Punto de entrada de la aplicación
├── form_calculadora.py     # Clase principal FormularioCalculadora (Interfaz y Lógica)
├── config/
│   └── constantes.py       # Definición de colores y constantes visuales
└── util/
    └── util_ventana.py     # Funciones auxiliares (ej. centrado de ventana)
