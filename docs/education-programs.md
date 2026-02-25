
---

# 📄 File 2: `docs/education-programs.md`

```markdown
# Argonne Education & Talent Programs  
## Faculty · Graduate · Undergraduate · PCI

Argonne provides structured programs that connect DePaul faculty and students to research appointments, internships, and workforce pipelines.

These programs support both technical and non-technical pathways.

---

```mermaid
flowchart LR

classDef start fill:#111827,stroke:#111827,color:#ffffff;
classDef edu fill:#dcfce7,stroke:#16a34a,color:#111827;
classDef step fill:#e5e7eb,stroke:#6b7280,color:#111827;

A["DePaul Faculty Member"]:::start --> B{Who are you engaging?}

B --> FP["Faculty Programs"]:::edu
B --> GP["Graduate Students"]:::edu
B --> UG["Undergraduate Students"]:::edu
B --> PCI["Professional & Career Internship Program"]:::edu

FP --> FP1["Visiting appointments<br/>Sabbatical research<br/>Guest scientist collaborations"]:::step

GP --> GP1["Research internships<br/>Graduate appointments<br/>Specialized research schools"]:::step

UG --> UG1["Summer research programs<br/>Community college programs<br/>STEM research internships"]:::step

PCI --> PCI1["Paid internships<br/>Technical + non-technical roles<br/>Business, policy, communication, computing"]:::step
