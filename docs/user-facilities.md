# Using Argonne User Facilities  
## APS · CNM · ALCF

Argonne’s User Facilities allow DePaul faculty to access world-class instruments and computing infrastructure through proposal-based or allocation-based systems.

These facilities are open to university researchers nationwide.

---

```mermaid
flowchart LR

classDef start fill:#111827,stroke:#111827,color:#ffffff;
classDef facility fill:#dbeafe,stroke:#2563eb,color:#111827;
classDef step fill:#e5e7eb,stroke:#6b7280,color:#111827;

A["DePaul Faculty Research Goal"]:::start --> B{Which capability do you need?}

B --> APS["APS<br/>X-ray beamtime"]:::facility
B --> CNM["CNM<br/>Nanofabrication & characterization"]:::facility
B --> ALCF["ALCF<br/>High-performance computing & AI"]:::facility

APS --> APS1["1. Identify beamline<br/>2. Contact beamline scientist<br/>3. Submit proposal via UPS<br/>4. Complete training & run experiment"]:::step

CNM --> CNM1["1. Register as user<br/>2. Discuss feasibility with staff<br/>3. Submit proposal in CNM portal<br/>4. Schedule instrument time"]:::step

ALCF --> ALCF1["1. Choose allocation path (DD / INCITE / ALCC)<br/>2. Submit computing request<br/>3. Add collaborators<br/>4. Begin runs"]:::step
