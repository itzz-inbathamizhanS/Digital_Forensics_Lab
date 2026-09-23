# Experiment 04: Email Investigation and Mail Header Analysis (MHA)

## Objective
To extract and analyze the extended headers of email communications to trace the origin, identify spoofing mechanisms, and uncover malicious phishing or social engineering campaigns.

## Tools Utilized
* **Email Header Analyzers**: Various command-line and web-based parsing tools for decoding MIME structures and SMTP routing logs.

## Cybersecurity and Forensic Metrics Applied
* **Network Security Metrics**: Detection rates of SMTP routing anomalies, IP geolocation verification, and the validation of Sender Policy Framework (SPF), DomainKeys Identified Mail (DKIM), and Domain-based Message Authentication, Reporting, and Conformance (DMARC) failure rates.
* **Incident Response Metrics**: Rapid identification of malicious sender domains to prevent organizational compromise.

## Artifacts in this Directory
* `Exp_4.pdf` / `Exp_4.docx`: Step-by-step methodology and documented procedure.
* `Results/`: Raw email headers, extracted attachments, and parsed routing paths.
* `Screenshots/`: Visual confirmation of header anomalies and domain authentication failures.
