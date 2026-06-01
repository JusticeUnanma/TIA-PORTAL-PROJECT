# Day 1 — Project Setup & Hardware Configuration

## Date
2026-06-01

## Objectives
- Create TIA Portal V19 project
- Configure S7-1214C CPU
- Understand Device View
- Achieve RUN state in PLCSIM

## Scan Cycle — Key Learning
The PLC scan cycle runs 3 phases continuously:
1. Read all physical inputs into memory
2. Execute program top to bottom
3. Write results to physical outputs

Cycle time: approximately 1-10ms depending on program size.
Critical insight: signals shorter than scan time can be missed.
Fix: use edge detection or hardware interrupt OB40.

## Lab Results
_(fill this in as you complete the lab)_

## Issues Encountered
_(document any problems and how you solved them)_

## Quiz Answers
_(fill in after quiz)_
