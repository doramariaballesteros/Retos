# 🧩 Reto 1. Descubriendo qué ocurre dentro de una caja negra

**Análisis de Señales**

---

## ⏱️ Duración

[Por definir]

## 👥 Modalidad

Trabajo por parejas.

Cada grupo deberá entregar un **único archivo PDF** con las respuestas, incluyendo las evidencias técnicas solicitadas y las conclusiones correspondientes.

> 📌 **Importante:** Python se utilizará como herramienta de **verificación**.  
> Primero deberán analizar el problema y proponer una solución a partir de los conceptos estudiados en clase. Posteriormente, podrán utilizar Python para comprobar si su propuesta reproduce correctamente la señal observada.

---

## Contexto

En un sistema de telecomunicaciones no siempre conocemos las operaciones que se realizan internamente sobre una señal. En algunas situaciones solo disponemos de la **señal de entrada** y la **señal de salida**, y a partir de ellas debemos inferir qué ocurrió dentro del sistema.

En este reto analizarán diferentes **cajas negras**. En cada caso conocerán su entrada y su salida, pero no la operación realizada internamente.

Su misión será **descubrir qué ocurrió dentro de cada caja negra y verificar su hipótesis utilizando Python.**

---

# 🧩 Desafío 1. ¿Qué transformación sufrió la señal?

Una señal discreta $x[n]$ ingresa a una **caja negra** que realiza una transformación desconocida de la variable independiente. A la salida se obtiene la señal $y[n]$.

<p align="center">
  <img src="Imagen_reto1_1.png" width="850">
</p>

A partir de las señales de entrada y salida:

### ¿Qué transformación de la variable independiente ocurrió dentro de la caja negra?

Su respuesta debe incluir:

- La **expresión matemática** que relaciona $y[n]$ con $x[n]$.
- Una explicación breve del **procedimiento utilizado para identificar la transformación**.
- La identificación de las operaciones de **compresión, dilatación, inversión y/o desplazamiento**, según corresponda.
- Una **verificación en Python** que demuestre que la transformación propuesta reproduce correctamente la señal de salida observada.

> 💡 **Recuerden:** el objetivo no es encontrar la respuesta probando transformaciones en Python.  
> **Primero formulen una hipótesis y después utilicen Python para verificarla.**
