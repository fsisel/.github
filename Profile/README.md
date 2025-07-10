# IFS GitHub Organization

Welcome to the **IFS GitHub Organization**. This organization is structured into distinct teams, each responsible for specific domains of the project.

## 🔧 Teams

- **Electronics** – Handles all hardware and embedded systems.
- **Powertrain** – Responsible for the vehicle's propulsion systems.
- **Web** – Manages the website and related frontend/backend services.
- **Driverless** – Develops autonomous and computer vision systems.

---

## 🚀 Repository Development Guide

All repositories in this organization follow a consistent Git workflow.

### Branching Strategy

- **`main`**  
  The default branch. Always stable and production-ready.

- **Development branches** (used during active development):
  - `dev` or `development`: General development branch.
  - `feat/<feature-name>`: Feature-specific branch.
  - `fix/<bug-name>`: Bugfix-specific branch.

### Releases

- When a new version is complete:
  1. Create a **tag** to mark the version.
  2. (Recommended) Create a **release** and include any relevant notes or binaries. For example, version `v2022.2023` represented the stable 2022–2023 release and successfully passed scrutineering.


---

## 👥 Team Roles and Access

| **Team**        | **Role Description**                             | **Permissions**                                                |
|-----------------|--------------------------------------------------|----------------------------------------------------------------|
| **Electronics** | Members working on electronics and embedded      | ✅ Clone<br>✅ Read<br>✅ Write to Electronics repositories     |
| **Powertrain**  | Members responsible for the vehicle’s powertrain | ✅ Clone<br>✅ Read<br>✅ Write to Powertrain repositories      |
| **Web**         | Web developers maintaining the site              | ✅ Clone<br>✅ Read                                             |
| **Driverless**  | Members building autonomous systems              | ✅ Clone<br>✅ Read<br>✅ Write to Driverless repositories      |

> ℹ️ **Note**: All members have *read-only* access by default unless specified otherwise.
