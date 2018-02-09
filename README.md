# Mouse
A PluMA pipeline that runs the MiSeq SOP metagenomics example from the Mothur tutorial, followed by some downstream analysis.

Mothur Tutorial is available at: https://www.mothur.org/wiki/MiSeq_SOP
Results of their experiment were published in:

Kozich JJ, Westcott SL, Baxter NT, Highlander SK, Schloss PD. (2013): Development of a dual-index sequencing strategy and curation pipeline for analyzing amplicon sequence data on the MiSeq Illumina sequencing platform. Applied and Environmental Microbiology. 79(17):5112-20.


To run this pipeline:

1. Clone this repository into the pipelines/ directory of PluMA.
2. Change to the new Mouse/ subdirectory.
3. Run ./getPlugins.sh to automatically download all relevant PluMA plugins.
4. Change to the PluMA root directory: 'cd ../../'
5. Run 'scons perl=0'
6. Run './pluma pipelines/Mouse/config.Mouse.txt'

