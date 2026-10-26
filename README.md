# Analog Communication Laboratory — EC31203

Original laboratory reports and one simulation assignment from the Analog Communication course (EC31203), IIT Kharagpur.

## Table of Contents

- [Overview](#overview)
- [Experiment Index](#experiment-index)
- [Concepts Covered](#concepts-covered)
- [Tools and Components](#tools-and-components)
- [Repository Structure](#repository-structure)
- [Academic Context](#academic-context)

## Overview

| Item | Detail |
|------|--------|
| Course | EC31203 — Communication-I (Analog Communication Lab) |
| Author | Jai Raj (23EC10031) |
| Institution | IIT Kharagpur, Department of E&ECE |
| Group | Group-6 |
| Experiments | 8 (filter design, modulators, demodulators, sampling, PWM) |
| Language | Lab reports (PDF); one MATLAB-less simulation report (FM Monte Carlo in AWGN) |

## Experiment Index

| # | Experiment | Objective (short) | Report |
|---|------------|-------------------|--------|
| 01 | [Basic filter design](analog-communication-lab/experiment-01/) | 1st-order passive LP/HP/BP and active LP filters | [PDF](analog-communication-lab/experiment-01/report.pdf) |
| 02 | [Switching modulator](analog-communication-lab/experiment-02/) | Transistor switch multiplying carrier and message | [PDF](analog-communication-lab/experiment-02/report.pdf) |
| 03 | [Amplitude modulation using MC1496](analog-communication-lab/experiment-03/) | AM with a balanced modulator IC; under/critical/over modulation | [PDF](analog-communication-lab/experiment-03/report.pdf) |
| 04 | [Envelope detector and log-antilog AM](analog-communication-lab/experiment-04/) | AM demodulation and log-antilog circuit | [PDF](analog-communication-lab/experiment-04/report.pdf) |
| 05 | [Frequency modulation using XR-2206](analog-communication-lab/experiment-05/) | FM generation with a function-generator IC | [PDF](analog-communication-lab/experiment-05/report.pdf) |
| 06 | [Frequency demodulation](analog-communication-lab/experiment-06/) | FM demodulation by several methods | [PDF](analog-communication-lab/experiment-06/report.pdf) |
| 07 | [Sampling](analog-communication-lab/experiment-07/) | Sample-and-hold at 10/15/50/80 % duty and 100 nF | [PDF](analog-communication-lab/experiment-07/report.pdf) |
| 08 | [Pulse width modulation](analog-communication-lab/experiment-08/) | PWM generation with an op-amp | [PDF](analog-communication-lab/experiment-08/report.pdf) |

Plus one original assignment: [FM Monte Carlo simulation in AWGN](analog-communication-lab/assignment-fm-monte-carlo/).

## Concepts Covered

- Passive and active filter design (LP/HP/BP).
- Amplitude modulation and demodulation (MC1496, envelope detector, log-antilog).
- Frequency modulation and demodulation (XR-2206).
- Switching modulation and sampling (sample-and-hold).
- Pulse-width modulation.
- FM performance in AWGN via Monte Carlo simulation.

## Tools and Components

- Discrete components, op-amps, MC1496, XR-2206, breadboard, function generator, oscilloscope.
- Reports only; no MATLAB/Python source was recovered for these experiments (the Monte Carlo assignment is report-only as well).

## Repository Structure

```text
analog-communication-lab/
├── README.md
├── .gitignore
└── analog-communication-lab/
    ├── README.md
    ├── experiment-01/ … experiment-08/
    │   ├── README.md
    │   ├── report.pdf
    │   └── figures/ (where available)
    └── assignment-fm-monte-carlo/
        ├── README.md
        └── report.pdf
```

## Academic Context

Coursework by Jai Raj (23EC10031), Group-6. Reports are joint lab work where applicable; attribution is preserved in the PDFs. No open-source license is applied.
