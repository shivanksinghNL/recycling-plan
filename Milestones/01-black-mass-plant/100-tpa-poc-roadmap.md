# 100 TPA Black-Mass Proof-of-Concept Roadmap

## Recommended Capacity

**100 TPA is the recommended operational proof-of-concept (POC) scale.** It equals approximately 8.3 tonnes per month, or 0.33 tonnes per working day across 300 operating days. Process it in planned, traceable batches rather than continuous production.

Capacity should progress as follows:

| Scale | Role | Decision |
|---|---|---|
| 1 TPA | Handling, documentation, and buyer-sample trial | Too small to validate plant economics or justify processing equipment |
| **100 TPA** | **Operational POC** | Validate supply, safety, compliance, black-mass quality, and buyer acceptance |
| 1,000 TPA | First small commercial black-mass plant | Build only after the POC proves reliable feedstock and offtake |

At 100 TPA, do not buy a full shredding line. Use a tolling or trial arrangement with a properly registered and permitted recycler for any battery breaking, shredding, or black-mass processing. This preserves capital while producing the evidence needed for a 1,000-TPA investment.

## POC Workflow

```mermaid
flowchart LR
    A["01 · Feedstock<br/>Suppliers and 100-TPA pipeline"] --> B["02 · Controlled Intake<br/>Weigh, inspect and document"]
    B --> C["03 · Classification<br/>Chemistry, condition and traceability"]
    C --> D["04 · Safe Storage<br/>Segregation and quarantine"]
    D --> E["05 · Permitted Processing<br/>Tolling partner converts batteries"]
    E --> F["06 · Product Control<br/>Black mass, Cu/Al and mass balance"]
    F --> G["07 · Quality Assurance<br/>Independent assay and buyer approval"]
    G --> H{"POC Gate<br/>Safety, compliance and economics"}
    H -->|"Pass"| I["08 · Scale Decision<br/>Prepare 1,000-TPA investment case"]
    H -->|"Improve"| J["Correct supplier, process or buyer terms"]
    J --> B

    classDef process fill:#E8F3F1,stroke:#16736A,color:#123C39,stroke-width:1.5px;
    classDef partner fill:#FFF6E3,stroke:#B67816,color:#5C4008,stroke-width:1.5px;
    classDef gate fill:#FDEBEC,stroke:#B42318,color:#6E1710,stroke-width:2px;
    class A,B,C,D,F,G,I,J process;
    class E partner;
    class H gate;
```

The diagram is deliberately partner-led: at 100 TPA, the business validates the complete controlled workflow before it owns capital-intensive processing equipment.

## POC Context Diagram

```mermaid
flowchart TB
    P["100-TPA POC<br/>Collection, traceability and commercial control"]

    subgraph Operations["Operational ecosystem"]
        S["Battery suppliers<br/>OEMs, fleets, aggregators and manufacturing scrap"]
        L["Licensed logistics provider"]
        R["Permitted recycler / tolling partner"]
        B["Domestic refiner / buyer"]
    end

    subgraph Assurance["Assurance and governance"]
        Q["Independent laboratory"]
        C["CPCB / GPCB and other authorities"]
        F["Bank, insurer and investors"]
    end

    S <-->|"Feedstock · data · settlement"| P
    L <-->|"Manifests · transport · delivery proof"| P
    R <-->|"Batch instructions · processing records · outputs"| P
    B <-->|"Specification · assay · offtake settlement"| P
    Q <-->|"Samples · certificate of analysis"| P
    C <-->|"Registration · consent · returns · inspections"| P
    F <-->|"Funding · insurance · governance reporting"| P

    classDef core fill:#0F5B54,stroke:#0B403B,color:#FFFFFF,stroke-width:2px;
    classDef operations fill:#E8F3F1,stroke:#16736A,color:#123C39,stroke-width:1.5px;
    classDef assurance fill:#FFF6E3,stroke:#B67816,color:#5C4008,stroke-width:1.5px;
    class P core;
    class S,L,R,B operations;
    class Q,C,F assurance;
```

The POC remains responsible for traceability and commercial control even when licensed partners perform logistics and processing.

## POC Objectives

- Process 100 tonnes of documented, chemistry-segregated battery feedstock over up to 12 months
- Establish a repeatable chain of custody from supplier to domestic refiner/offtaker
- Demonstrate safe handling, storage, discharge, transport, and batch traceability
- Obtain independent black-mass assays and written buyer feedback
- Measure actual collection, transport, tolling, testing, and selling costs

## Roadmap

| Phase | Target outcome | Evidence required to proceed |
|---|---|---|
| 1. Define the POC | Select feed chemistry, supply source, and domestic refiner/offtaker | Signed POC scope, material specification, and buyer quality requirements |
| 2. Prepare compliance and safety | Establish the legal entity, handling procedures, training, traceability, storage controls, and applicable approvals | Written confirmation of CPCB/GPCB requirements and approved safety plan |
| 3. Secure feedstock | Build a documented 100-TPA supplier pipeline | Supplier LOIs/contracts, chain-of-custody records, weights, and condition records |
| 4. Run partner batches | Process planned batches through the permitted operating model | Processing agreement, batch records, recovery data, and residue-disposal records |
| 5. Qualify output | Produce buyer-evaluated black mass from multiple batches | Certificates of analysis, moisture/contamination results, and written buyer feedback |
| 6. Make the scale decision | Choose whether to launch a 1,000-TPA plant | Actual unit economics, safety review, compliance audit, and signed offtake/supply commitments |

## Required Deliverables

- At least 100 tonnes of fully traceable battery feedstock, segregated by chemistry where possible
- Supplier, transport, permitted-processing, and black-mass offtake/tolling agreements
- Safety and emergency-response procedures
- Batch mass balances: input batteries, black mass, copper, aluminium, residues, and disposal route
- Independent assay results for each representative batch
- Actual unit-cost and cash-cycle model

## Transition: 100 TPA → 1,000 TPA

Build a 1,000-TPA plant only after at least three successful representative batches, a credible pipeline for at least 70% of 1,000-TPA annual feedstock, a domestic buyer or tolling partner with agreed specifications, no unresolved safety or compliance findings, and a positive or clearly improvable contribution margin.
