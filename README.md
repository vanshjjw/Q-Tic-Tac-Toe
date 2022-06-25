# QTicTacToe

A Quantum Version of the classic TicTacToe Game. 

## General Rules:

1. Instead of placing normal crosses and nuts, you will be placing superpositions of crosses and nuts called Qubits.
2. The 3x3 Grid is numbered from 0-8 (Top-Left to Bottom-Right)
3. You and the Computer take turns placing your Qubits (You can only choose to place from a pre-defined set of Qubits)
4. You and the Computer can both choose to "Measure" any 3 Qubits along a row, column or a diagonal. By Measuring, you force the Qubits to collapse onto either a cross or a nut, in accordance to the probabilities of the Qubit. The goal is to measure and find **either** three crosses **or** three nuts.
5. You and the Computer can both choose to measure a maximun of 5 times. If a measurement is succesful, you win, otherwise the 3 Qubits you measured are removed from the grid, and the game continues. 
6. If you (or the computer) make 5 unsuccessful Measurements,  you lose!
