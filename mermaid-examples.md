# 🧬 Mermaid Diagrams & Visualizations

Here are some examples of biological signalling cascades, metabolic cybernetics pathways, and research workflows constructed using **Mermaid.js**.

---

## 1. Adrenaline Signalling Pathway (Heart Rate Control)
Demonstrating G-protein-coupled receptor activation leading to physiological change.

```mermaid
sequenceDiagram
    autonumber
    actor Adr as Adrenaline (Ligand)
    participant R as β1-Adrenergic Receptor
    participant G as Gs Protein (α-subunit)
    participant AC as Adenylyl Cyclase
    participant PKA as Protein Kinase A
    participant Heart as Cardiac Myocytes

    Adr->>R: Binds & activates receptor
    R->>G: Conformational change & activates
    G->>AC: Stimulates AC enzyme
    AC->>PKA: Converts ATP to cAMP -> activates PKA
    PKA->>Heart: Phosphorylates Ca²⁺ channels
    Note over Heart: Physiological effect:<br/>Tachycardia & ↑ Contractility
```

---

## 2. Metabolic Feedback Control (Metabolic Cybernetics)
A negative feedback loop illustrating homeostasis.

```mermaid
stateDiagram-v2
    [*] --> Inactive_Gs: GDP bound
    Inactive_Gs --> Active_Gs: Ligand binding induces GDP-GTP exchange
    Active_Gs --> Effector_Binding: α-subunit dissociates to activate AC
    Effector_Binding --> Inactive_Gs: Intrinsic GTPase hydrolyses GTP to GDP
```

---

## 3. Marine Trophic Energy Flow
Energy transfer across trophic levels in a marine ecosystem.

```mermaid
sankey-beta
    Solar Energy,Primary Producers (Phytoplankton),1000
    Primary Producers (Phytoplankton),Zooplankton,100
    Primary Producers (Phytoplankton),Heat Loss / Respiration,900
    Zooplankton,Small Fish,10
    Zooplankton,Heat Loss,90
    Small Fish,Apex Predators,1
    Small Fish,Heat Loss,9
```

---

[⬅️ Back to Profile Overview](README.md)
