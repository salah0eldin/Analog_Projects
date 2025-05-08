# Analog_Projects

This repository contains two main analog design projects:

## Folded Cascoded Amplifier (Folded_Cascoded_AMP)

This project focuses on the design and analysis of a folded cascoded amplifier. The directory structure is as follows:

- **cds.lib, cdsLibEditor.log, libManager.log**: Configuration and log files for Cadence tools.
- **Folded_Cascoded_AMP_Lib/**: Contains the library files for the project.
  - **FinalCircuit/**: Includes the schematic and constraints for the final circuit.
  - **FinalCircuit_Buffer/**: Contains the buffer circuit schematics.
  - **FinalCircuit_Buffer_No_Probe/**: Buffer circuit without probe schematics.
  - **FoldedCascodedAMP/**: Main amplifier design schematics and symbols.
  - **Sizing_N_bench/** and **Sizing_P_bench/**: Testbenches for sizing NMOS and PMOS transistors.
- **logs_cadence/**: Logs generated during simulations.
- **Plot_files/**: Graph files for various performance metrics.
- **Plot_screens/**: Screenshots of plots and schematics.
- **Report/**: Contains reports and procedures.
- **scs_files/**: Simulation control scripts.

## Universal Biquadratic Filter (Universal_Biquadratic_Filter)

This project involves the design and analysis of a universal biquadratic filter. The directory structure is as follows:

- **cds.lib, libManager.log**: Configuration and log files for Cadence tools.
- **Report_final.pdf**: Final report for the project.
- **logs_cadence/**: Logs generated during simulations.
- **plots/**: Contains plots for various filter responses.
- **proj1/**: Includes subdirectories for different filter configurations:
  - **Biquad/**, **Biquad_sin/**, **Biquad_square/**: Different filter designs.
  - **ideal_opamp/**: Ideal operational amplifier configurations.

Both projects are structured to facilitate easy navigation and understanding of the design and simulation processes.
