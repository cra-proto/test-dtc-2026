# Test DTC

*description of the project*

**Timeframe** 2026-11-05 - 2027-02-11

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-test-arc.canada.ca/test-dtc-2026](https://cra-test-arc.canada.ca/test-dtc-2026)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-11-19

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Taxes)
    node3(Tax credits and benefits for individuals)
    node4(Disability tax credit #40;DTC#41;)
    node5(What is the DTC)
    node6(Mental functions eligibility)
    node7(Who is eligible)
    node8(Dressing eligibility)
    node9(Feeding eligibility)
    node10(Eliminating eligibility)
    node11(Hearing eligibility)
    node12(Speaking eligibility)
    node13(Vision eligibility)
    node14(Life-sustaining therapy eligibility)
    node15(Cumulative effect eligibility)
    node16(New criteria page)
    node17(Walking eligibility)
    node18(How to apply)
    node19(CRA's review)
    node20(CRA's decision)
    node21(Claiming the credit – Disability tax credit #40;DTC#41;)
    node22(Get support for an issue)
    node23(Demystifying the disability tax credit)
    node1 --> node2
    node2 --> node3
    node3 --> node4
    node4 --> node5
    node5 --> node6
    node4 --> node7
    node7 --> node8
    node7 --> node9
    node7 --> node10
    node7 --> node11
    node7 --> node12
    node7 --> node13
    node7 --> node14
    node7 --> node15
    node7 --> node16
    node7 --> node17
    node4 --> node18
    node4 --> node19
    node4 --> node20
    node4 --> node21
    node4 --> node22
    node4 --> node23

    classDef inscope stroke:#7636ab,stroke-width:3px
    class node4,node5,node6,node7,node8,node9,node10,node11,node12,node13,node14,node15,node16,node17,node18,node19,node20,node21,node22,node23 inscope
    classDef isnew fill:#00706f,color:#fff
    class node16 isnew
    classDef ismoved fill:#eab308,color:#000
    class node6 ismoved
```
