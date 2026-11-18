# Case 001: Data Leakage Investigation

 
| Field | Value |
|---|---|
| Case number | 001 |
| Case name | Data Leakage (NIST CFReDS) |
| Examiner | Joseph Guidici |
| Report version | 0.1 (draft) |
| Date started | 2026-11-17 |
| Date completed | YYYY-MM-DD |
| Status | In progress |

---

## Table of Contents
 
1. [Executive Summary](#1-executive-summary)
2. [Case Background and Scope](#2-case-background-and-scope)
3. [Evidence Inventory and Integrity](#3-evidence-inventory-and-integrity)
4. [System Profile](#4-system-profile)
5. [User Accounts and Activity](#5-user-accounts-and-activity)
6. [Communications with the Suspected Conspirator](#6-communications-with-the-suspected-conspirator)
7. [Web and Search Activity](#7-web-and-search-activity)
8. [File Access and Confidential Data](#8-file-access-and-confidential-data)
9. [Removable Media Analysis](#9-removable-media-analysis)
10. [Consolidated Timeline](#10-consolidated-timeline)
11. [Findings Summary](#11-findings-summary)
12. [Conclusions](#12-conclusions)
13. [Appendices](#13-appendices)

---

## 1. Executive Summary


---

## 2. Case Background and Scope


---

## 3. Evidence Inventory and Integrity

| Evidence ID | File name | Description | Size | MD5 |
|---|---|---|---|---|
| E-001 (1/4) | `cfreds_2015_data_leakage_pc.E01` | Suspect's personal computer segmented into 4 images | 2147463521 | 7338dbed7d2293334801416613bc17b5 |
| E-001 (2/4) | `cfreds_2015_data_leakage_pc.E02` | Suspect's personal computer segmented into 4 images | 2147452984 | 51675274ad9eb6a15d0e562d10a4913f |
| E-001 (3/4) | `cfreds_2015_data_leakage_pc.E03` | Suspect's personal computer segmented into 4 images | 2147469124 | 7a21bf1b6db3ce433c55ac76749f12d9 |
| E-001 (4/4) | `cfreds_2015_data_leakage_pc.E04` | Suspect's personal computer segmented into 4 images | 1382823825 | 62f6cce2ec9e1b1f7a21cef0d12e0e38 |
| E-002 | `cfreds_2015_data_leakage_rm#1.E01` | USB removable media (SN: #) | 78186742 | 7cd7bc148d3a1e5f329cb3580d4d4f8f |
| E-003 | `cfreds_2015_data_leakage_rm#2.E01` | USB removable media (SN: #) | 255051328 | 6cfbfdb14e0a504684a338b87362d753 |
| E-004 | `cfreds_2015_data_leakage_rm#3_type3.E01` | CD media (SN: #) | 94594894 | b49cb0c7dfccb8cd0e39424e3f1abc86 |

The full chain of custody and examiner notes are kept in [case-log.md](./case-log.md).

---

## 4. System Profile

| Attribute | Value | Source artifact |
|---|---|---|
| OS name / version | | `SOFTWARE\Microsoft\Windows NT\CurrentVersion` |
| Install date | | `SOFTWARE\...\CurrentVersion\InstallDate` |
| Registered owner | | `SOFTWARE\...\CurrentVersion\RegisteredOwner` |
| Computer name | | `SYSTEM\...\ComputerName\ComputerName` |
| Time zone | | `SYSTEM\...\Control\TimeZoneInformation` |
| Last shutdown | | `SYSTEM\...\Control\Windows\ShutdownTime` |
| Network interfaces / IPs | | `SYSTEM\...\Tcpip\Parameters\Interfaces` |
| Installed applications | See 5.1 | `SOFTWARE\...\Uninstall` |

### Installed Applications of Interest

| Application | Version | Install date | Relevance |
|---|---|---|---|
| | | | |

---

## 5. User Accounts and Activity

| Username | RID | Created | Last logon | Logon count | Source |
|---|---|---|---|---|---|
| | | | | | SAM |

---

## 6. Communications with the Suspected Conspirator

### Email Client

| Attribute | Value | Source artifact |
|---|---|---|
| Email client | | |
| Mail store location | | e.g. `.pst` / `.ost` path |
| Suspect's email address | | |
| Conspirator's email address | | |

### Relevent Messages

| Date/time (UTC) | From | To | Subject | Attachments (name / hash) | Summary |
|---|---|---|---|---|---|
| | | | | | |

---

## 7. Web and Search Activity

### Browser Client

| Browser | Version | History location |
|---|---|---|
| | | |

### Relevent Searches

| Date/time (UTC) | Browser | URL / search term | Relevance |
|---|---|---|---|
| | | | |

---

## 8. File Access and Confidential Data


---

## 9. Removable Media Anaylsis

### 11.1 RM#2 (USB)
 
| Attribute | Value |
|---|---|
| File system | |
| Volume serial | |
| Volume label | |
| Correlates to PC USB entry | |
 
**Contents (allocated and deleted):**
 
| File | Status | Size | Hash | Timestamps | Notes |
|---|---|---|---|---|---|
| | | | | | |
 
### 11.2 RM#3 (CD-R)
 
| Attribute | Value |
|---|---|
| File system / sessions | |
| Volume label | |
| Correlates to PC burn activity | |
 
**Contents (including deleted/prior sessions):**
 
| File | Status | Size | Hash | Timestamps | Notes |
|---|---|---|---|---|---|
| | | | | | |
 
---

## 10. Consolidated Timeline


---

## 11. Findings Summary


---

## 12. Conclusions


---

## 13. Appendices

### Artifact Locations Reference
 
| Artifact | Location |
|---|---|
| | |
