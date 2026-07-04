# Peak Time Monitor (PTM)

A small ASIC digital design project implementing a peak-value tracker
with interval timing, taken through the full RTL-to-GDSII flow using
Cadence Genus (synthesis) and Cadence Innovus (physical design) on the
SCL180 PDK.

## Project Structure

- `1_Inputs/` - RTL source, testbench, and simulation results
- `2_Synthesis/` - Logic synthesis reports (timing, power, area, gates)
- `3_Floorplan/` - Die/core floorplanning
- `4_Powerplan/` - Power ring and stripe distribution
- `5_Placement/` - Standard cell placement and pre-CTS timing
- `6_cts/` - Clock tree synthesis
- `7_Routing/` - Global and detailed routing
- `8_Signoff/` - Final STA, DRC/LVS-style checks, and GDSII streamout

## Note on Repository Contents

Tool scripts (`.tcl`), constraint files (`.sdc`), and I/O configuration
files used in each stage have been excluded from this repository under
an NDA covering the PDK and flow scripts used during this internship.
Each stage folder instead contains a `.txt` summary describing the
tools, workflow, and key learnings from that stage, along with output
screenshots from Cadence Innovus/Genus.

See `PROJECT_REPORT.md.txt` for a full write-up of the project.
