8-bit RISC Processor Design
This repository contains the design and implementation of an 8-bit RISC processor using Verilog on EDA Playground. The project includes detailed documentation and the necessary source files for simulating and synthesizing the processor.

Features
8-bit Data Path: The processor handles 8-bit wide data operations.
RISC Architecture: Implements a Reduced Instruction Set Computing (RISC) architecture for simplicity and efficiency.
Basic Instruction Set: Supports fundamental instructions such as arithmetic operations, logical operations, load/store, and control flow.
Modular Design: Comprises modular components such as the ALU, control unit, datapath, and memory, making it easy to understand and extend.
Testbenches: Includes testbenches to verify the functionality of each module and the overall processor.
Directory Structure
src/: Contains Verilog source files for the processor components.
alu.v: Arithmetic Logic Unit (ALU) module.
control_unit.v: Control Unit module.
datapath.v: Datapath module.
memory.v: Memory module.
docs/: Contains design documentation.
design_doc.md: Detailed design document explaining the architecture and design choices.
Getting Started
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/8bit-RISC-Processor.git
cd 8bit-RISC-Processor
Simulate and Synthesize:

Open the project files in EDA Playground or your preferred Verilog simulation tool.
Run the provided testbenches to verify functionality.
License
This project is licensed under the MIT License - see the LICENSE file for details.

https://www.edaplayground.com/x/Cpap

Contributing
Contributions are welcome! Please read the CONTRIBUTING file for guidelines on how to contribute to this project.
