# lfp-juxta

This repository contains codes and data used in the following paper:

"Spread of pathological human Tau from neurons to oligodendrocytes and loss of high-firing pyramidal neurons in ageing mice" by Tim J. Viney, Barbara Sarkany, A. Tugrul Ozdemir, Katja Hartwich, Judith Schweimer, David Bannerman, Peter Somogyi.

"unit analysis pipeline.nb" is a Mathematica (https://www.wolfram.com/mathematica/) notebook containing code that was used to analyse the units recorded from the hippocampal formation of mice navigating along a virtual corridor. Example data from the paper are included (zip file containing units from recording session TV145 LHS 842um L3, text file containing the theta epochs, and another text file containing the times of the detected theta troughs).

Circular statistics from the Mathematica notebook have also been included in a Jupyter notebook, "circular data functions.ipynb".

"LFP analysis emd.ipynb" is a Jupyter notebook with examples of how the LFP analysis was performed. Recording channels (wideband signals, downsampled to 1.25 kHz) are exported from Spike2 as ".mat" files (MATLAB version 6 format). Example files included in this repository: TV136, TV139, TV140, TV145, TV153.
