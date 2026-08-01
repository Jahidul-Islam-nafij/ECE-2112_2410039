
# Experiment: Creating All Three Basic Gates Using NAND Gate

## 1. Problem 01

### 1.1 Problem Statement

The objective of this experiment is to design and implement the three basic logic gates, **AND, OR, and NOT**, using only **NAND gates**. Since the NAND gate is a universal logic gate, it can be used to construct other fundamental logic gates by properly connecting multiple NAND gates. The designed circuits are simulated and their outputs are verified using the corresponding truth tables.

### 1.2 Theory and Design Methodology

A **NAND gate** is a universal logic gate because all basic logic gates can be constructed using only NAND gates. In this experiment, the **NOT gate** is created by connecting both inputs of a NAND gate together. The **AND gate** is constructed by first performing a NAND operation on the two inputs and then passing the output through another NAND gate configured as a NOT gate. Similarly, the **OR gate** is implemented using De Morgan's theorem by first inverting both inputs using two NAND gates and then applying them to a third NAND gate. The output of each designed circuit is verified by comparing it with the standard truth table of the corresponding logic gate.

The Boolean expressions are:

**NOT Gate:**

$$
Y = A \ NAND\ A = \overline{A}
$$

**AND Gate:**

$$
Y = (A \ NAND\ B)\ NAND\ (A \ NAND\ B)
$$

$$
Y = A \cdot B
$$

**OR Gate:**

$$
Y = (A \ NAND\ A)\ NAND\ (B \ NAND\ B)
$$

$$
Y = A + B
$$

### 1.3 Circuit Diagram

The circuit diagrams for the **NOT, AND, and OR gates** are designed using only NAND gates. For the NOT gate, the two inputs of a single NAND gate are connected together. For the AND gate, two input signals are first connected to a NAND gate, and its output is connected to both inputs of a second NAND gate. For the OR gate, each input is first connected to a separate NAND gate with its inputs tied together, and the two resulting outputs are then connected to a third NAND gate. These configurations demonstrate the universal property of the NAND gate and produce the same logical outputs as the conventional NOT, AND, and OR gates.

#### NOT Gate Using NAND

![NOT Gate Using NAND](images/not_gate_using_nand.png)

#### AND Gate Using NAND

![AND Gate Using NAND](images/and_gate_using_nand.png)

#### OR Gate Using NAND

![OR Gate Using NAND](images/or_gate_using_nand.png)

# Experiment: Creating All Three Basic Gates Using NOR Gate

## 1. Problem 01

### 1.1 Problem Statement

The objective of this experiment is to design and implement the three basic logic gates, **AND, OR, and NOT**, using only **NOR gates**. Since the NOR gate is a universal logic gate, it can be used to construct other fundamental logic gates by properly connecting multiple NOR gates. The designed circuits are simulated and their outputs are verified using the corresponding truth tables.

### 1.2 Theory and Design Methodology

A **NOR gate** is a universal logic gate because all basic logic gates can be constructed using only NOR gates. In this experiment, the **NOT gate** is created by connecting both inputs of a NOR gate together. The **OR gate** is constructed by first performing a NOR operation on the two inputs and then passing the output through another NOR gate configured as a NOT gate. Similarly, the **AND gate** is implemented using De Morgan's theorem by first inverting both inputs using two NOR gates and then applying them to a third NOR gate. The output of each designed circuit is verified by comparing it with the standard truth table of the corresponding logic gate.

The Boolean expressions are:

**NOT Gate:**

$$
Y = A \ NOR\ A = \overline{A}
$$

**OR Gate:**

$$
Y = (A \ NOR\ B)\ NOR\ (A\ NOR\ B)
$$

$$
Y = A + B
$$

**AND Gate:**

$$
Y = (A\ NOR\ A)\ NOR\ (B\ NOR\ B)
$$

$$
Y = A \cdot B
$$

### 1.3 Circuit Diagram

The circuit diagrams for the **NOT, OR, and AND gates** are designed using only NOR gates. For the NOT gate, the two inputs of a single NOR gate are connected together. For the OR gate, two input signals are first connected to a NOR gate, and its output is connected to both inputs of a second NOR gate. For the AND gate, each input is first connected to a separate NOR gate with its inputs tied together, and the two resulting outputs are then connected to a third NOR gate. These configurations demonstrate the universal property of the NOR gate and produce the same logical outputs as the conventional NOT, OR, and AND gates.

#### NOT Gate Using NOR

![NOT Gate Using NOR](images/not_gate_using_nor.png)

#### OR Gate Using NOR

![OR Gate Using NOR](images/or_gate_using_nor.png)

#### AND Gate Using NOR

![AND Gate Using NOR](images/and_gate_using_nor.png)
