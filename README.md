# IDS-Extra-Vehicle

> Research on Intrusion Detection Systems (IDS) for secure Vehicle-to-Cloud communication in the Internet of Vehicles (IoV).

## Overview

This repository is an extension of my undergraduate final project, which focused on **Intrusion Detection Systems (IDS) for In-Vehicle Networks**.

The scope of this research shifts from **In-Vehicle security** to **Extra-Vehicle communication**, specifically the communication between vehicles and cloud/server infrastructure. The objective is to study communication security in Internet of Vehicles (IoV) environments, with a focus on protecting data exchange between vehicles and cloud services.

---

## Research Objectives

The main objectives of this research are:

- Investigate secure methods for transmitting data from vehicles to cloud servers.
- Study IDS approaches for Vehicle-to-Cloud communication.
- Study IDS deployment on the server/cloud side.
- Detect **Man-in-the-Middle (MitM)** attacks.
- Detect **Eavesdropping** attacks.
- Detect **False Data Injection Attacks (FDIA)**.
- Detect **Jamming** attacks.

---

## Research Scope

This research focuses on:

- Vehicle-to-Cloud communication.
- Communication network security between vehicles and cloud servers.
- Intrusion Detection Systems (IDS).
- Network attack detection.
- Open-source datasets.

---

## Limitations

The scope of this research is limited to the following:

- Focuses on **Extra-Vehicle Communication**, not In-Vehicle Networks.
- Does not cover attack prevention or mitigation.
- IDS is used for **detection only**.
- Uses publicly available (open-source) datasets.
- Does not use self-generated datasets.

---

## Attack Scenarios

The research focuses on detecting the following attacks:

- Man-in-the-Middle (MitM)
- Eavesdropping
- False Data Injection Attack (FDIA)
- Jamming Attack

---

## Dataset

This research uses publicly available (open-source) datasets selected according to the requirements of each attack scenario.

---

## Research Architecture

```text
Vehicle
    │
    ▼
=============================
 Vehicle-to-Cloud Network
      (Research Focus)
=============================
    │
    ▼
Server / Cloud
```

The research focuses on securing the communication channel between vehicles and cloud servers by detecting attacks during data transmission.

---

## Relationship to the Previous Project

| Previous Project | This Project |
|------------------|--------------|
| In-Vehicle IDS | Extra-Vehicle IDS |
| CAN & Automotive Ethernet | Vehicle-to-Cloud Communication |
| Internal Vehicle Network | External Communication Network |
| In-Vehicle Attack Detection | Vehicle-to-Cloud Attack Detection |

---

## Status

🚧 Research in Progress.
