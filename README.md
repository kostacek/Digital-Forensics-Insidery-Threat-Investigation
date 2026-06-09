# Digital Forensics Investigation & Incident Reconstruction

## Overview

This project demonstrates the application of digital forensic methodologies to investigate a simulated financial fraud case. The objective was to acquire, preserve, analyze, and document digital evidence while maintaining forensic integrity and chain-of-custody principles.

The investigation focused on identifying evidence of fraud, recovering deleted artifacts, analyzing system activity, and reconstructing user actions through forensic examination of disk images and memory artifacts.

---

## Skills Demonstrated

- Digital Forensics
- Incident Investigation
- Evidence Acquisition
- Evidence Preservation
- Memory Analysis
- File System Analysis
- Browser Artifact Analysis
- USB Device Analysis
- Deleted File Recovery
- File Carving
- Timeline Reconstruction
- Hash Verification
- Forensic Reporting

---

## Tools Utilized

| Tool | Purpose |
|--------|---------|
| FTK Imager | Evidence acquisition and forensic image verification |
| Autopsy | Artifact analysis and deleted file recovery |
| Volatility 3 | Memory forensics and process analysis |
| Arsenal Image Mounter | Mounting forensic disk images |
| HxD | Hex analysis and file carving |
| DB Browser for SQLite | Examination of browser and application databases |
| Microsoft Excel | Data analysis and reporting |
| DCode | Timestamp and metadata decoding |

---

## Investigation Objectives

The examination sought to:

- Verify forensic image integrity
- Identify operating system information
- Determine file system structures
- Recover deleted files
- Analyze browser activity
- Identify USB device usage
- Investigate hidden artifacts
- Reconstruct user activity
- Correlate evidence supporting fraudulent activity
- Produce a professional forensic report

---

## Key Findings

### Evidence Integrity Verification

- Verified forensic image integrity using cryptographic hash validation.
- Confirmed evidence remained unchanged throughout the investigation process.

### Operating System Identification

- Identified the operating system through memory analysis using Volatility.
- Recovered system metadata and configuration information.

### File System Analysis

- Examined disk geometry and partition structures.
- Identified NTFS and FAT32 file systems.
- Accounted for disk utilization and partition allocation.

### Deleted Artifact Recovery

- Recovered deleted spreadsheet files from unallocated space.
- Performed file carving using Autopsy and HxD.
- Identified evidence of financial planning and hidden documentation.

### Browser Forensics

- Examined browser artifacts and bookmarks.
- Recovered evidence of research related to fraudulent financial activities.

### USB Device Analysis

- Identified multiple USB devices connected to the system.
- Recovered device identifiers and connection history.

### Memory Analysis

- Utilized Volatility 3 to examine memory artifacts.
- Recovered operating system details and active process information.

### User Activity Reconstruction

- Reconstructed suspect activities through artifact correlation.
- Established evidence supporting motive, means, and opportunity.

---

## Methodology

### Phase 1 – Evidence Acquisition

1. Verify image integrity
2. Mount forensic image
3. Preserve original evidence
4. Document acquisition process

### Phase 2 – Examination

1. Analyze file systems
2. Recover deleted files
3. Review browser artifacts
4. Examine USB history
5. Analyze memory artifacts

### Phase 3 – Analysis

1. Correlate recovered artifacts
2. Develop investigative timeline
3. Validate findings
4. Verify evidentiary integrity

### Phase 4 – Reporting

1. Document findings
2. Capture screenshots
3. Record methodology
4. Produce final forensic report

---

## Technologies & Concepts

- Digital Evidence Preservation
- Chain of Custody
- Memory Forensics
- Disk Forensics
- File Carving
- Hash Verification
- Incident Response
- Cyber Investigations
- Windows Forensics
- Artifact Analysis
- Security Investigations

---

## Repository Contents

```text
report/
└── Graduate_Digital_Forensic_Report.pdf

screenshots/
├── FTK-Imager
├── Autopsy
├── Volatility
├── Arsenal-Image-Mounter

README.md
