# commodore-64-emulator — Commodore 64 Emulator in C++

commodore-64-emulator es un **emulador open-source del Commodore 64**, escrito en **C++**, con un enfoque **educativo** y de **arquitectura clara**.  
El objetivo del proyecto es aprender y documentar cómo funciona el hardware clásico del C64 implementándolo paso a paso.

Este proyecto no busca ser el emulador más rápido ni el más completo, sino un **recurso didáctico** para entender la emulación de sistemas retro.

---

## ✨ Características

- Emulación de la CPU **MOS 6510**
- Mapa de memoria del Commodore 64
- Carga de archivos **PRG**
- Emulación del chip gráfico **VIC-II** (en progreso)
- Emulación básica del sonido **SID** (planeado)
- Interfaz en **modo consola (TUI)** estilo retro
- Código modular y fácil de leer

---

## 🎯 Objetivos del Proyecto

- Aprender cómo funciona el hardware del Commodore 64
- Servir como referencia educativa para otros desarrolladores
- Mantener un código limpio, comentado y bien estructurado
- Documentar cada componente del sistema

---

## 🧱 Arquitectura General

El emulador está dividido en módulos que representan el hardware real:

- CPU (6510)
- Memoria
- VIC-II (video)
- SID (audio)
- I/O (teclado, joystick)
- Sistema principal (timing y sincronización)

---

## 🗂️ Estructura del Proyecto

