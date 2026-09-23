# Experiment 06: File System Analysis using The Sleuth Kit (TSK)

## Objective
To manually analyze volume and file system data at a low level using command-line tools to extract metadata, view deleted data nodes, and understand raw disk structures.

## Tool Utilized
* **The Sleuth Kit (TSK)**: A library and collection of command-line tools that allow for the investigation of disk images. 

## Cybersecurity and Forensic Metrics Applied
* **Data Recovery Metrics**: Success rate in inode/MFT record extraction, allocation status verification, and recovering deleted file nodes from the raw hex level.
* **Data Integrity Metrics**: Validation of raw image structures without reliance on high-level operating system APIs, ensuring unadulterated artifact retrieval.

## Artifacts in this Directory
* `Exp_6.pdf` / `Exp_6.docx`: Step-by-step methodology and documented procedure.
* `Results/`: TSK command outputs, extracted metadata logs, and recovered hex fragments.
* `Screenshots/`: Visual confirmation of terminal execution and file system layer analysis.
