# Experiment 01: Forensic Data Acquisition using FTK Imager

## Objective
To acquire a complete, bit-stream forensic image of a target storage device or logical drive while ensuring zero data alteration and preserving the chain of custody.

## Tool Utilized
* **FTK Imager**: A premier data preview and imaging tool that allows for the creation of identical copies of data without making changes to the original evidence.

## Cybersecurity and Forensic Metrics Applied
* **Data Integrity Metrics**: Validation of the acquired image using cryptographic hashing algorithms, specifically MD5, SHA-1, and SHA-256. This ensures the bit-stream copy is identical to the source.
* **Evidence Acquisition Metrics**: Evaluation of logical and physical imaging time, verification time, and the identification of bad sectors or errors during the imaging process.

## Artifacts in this Directory
* `Exp_1.pdf` / `Exp_1.docx`: Step-by-step methodology and documented procedure.
* `Results/`: Generated hash files and acquisition logs.
* `Screenshots/`: Visual confirmation of the acquisition and verification phases.
