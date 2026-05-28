# Flow Cytometry FCS Metadata Extractor

A Python utility built for flow cytometry workflows to automatically extract instrument metadata, cell/event counts, and channel configurations from binary `.fcs` data files.

## 📌 Project Overview
In a high-throughput flow cytometry core, tracking laser settings, fluorophore configurations, and event counts across thousands of files is a significant manual bottleneck. This tool automates quality control and usage auditing by parsing binary FCS data directly, removing the need for expensive, proprietary analysis software.

## 🔬 Core Facility Use Cases
* **Instrument QC:** Instantly verify that laser and detector channel configurations match standard operating procedures.
* **Usage Analytics:** Rapidly extract total event counts per sample file for high-throughput billing and utilization tracking.
* **Data Auditing:** Parse legacy files to confirm specific parameters and voltages used during older experiments.

## 🛠️ Built With
* **Python 3**
* **FlowCytometryTools** - Python library for parsing the flow cytometry standard binary format

## 🔒 Data Privacy & Security Note
This repository contains only source code workflows. Due to patient data privacy regulations (HIPAA/GDPR) and massive file sizes, actual instrument `.fcs` data files are strictly excluded from this repository via `.gitignore`.

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
