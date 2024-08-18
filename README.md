# DFA String Acceptance Checker

This C++ program implements a Deterministic Finite Automaton (DFA) to determine whether a given string is accepted by the DFA. It allows users to define states, input symbols, the start state, final states, and the transition function of the DFA.

## Features

- Define states and input symbols of the DFA.
- Set the start state and final states.
- Input the transition function for state transitions.
- Check if a given input string is accepted by the DFA.

example:
Enter the number of states: 3
Enter the states (space-separated): q0 q1 q2
Enter the number of input symbols: 2
Enter the input symbols (space-separated): 0 1
Enter the start state: q0
Enter the number of final states: 1
Enter the final states (space-separated): q2
Define the transition function:
From state q0 with input '0', go to state: q1
From state q0 with input '1', go to state: q0
From state q1 with input '0', go to state: q0
From state q1 with input '1', go to state: q2
From state q2 with input '0', go to state: q2
From state q2 with input '1', go to state: q2
Enter a string to check: 0110__
The string is ______ by the DFA.
