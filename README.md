# exploring-SEGY

Using a cropped volume from a post-stack time-migrated survey from New Zealand called Kora3D. Kora3D is made public thanks to the New Zealand Petroleum and Minerals.
I try to avoid putting all of the seismic survey into RAM so I can extend these functions to larger surveys. This results in building inline, xline, and time slices from the segy file directly.

Notebook outline:
1) View the 3200 byte EBCDIC header and defining trace headers
2) Look at a few individual traces
3) View survey geometry with some QC
4) Visualize cross-sections and time slices
