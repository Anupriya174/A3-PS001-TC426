# AIORI-3-HACKATHON-PROJECTS
This repository will contain the code and resources for the AIORI-3 hackathon that will be developed during the AIORI-3


# CyberSentinel: Android Ransomware-Like Activity Early Warning

AIORI Hackathon 3 | A3-PS001-TC426 | Cyber Security
Guide: Dr. Animesh Giri

## Overview
Zero-day ransomware has no known signature, so antivirus often misses it.
CyberSentinel is a behaviour-based early-warning detector. It watches one test
folder in a controlled Android emulator, raises an alert when file activity
looks like ransomware, and stops only the simulated test workload.

## Team
| Name | Focus |
|------|-------|
| Anupriya | Lab environment, telemetry, simulation scripts |
|  Anvii S Rai | Detector, responder, evaluation |

## Done
- Studied the problem and related work
- Designed the architecture and data flow
- Planned the detector, safety rules and evaluation
- Prepared the proposal slides
- Set up the GitHub repository

## Next
1. Emulator lab setup and restore script
2. Capture file events with timestamps
3. Safe attack simulations and normal workloads
4. Detector, canary files and test-workload-only kill
5. Evaluation: detection delay, precision, recall, files changed
6. Demo and documentation

## Safety
Dummy files in the LabTest folder only. No network, no ransom note, and only
the allowlisted test workload can be stopped.

## Status
Proposal and design complete. Implementation in progress.


## yt video link : https://youtu.be/_KwIhL9mdUI
