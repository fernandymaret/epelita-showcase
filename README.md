# e-PELITA
### elektronik - Pelayanan Hukum Bagi Masyarakat Tidak Mampu
[![Status](https://img.shields.io/badge/Status-Production-success)]()
[![Platform](https://img.shields.io/badge/Platform-Web-blue)]()
[![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red)]()

> Portfolio showcase of a digital legal service platform developed to improve public access to court services through an integrated online system.

---

## Background

Public legal services often require citizens to visit court offices physically to obtain information, legal consultation, submit requests, or access administrative services.

e-PELITA was developed as a digital transformation initiative that centralizes multiple public-facing court services into a single web platform, enabling easier access, faster response times, and improved service transparency.

---

## Objectives

- Improve accessibility of legal services
- Reduce physical visits to court offices
- Accelerate service delivery
- Increase transparency and accountability
- Support court digital transformation initiatives

---

## Core Services

### POSBAKUM Online

Legal aid services for underprivileged citizens.

Features:

- Online registration
- Legal consultation
- Service procedures
- Call center support
- Individual applications
- Organization applications

---

### Zitting Plaats

Circuit court service module.

Features:

- Service registration
- Consultation support
- Procedure guidance
- Information services

---

### Prodeo Services

Fee-waived court service module.

Features:

- Online application
- Consultation services
- Eligibility information
- Application guidance

---

### E-PTSP

Electronic One-Stop Integrated Services.

Available services:

- Criminal Division
- Civil Division
- Legal Division
- General Administration
- Priority Services
- Complaints
- Public Information

---

## System Architecture

```text
Citizens
    │
    ▼
┌─────────────────────┐
│      e-PELITA       │
│   Web Application   │
└──────────┬──────────┘
           │
 ┌─────────┼─────────┬─────────┐
 ▼         ▼         ▼         ▼

POSBAKUM  ZITTING   PRODEO   E-PTSP

                     │
                     ▼

         Court Service Units

                     │
                     ▼

               Database
```

---

## Service Workflow

```text
Citizen
   │
   ▼
Access e-PELITA
   │
   ▼
Select Service
   │
   ├── POSBAKUM
   ├── Zitting Plaats
   ├── Prodeo
   └── E-PTSP
           │
           ▼
Submit Request
           │
           ▼
Verification
           │
           ▼
Officer Handling
           │
           ▼
Status Update
           │
           ▼
Service Completion
```

---

## Key Benefits

### For Citizens

- Easier access to legal services
- Reduced travel and waiting time
- Online consultation availability
- Better service transparency

### For Court Administration

- Centralized service management
- Improved monitoring capabilities
- Reduced manual workload
- Enhanced service documentation

---

## Screenshots

### Landing Page

![Landing Page](docs/screenshots/landing-page.png)

### POSBAKUM Online

![POSBAKUM](docs/screenshots/posbakum.png)

### Online Consultation

![Consultation](docs/screenshots/consultation.png)

### E-PTSP Services

![E-PTSP](docs/screenshots/e-ptsp.png)

### Call Center

![Call Center](docs/screenshots/call-center.png)

---

## Project Status

Production System

---

## Ownership & Notice

This repository is maintained by Fernandy Maret Astriawan and published under the MarchTech brand.

The repository is intended exclusively for portfolio presentation, project documentation, and professional evaluation purposes.

Source code, production infrastructure, deployment configurations, sensitive data, proprietary implementation details, and operational data are not publicly available.

---

## License

All Rights Reserved.

See the LICENSE file for details.

© 2026 Fernandy Maret Astriawan — Developed under the MarchTech brand.
