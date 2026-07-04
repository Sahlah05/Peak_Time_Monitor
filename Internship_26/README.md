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

*Flow scripts and constraint files are omitted; each stage folder includes a summary and output screenshots instead.*


See `PROJECT_REPORT.md.txt` for a full write-up of the project.
