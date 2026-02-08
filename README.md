# USB-and-Network-Forensics-Investigation

# Rhino Case: USB and Network Forensics Investigation

## Overview
This repository documents a forensic investigation involving a USB storage device image and multiple network traffic captures. The objective was to recover image files, analyze user activity, and correlate evidence across storage media and network traces.

The investigation focuses on identifying illegal content, reconstructing file transfers, and determining user actions using standard forensic tools and methodologies.

---

## Case Background
In 2004, the city of New Orleans enacted legislation making possession of **nine or more unique rhinoceros images** a serious criminal offense.

Suspicious network activity was detected by a system administrator at the University of New Orleans. As a result, law enforcement seized:
- A laboratory computer (without an internal hard drive)
- A USB flash drive
- Three network traffic logs associated with the same system

The suspect is the primary user of the seized machine.

---

## Evidence Examined
The following evidence files were analyzed:

- `RHINOUSB.dd` – Forensic image of a USB flash drive  
- `rhino.log` – Network traffic capture  
- `rhino2.log` – Network traffic capture  
- `rhino3.log` – Network traffic capture  

### Evidence Integrity
All evidence files were validated using MD5 hash verification prior to analysis to ensure data integrity and chain-of-custody reliability.

---

## Tools Utilized
The following tools were used during the investigation:

- Autopsy / FTK – Forensic image analysis and file recovery  
- Wireshark – Network traffic inspection and protocol analysis  
- Stegdetect / Stegbreak – Steganography detection  
- Jphide / Jpseek – JPEG steganography analysis  
- Password recovery tools – Credential extraction from network data  

---

## Investigation Process

### USB Drive Analysis
- The USB image was examined using forensic analysis tools
- Deleted and hidden files were identified and recovered
- Image files were carved and validated
- File metadata and timestamps were analyzed

### Network Traffic Analysis
- Network captures were reviewed in Wireshark
- Telnet and FTP sessions were identified
- User credentials were recovered from plaintext traffic
- Relevant file transfer activity was reconstructed

### Steganography Examination
- Recovered images were analyzed for hidden content
- Embedded data was identified and extracted where present

---

## Findings

- Recovered **nine or more unique rhinoceros images**
- Identified FTP/Telnet account credentials
- Observed image file transfers within network traffic
- Determined the internal hard drive was deliberately removed
- Confirmed the USB device was actively used for storage and transfer
- Established a clear link between USB data and network activity through matching filenames and timestamps

---

## Conclusion
The investigation successfully demonstrates the recovery and correlation of digital evidence across removable media and network traffic. The findings show consistent user behavior across both evidence sources and confirm intentional actions to store, transfer, and conceal image files.

This case highlights the importance of secure protocols and proper handling of digital storage devices.

---

## Disclaimer
This repository is provided for **professional and educational demonstration purposes only**.  
All case details are handled in a controlled and lawful context.
