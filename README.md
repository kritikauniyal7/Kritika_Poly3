# HappyCircuit

HappyCircuit Zero-Knowledge Proof Template
This repository contains a Circom circuit template named HappyCircuit that demonstrates how to build a simple zero-knowledge proof using custom logic gates. This example showcases a basic multiplication check using zk-SNARKs.

What is Circom?
Circom is a programming language used to create zero-knowledge succinct non-interactive arguments of knowledge (zk-SNARK) circuits. These circuits enable the creation of cryptographic proofs that validate computations without revealing the actual data.


## Circuit Description

The circuit is designed using the Circom language, version 2.0.0. It consists of three components: `andGate1`, `notGate`, and `andGate2`. The main circuit template is `HappyCircuit`, which connects these components to create the desired logic.

### Components
Signal Inputs:

a and b are input signals representing the two operands.
Intermediate Signals:

x and y are intermediate signals used to store gate outputs.
Output Signal:

q is the output signal representing the result of the multiplication check.
Component Gates:

orGate, notGate, and andGate are components representing OR, NOT, and AND gates.

### Circuit Logic

The AND gate computes the product of a and b, storing the result in signal x.
The NOT gate inverts the value of b, storing the result in signal y.
The OR gate computes the logical OR of x and y, generating the final output signal q.
Main Component:

The main component is an instance of the HappyCircuit template, representing the complete circuit.

## Deployed Contract

The circuit has been deployed on the Mumbai test network using the appropriate tools. The contract's address and transaction details can be found in the deployment logs.

## Usage

To use this circuit for other inputs or different logical operations, the `HappyCircuit` template can be modified accordingly. By changing the logic of the gates and the connections, the circuit can perform various computations based on the inputs.

## Authors

Kritika Uniyal
Student-Chandigarh University
