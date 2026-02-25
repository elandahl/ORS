# How DePaul Faculty Can Use Argonne

```mermaid
flowchart LR

%% ---------- Styling (GitHub-safe) ----------
classDef start fill:#111827,stroke:#111827,color:#ffffff;
classDef decision fill:#f59e0b,stroke:#b45309,color:#111827;
classDef group fill:#e5e7eb,stroke:#6b7280,color:#111827;
classDef userfac fill:#dbeafe,stroke:#2563eb,color:#111827;
classDef edu fill:#dcfce7,stroke:#16a34a,color:#111827;

%% ---------- Diagram ----------
A["DePaul Faculty Member<br/>How can I use Argonne to advance my work?"]:::start
A --> B{"Choose Your Path"}:::decision

B --> UF["Conduct Research Using Argonne User Facilities"]:::group
B --> EDU["Engage Through Education & Talent Programs"]:::group

UF --> APS["APS<br/>Advanced Photon Source"]:::userfac
UF --> CNM["CNM<br/>Center for Nanoscale Materials"]:::userfac
UF --> ALCF["ALCF<br/>Leadership-class Supercomputing"]:::userfac

EDU --> FP["Faculty Programs"]:::edu
EDU --> GP["Graduate Programs"]:::edu
EDU --> UG["Undergraduate Programs"]:::edu
EDU --> PCI["Professional & Career Internship Program (PCI)"]:::edu

%% ---------- Links ----------
click APS "https://www.aps.anl.gov/Users-Information/About-Proposals/Apply-for-Time"
click CNM "https://cnm.anl.gov/pages/user-information"
click ALCF "https://www.alcf.anl.gov/get-started"

click FP "https://www.anl.gov/education/faculty-programs"
click GP "https://www.anl.gov/education/graduate-programs"
click UG "https://www.anl.gov/education/undergraduate-programs"
click PCI "https://www.anl.gov/education/professional-career-internship-program"
click UG "https://www.anl.gov/education/undergraduate-programs"
click PCI "https://www.anl.gov/education/professional-career-internship-program"
