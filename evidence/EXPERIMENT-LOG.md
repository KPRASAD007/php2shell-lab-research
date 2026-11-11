# PHP2Shell — Experiment Log

## 1. Experiment Overview

This document records observations from the previously examined, locally hosted PHP2Shell research environment.

## 2. Environment

- Host: Kali Linux Rolling
- Containerization: Docker
- Web server: Apache
- PHP version: 8.4.26
- Local service binding: 127.0.0.1:8088

## 3. Observations

The following stages were observed during the earlier local research session:

- Information-leak stage
- Memory-reclamation sweep
- Proof-of-concept reported an RCE outcome
- Directory listing displayed in the terminal

These are observations from that specific experiment. They do not independently establish the root cause, affected-version range, or exploitability of every reported vulnerability.

## 4. Evidence

### Screenshot 1 — PHP2Shell Lab Experiment

File: `php2shell-lab-experiment.png`

This screenshot documents the practical work performed during the local PHP2Shell research experiment.

It is included as supporting evidence of the experiment, not as independent proof of the underlying vulnerability.
## 5. Limitations

- Results are specific to the previously examined environment.
- A reported proof-of-concept result is not equivalent to independent vulnerability validation.
- No conclusions should be generalized to other PHP versions without further evidence.
