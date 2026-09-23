# Experiment 07: Mobile Device Forensics using AF Logical

## Objective
To logically acquire and analyze artifacts from an Android mobile device, including call logs, SMS messages, contacts, and application data.

## Tool Utilized
* **AF Logical OSE / Android Forensics Tools**: Tools designed to extract data from Android devices over an ADB (Android Debug Bridge) connection using logical acquisition methods.

## Cybersecurity and Forensic Metrics Applied
* **Evidence Acquisition Metrics**: Measurement of logical extraction speed, artifact preservation capabilities, and handling of database file locks on mobile operating systems.
* **Data Integrity Metrics**: Ensuring that the logical extraction client minimizes writes to the target device, maintaining the highest possible standard of chain of custody for live devices.

## Artifacts in this Directory
* `Exp_7.pdf` / `Exp_7.docx`: Step-by-step methodology and documented procedure.
* `Results/`: Extracted SQLite databases, CSV exports of call logs/messages.
* `Screenshots/`: Visual confirmation of the extraction process and database parsing.
