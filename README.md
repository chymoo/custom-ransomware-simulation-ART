# Custom Ransomware Simulation

This repository contains files for simulating various attack techniques using Atomic Red Team.

## Techniques Included
- **T1059**: Command and Scripting Interpreter
- **T1204.002**: Malicious File Execution
- **T1548.002**: Bypass User Account Control
- **T1486**: Data Encrypted for Impact (Ransomware Simulation)
- **T1083**: File and Directory Discovery
- **T1056.001**: Input Capture (Keylogging)
- **T1048**: Exfiltration Over Alternative Protocol

## Structure
Each technique has its own folder containing:
- YAML configuration files
- Scripts and payloads specific to the technique

Shared tools are stored in the `tools/` folder.

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/chymoo/custom-ransomware-simulation-ART.git
