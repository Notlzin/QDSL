# Q$

Q$ is basically text based **quantum computing inspired DSL**, and its a **toy programming language** with conceptual quantum computer components like: **kernels, bootloaders, QPU and Grover's Algorithm**, **Note:** this isnt a real quantum computing based programming language.

---

## Q$ features

- **quantum computer inspired DSL**: uses qubits, room temperature, and simulated quantum ops and includes coherence and decoherence.
- **Kernel and vKernel**: the core computational part of the quantum computer.
- **bootloader support**: a shared environment for .qx files.
- **grover's algorithm**: globally installed and prebuilt, supports O(sqrt(N)) conceptual "runtime" and searches.
- **math and printing libs**: includes: Qubit.print(), ADD, MUL, SUB, DIV, RAND and advanced Qubit Manipulation.
- **error and decoherence hanlding**: returning |0⟩ or |1⟩ to represent success or failure.

---

## getting started with Q$ 

1. clone the github repository:
```bash
git clone https://github.com/Notlzin/QDSL.git
```
2. open any .qx files on your favorite code/text editors to explore Q$ DSL syntax.
3. conceptually "run" the example tests given in the folder itself. available outside the lib and vSystem folders.
example:
```qx
_Qubit::state::|0⟩;
_Qubit::cohere();

IF _Qubit::state == |0⟩ {
    _Qubit::state = |1⟩;
};
_Qubit::algo[1][1][1];  *activates Grover algorithm*
```
license
MIT license, feel free to explore deeper about Q$, or fork Q$

---

## **2. topic/tags**
- quantum
- quantum computing
- toy-language
- experimental
- programming-language
  
---

v0.1 | initial release.
- released Q$.
- added Q$ DSL such as: QPU, bootloader, kernels.
- prebuilt and globally installed grovers algorithm.
- math and printing libraries preinstalled.
- conceptual runtime tests.
- added ADD, SUB, MUl, DIV, RAND to math lib.



