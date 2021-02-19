# Capítulo 1: **Code Patterns**

La optimización puede conseguirse en cuanto al **tamaño del código** o la **velocidad del código**.
3 niveles de optimización en los compiladores.

- **Compiladores no-optimizadores**: Más rápido, produce código más entendible.

- **Compiladores optimizadores**: Menos rápido, pero el código producido se ejecuta más rápido (no necesariamente produce código compacto).

En ocasiones los compiladores incluyen información de compilación (debug info) en el archivo resultante. El código depurado puede contener enlaces entre cada linea del código fuente y su respectiva dirección de código máquina.

Cada CPU tiene su propio ISA:
**Instruction Set Arquitechture (ISA)**: Es el juego de instrucciones que la CPU puede entender. Se pueden clasificar según su **complejidad de arquitectura**:

- **CISC**: Tiene un conjunto de instrucciones amplio y permite operaciones complejas entre operandos de la memoria y registros internos. **Dificulta el paralelismo** entre instrucciones (familia x86, familia 8080...) 

- **RISC**: Instrucciones de tamaño fijo. Solo las instrucciones de carga y almacenamiento acceden a la memoria de datos. **Facilita el paralelismo**. (Lenguaje MIPS está basado en el diseño RISC)

- **SISC**: Orientado al paralelismo. RISC es un subconjunto del SISC.

![Esquema](https://github.com/franramos97/Notes_ReverseEngineeringForBeginners/blob/main/Esquema.jpeg)

