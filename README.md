# Splunk Enterprise Configuration

## Overview

This section documents the basic configuration performed after installing Splunk Enterprise on Linux.

The configuration prepares the Splunk environment for log ingestion, indexing, searching, and security monitoring.

---

## 1. Splunk Configuration

After completing the installation, Splunk Enterprise was accessed through the Splunk Web interface.

The configuration phase focuses on preparing the Splunk environment for log analysis.

---

## 2. Index Configuration

Indexes are used by Splunk to store and organize indexed data.

The indexes used in this lab include:

- `main`
- `windowslogs`

The `main` index is the default Splunk index, while `windowslogs` is used for Windows-related log data.

---

## 3. Creating the Windows Logs Index

A dedicated index named `windowslogs` was configured to organize Windows event log data.

This allows Windows-related events to be searched independently.

Example SPL search:

```spl
index="windowslogs"
