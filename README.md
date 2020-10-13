# DCC
DCC: dynamic compilation of core gene sets

1: Download the OMA files from https://omabrowser.org/oma/current/
Required files:

- OMA groups in Text format
- Protein sequences in Fasta format
- Species information Text format

save it in the folder: DCC/data

2: move into the folder script and run createDic.py

3: Download and install the following libraries:

Python3:

- os
- sys
- json
- time
- multiprocessing
- coreapi

R 3.6:
- shiny
- shinyjs
- shinyalert
- data.table
- shinyDirectoryInput
