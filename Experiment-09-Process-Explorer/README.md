# Experiment 09: Live System Analysis using Process Explorer

## Objective
To conduct a live system forensic analysis to monitor running processes, identify malicious persistence mechanisms, and detect anomalous behaviors indicative of an active compromise.

## Tool Utilized
* **Sysinternals Process Explorer**: An advanced process management utility that provides detailed insight into active processes, loaded DLLs, memory mapping, and network connections.

## Cybersecurity and Forensic Metrics Applied
* **Incident Response Metrics**: Decreasing the Mean Time to Detect (MTTD) by identifying anomalous parent-child process relationships, unsigned binaries, and unauthorized network connections.
* **Malware Analysis Metrics**: Tracking dynamic execution behavioral flags, such as unauthorized memory injections, unexpected thread creation, or anomalous registry key handles.

## Artifacts in this Directory
* `Exp_9.pdf` / `Exp_9.docx`: Step-by-step methodology and documented procedure.
* `Results/`: Process tree exports, DLL logs, and identified anomaly reports.
* `Screenshots/`: Visual confirmation of malicious process identification and handle inspection.
