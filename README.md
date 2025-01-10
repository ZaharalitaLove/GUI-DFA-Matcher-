# GUI-DFA-Matcher-
Computer Science II Project. This project implements a Deterministic Finite Automaton (DFA) system in Java. The program models state machines using State and Transition classes, allowing you to define and simulate DFA-based automata. A Java Swing GUI provides an interactive interface for testing input strings against DFAs.

Features
* State Machine Modeling:
* DFA Generation:
* DFA Matching:
* Word Searcher:

Key Classes & Interfaces
* State: Represents a DFA state with a label and acceptance condition.
* Transition: Represents a transition between states on a specific symbol.
* DFAGen: Reads DFA definitions from files and generates state machines.
* DFAMatcher: Matches input strings against a DFA.
* WordSearcher: Creates a DFA from a list of words and checks if input strings match.
* Exception Handling: Handles common DFA errors like invalid states, duplicate transitions, or missing attributes.

How to Use
1. Define the DFA:
    * Input the DFA in the format described in README_dfa.txt.
    * Specify states, transitions, and which states are accepting.
2. Test Strings:
    * For the DFAMatcher, input a string to check if it is accepted by the DFA.
    * For the WordSearcher, provide a list of words to test against the DFA.
3. Visualize the DFA:
    * Both programs use the underlying state machine definitions to simulate the DFA's behavior based on input.

Skills Demonstrated
* State Machine Theory: Implementation of a DFA using states and transitions.
* File Parsing: Reading DFA definitions from files and streams.
* Java Generics: Creating reusable and type-safe state and transition classes.
* Exception Handling: Implementing custom exceptions for DFA validation errors.
* Integration: Working with existing codebase.

