# Research & Summarize Botnet Architectures

## Goal
Understand the structure of botnets, focusing on centralized and decentralized botnets.

## Task
Write up a summary of your findings in `/docs/botnet_architecture_notes.md`.

## Botnet Architectures to Focus On:

### Centralized Botnets
- Controlled by a central command-and-control (C&C) server.
- Easier to detect due to a single point of failure.
- **Example**: Zeus botnet.

### Decentralized (Peer-to-Peer) Botnets
- No central server; bots communicate with each other (P2P architecture).
- Harder to detect because there is no single point of failure.
- **Example**: Storm botnet.

## Traditional Detection Methods:

### Signature-based Detection
- Detects based on known malicious patterns (signatures).
- Effective but limited to known threats.

### Anomaly-based Detection
- Monitors network traffic for deviations from normal behavior.
- Effective for new/unknown threats but prone to false positives.