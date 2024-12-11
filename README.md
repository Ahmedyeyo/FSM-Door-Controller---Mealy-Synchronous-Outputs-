
---

### **FSM Door Controller - Mealy (Synchronous Outputs)**

```markdown
# FSM Door Controller - Mealy (Synchronous Outputs)

## Project Overview
This project implements a Finite State Machine (FSM) for door control using the Mealy model with synchronous outputs. By registering the outputs, the design ensures stability and prevents glitches that can occur in high-speed systems. This architecture is particularly suited for environments requiring precise timing and controlled transitions.

## Features
- **Synchronous Outputs**: Outputs are registered to ensure stable and predictable signals at each clock edge.
- **Mealy Model**: Combines state-based logic with input responsiveness for dynamic control.
- **Precise Timing**: Designed to prevent glitches and ensure reliable operation in high-speed applications.
- **Extensive Testing**: Fully validated through simulation and waveform analysis.

## Applications
- Precision-controlled automatic doors in secure environments.
- Advanced industrial systems requiring glitch-free output transitions.
- Systems with strict timing requirements for inputs and outputs.

## File Structure
- **src/**: Contains VHDL files for the Mealy FSM with synchronous outputs.
- **doc/**: Documentation detailing the FSM structure, state diagrams, and test protocols.
- **simulation/**: Includes simulation files, waveforms, and logs.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/FSM_Door_Controller_Mealy_Synchronous.git
