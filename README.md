# FoodSafe Compliance Informatics Platform (FCIP)

### An AI-Enabled Health Informatics Framework for FDA-Compliant Cross-Border Food Safety Monitoring and Supply Chain Traceability

**Author:** Janet Kolawole, MSc — Computational Health Informatics, University of Houston
**Contact:** janelandnet@gmail.com

---

## Overview

This repository documents the design and development of the **FoodSafe Compliance Informatics Platform (FCIP)** — an AI-enabled health informatics framework I am building to support regulatory compliance, food safety monitoring, and supply chain traceability for small and medium-sized food producers operating across international markets.

The framework combines three things I've worked with extensively in different parts of my career: regulatory compliance for cross-border food trade, machine learning methodologies from clinical health informatics, and workflow automation. FCIP brings these together into a pre-arrival compliance screening, documentation, and traceability system.

FCIP serves as a practical implementation of my broader endeavor to develop and deploy AI-enabled health informatics and regulatory compliance systems that improve food safety monitoring, supply chain traceability, FDA-compliant international trade, and public health outcomes for underserved communities in the United States.

---

## The Problem

Significant regulatory compliance gaps persist in the U.S. Food Import System, especially for Small and Medium-Sized Producers (SMPs) based in Sub-Saharan Africa and other developing economies. These producers supply culturally relevant food and health products to growing immigrant and underserved populations in the United States, but they generally lack accessible, easy-to-use systems to help them navigate FDA and USDA regulations before importing their products.

This creates a cycle of poor-quality imports, opaque supply chains, detained shipments at ports of entry, and public health risks that disproportionately affect the same vulnerable populations who rely on these products for cultural, nutritional, and economic reasons.

While health informatics, AI, and digital compliance systems have advanced significantly, these technologies have been applied almost exclusively in clinical healthcare settings. International food safety and cross-border trade compliance remain underserved by this kind of data-driven infrastructure — and that's the gap FCIP is designed to close.

### Why this matters nationally

FDA import refusals disproportionately affect producers from developing economies who lack institutional knowledge of U.S. regulatory pathways. According to FDA import data, food safety violations — including labeling failures, contamination risks, and documentation gaps — represent the most common grounds for shipment refusal. For underserved communities in the U.S., these refusals translate directly into reduced access to culturally appropriate food products and compounded nutritional and public health disparities.

At the same time, the U.S. government has identified expansion of African trade relationships as a national economic priority through frameworks including the African Growth and Opportunity Act (AGOA) and the Prosper Africa initiative. Closing the regulatory compliance gap for African food producers is therefore both a public health imperative and a national economic interest.

---

## My Background With This Problem

My involvement in international food product compliance for African foods spans from 2008 through 2025. From 2008 to 2019, I served as Production & Quality Assurance Manager at Janeland Networks Limited in Lagos, Nigeria, where I built quality systems from the ground up, developed SOPs, managed NAFDAC certification processes, and led cross-functional teams across production, quality, logistics, and sales. Since 2019, as a co-founder of Janeland Networks Global Group, I have volunteered my quality assurance and regulatory compliance expertise to support the company's U.S. import documentation and FDA compliance processes — drawing on the regulatory knowledge I developed during my eleven years of hands-on operations in Nigeria.

This combination of direct operational experience in Nigeria and ongoing co-founder involvement in U.S. compliance documentation — alongside my graduate training in Computational Health Informatics at the University of Houston — is what positions me to design and build FCIP.

### The moment that made the need for FCIP clear

In 2019, Janeland Networks received formal notification from the U.S. FDA that a physical inspection of our facility was scheduled. Although we had already completed the local NAFDAC inspection process, I had no idea what to expect from an international FDA inspection — and when I searched online for resources to help prepare, I found nothing accessible or practical.

The compliance gap was so significant that NAFDAC had to intervene directly: they organized a dedicated GMP (Good Manufacturing Practice) inspection to prepare us for the upcoming USFDA visit, and a NAFDAC director was present to observe the FDA inspection itself. Through that coordinated effort, the inspection was a success — but the experience revealed something important: two major regulatory agencies had to mobilize significant human resources to bridge a gap that a well-designed digital compliance system could have addressed automatically.

That experience — searching for FDA compliance preparation resources and finding nothing, then watching two regulatory bodies coordinate manually to fill the gap — is the founding problem that FCIP is designed to solve. Had a platform like FCIP existed, producers like Janeland could have accessed FDA requirements, identified compliance gaps, and prepared documentation independently, without requiring extraordinary institutional intervention.

### The regulatory duality problem

Food imports from Nigeria require compliance with two distinct regulatory systems — NAFDAC (Nigeria's National Agency for Food and Drug Administration and Control), which governs export certification, and the U.S. FDA, which governs market entry under FSMA and associated import regulations.

While both NAFDAC and the U.S. FDA continue to expand digital regulatory capabilities, they operate within different regulatory ecosystems, documentation structures, data standards, and compliance workflows. As a result, information generated within one system may not always align seamlessly with the verification and traceability requirements of the other. This creates interoperability challenges that can increase compliance preparation burdens for exporters and importers operating across jurisdictions.

The result is a structural compliance gap that exists not because the product is unsafe, but because the documentation systems used to certify compliance at origin are incompatible with the digital verification systems used at destination. This gap is invisible until the shipment reaches a U.S. port — at which point resolution requires manual intervention, port delays, and significant added costs.

### What I've observed at the border

Through my co-founder involvement and volunteer compliance support — including direct engagement with shipments to the U.S. — I have observed firsthand how heightened FDA scrutiny results in extended port holds due to:

- Documentation gaps between NAFDAC-issued export certificates and FDA-required preventive control verification records
- Labeling discrepancies between origin-country packaging standards and FDA labeling requirements under 21 CFR Part 101
- Absence of supplier verification records required under FSMA's Foreign Supplier Verification Program (FSVP)
- Traceability record gaps preventing automated clearance through FDA's PREDICT risk-scoring system

Every one of these issues is correctable — but only through manual documentation supplementation, direct engagement with FDA import specialists, and extended port holds during which costs continue to accumulate. These costs compound for small producers, reducing profit margins and limiting their ability to scale operations.

Critically, every deficiency observed at the U.S. border originated before shipping — in the gap between origin-country compliance documentation and U.S. FDA verification and traceability requirements. Had a pre-arrival compliance screening system existed, these gaps could have been identified and resolved before the shipment left Nigeria.

### Regulatory interoperability and the institutional layer

Regulatory agencies across the world continue to invest in modernization, digitization, and improved compliance oversight. In Nigeria, NAFDAC has implemented multiple initiatives to strengthen regulatory efficiency — including expanded digital registration processes, electronic verification systems, enhanced quality management frameworks, and broader adoption of technology-enabled regulatory services. These advancements represent important progress toward stronger regulatory governance and more efficient trade facilitation.

However, regulatory systems are developed to serve different legal, operational, and technological environments. As a result, documentation generated within one regulatory ecosystem may not always align seamlessly with the requirements, formats, traceability expectations, and verification processes used within another. For producers operating across multiple jurisdictions, these differences can create compliance preparation challenges even when products meet applicable safety and quality standards in their country of origin.

In practice, this means compliance documentation arriving at U.S. ports cannot always be automatically processed by digitally-integrated systems like FDA's PREDICT — not because the products are unsafe, but because the documentation formats, data structures, and verification trails differ across regulatory environments. This creates additional grounds for manual review, port holds, and heightened scrutiny that could be substantially reduced if compliance documentation were generated, standardized, and transmitted through an AI-enabled digital system designed to bridge these regulatory environments.

FCIP is designed to complement — not replace — existing regulatory systems by supporting interoperability, documentation readiness, traceability, and compliance preparation across regulatory environments.

### Who actually bears the cost

Small and medium-sized producers — the ones most likely to supply culturally relevant food products to immigrant and underserved communities — absorb these port delay costs directly. Unlike large multinational food corporations with dedicated compliance departments and established FDA relationships, small producers often cannot absorb these costs and may be forced to withdraw from the U.S. market entirely.

The downstream effect is reduced access to culturally appropriate food products for the communities that depend on them, increased reliance on substitutes that do not meet the same nutritional or cultural needs, and compounded food security disparities among immigrant populations.

---

## What This Tells Me About a Solution

Based on this experience, I see three requirements for an effective solution:

1. **Compliance screening must happen before shipment departure** — not at the U.S. border. Pre-arrival validation eliminates the cost and disruption of port holds by resolving gaps while remediation is still practical and affordable.

2. **The system must digitize and standardize compliance documentation across differing regulatory environments** — generating standardized digital records that support FDA compliance review and traceability requirements without requiring manual intermediary processing.

3. **The system must be accessible to small and medium-sized producers** — designed for low-resource environments, free or low-cost, and able to function where institutional regulatory infrastructure is limited.

These three requirements define the FCIP framework below.

---

## Health Informatics Foundation

FCIP is grounded in the field of Health Informatics — the collection, integration, analysis, and application of data to support decision-making, improve outcomes, and strengthen complex systems. While these methodologies are traditionally applied in clinical and healthcare settings, they are equally applicable to food safety and regulatory environments where public health protection depends on timely, accurate, and actionable information.

FCIP applies the following core health informatics principles:

**Predictive Analytics** — Using machine learning models to identify compliance risks before shipment departure.

**Risk Stratification** — Prioritizing shipments according to likelihood of regulatory deficiencies, food safety concerns, or documentation gaps.

**Decision Support** — Providing producers with actionable recommendations that improve regulatory readiness before export.

**Workflow Automation** — Reducing manual compliance burdens through automated documentation review and validation, implemented using n8n and REST API integration.

**Explainable AI** — Using interpretable machine learning techniques — SHAP for tabular risk models and Grad-CAM for image-based classification — to improve transparency and trust in compliance recommendations.

**Population-Level Monitoring** — Aggregating compliance and traceability data to identify broader trends affecting food safety, trade performance, and public health outcomes.

These methodologies form the technical foundation of FCIP and reflect competencies developed through my graduate training in Computational Health Informatics at the University of Houston, applied research in predictive analytics and machine learning, and direct experience building AI-enabled analytical systems.

---

## The FCIP Framework

FCIP is designed as four integrated modules: Compliance Risk Screening, Documentation Validation and Generation, Supply Chain Traceability, and Public Health Analytics.

### Module 1 — AI-Enabled Compliance Risk Screening

This module applies machine learning classification to assess shipment-level FDA compliance risk before departure. I'm drawing on the same methodologies I used in my clinical health informatics research — Random Forest, Logistic Regression, Naïve Bayes, and Decision Tree classifiers (see my diabetes risk prediction papers below) — and adapting them to food safety compliance risk prediction.

**Potential training data sources include:**
- FDA historical import refusal records (publicly available via the FDA Import Refusal Report database)
- Publicly available regulatory datasets
- Product registration records
- FDA compliance guidance documents
- Food traceability and supply chain datasets
- Relevant compliance documentation frameworks

The model generates a compliance risk score for each shipment, flagging documentation gaps, labeling discrepancies, and traceability issues before departure, with actionable guidance on exactly what's missing.

For interpretability, I'm applying explainable AI techniques — SHAP for the tabular risk model (Random Forest, Logistic Regression), and Grad-CAM, which I previously implemented in my maternal-fetal ultrasound classifier, reserved for future image-based compliance extensions (e.g., visual product inspection).

### Module 2 — Automated Documentation Validation and Generation

This module addresses structural incompatibilities between differing regulatory documentation systems and FDA's compliance verification requirements, through three functions:

- **Validation** — automated cross-referencing of submitted documentation against FSMA, 21 CFR labeling standards, and FSVP requirements, flagging gaps in real time
- **Standardization** — converting NAFDAC and equivalent origin-country certification records into standardized digital formats that support FDA compliance review and traceability requirements
- **Generation** — AI-assisted drafting of required compliance documentation (supplier verification records, preventive control plans, labeling certificates) based on producer-submitted data, reviewed against current FDA requirements before transmission

Workflow automation here uses low-code platforms like **n8n** — which I worked with directly through my Special Problem coursework with Mutree Solutions — to enable seamless data exchange between producer records, origin-country databases, and FDA import systems.

### Module 3 — Supply Chain Traceability Infrastructure

End-to-end digital documentation of product movement from production through export certification, transit, and U.S. port clearance:

- Digital lot-level tracking from production batch through customs clearance
- Tamper-evident audit trails compatible with FDA's Food Traceability Rule (FSMA Section 204)
- Real-time shipment status monitoring with automated compliance alerts
- Supplier verification record maintenance meeting FSVP requirements

### Module 4 — Public Health Analytics Dashboard

Aggregates compliance, traceability, and import data into population-level insights:

- Compliance risk trends by product category and origin country
- Import refusal pattern mapping to identify systemic compliance gap clusters
- Nutritional access monitoring for underserved community product categories
- Supplier compliance performance tracking for proactive intervention

These analytics are designed to be useful to FDA import program administrators, public health researchers, trade policy analysts, and community health organizations. FCIP's analytics infrastructure may also support population-level monitoring of food safety trends and emerging public health risks associated with imported food products — strengthening the intersection of health informatics, food safety surveillance, and national public health oversight.

---

## Technical Architecture
![FCIP High-Level System Architecture](fcip_architecture_v2.png)
| Component | Technology |
|---|---|
| Machine learning models | Python, scikit-learn, TensorFlow |
| Data processing pipelines | SQL, pandas, NumPy |
| Workflow automation | n8n, REST API integration |
| Dashboard and visualization | Power BI, Tableau, Streamlit |
| Traceability infrastructure | Structured database with audit logging |
| Deployment | Cloud-based, accessible via web interface |

This stack reflects tools I've used directly across my graduate research and professional work — predictive modeling, deep learning deployment, workflow automation, and interactive dashboards. The goal is for FCIP to be built on capabilities I've already demonstrated, not aspirational technology.

---

## Why This Matters

**Food safety as a national priority.** Food safety is a documented U.S. federal priority, codified in FSMA and enforced through FDA's import screening infrastructure. FCIP addresses compliance failures at the pre-arrival stage — where intervention is most effective and least costly — rather than at the border, where remediation is expensive and disruptive.

**Trade policy alignment.** By helping small and medium-sized food producers in Africa and other developing economies achieve consistent FDA compliance, FCIP supports U.S. trade policy objectives under AGOA and Prosper Africa — expanding compliant food imports, reducing the enforcement burden on FDA and CBP, and creating sustainable trade pathways.

**Health equity.** Consistent access to culturally relevant, FDA-compliant food products is a measurable factor in nutritional health and food security for immigrant and minority communities. By reducing compliance barriers for the producers who supply these communities, FCIP addresses food access disparities aligned with HHS national priorities.

**Reducing reliance on vulnerable certification processes.** By supplementing existing certification processes with AI-enabled screening and documentation support, FCIP reduces the vulnerability of compliance documentation to inconsistencies arising from cross-jurisdictional format differences — improving the reliability and integrity of documentation arriving at U.S. borders and supporting more efficient regulatory review.

---

## Related Work

This framework builds directly on my published research and deployed projects:

- **Kolawole, J. (2025a).** *Leveraging Machine Learning for Early Diabetes Risk Screening: An Applied Study Supporting Innovation in Preventive Health Solutions.* University of Houston Institutional Repository (UHIR #20927).
- **Kolawole, J. (2025b).** *Innovative Machine Learning Approaches for Predicting Type 2 Diabetes: An Applied Review Using the PIMA Indians Dataset.* University of Houston Institutional Repository (UHIR #20931).
- **Kolawole, J. (2026).** *Maternal-Fetal Ultrasound AI — Scan Plane Classifier with Grad-CAM.* [GitHub Repository](https://github.com/janelandnet-code/maternal-fetal-ultrasound-ai)
- **Kolawole, J. (2026).** *FoodSafe Compliance Informatics Platform (FCIP): A Technical Framework for AI-Enabled Regulatory Compliance, Food Safety, and Supply Chain Traceability* (Version 1.0). Zenodo. https://doi.org/10.5281/zenodo.21232063

## Roadmap

- [ ] Build compliance risk model using FDA historical import refusal data
- [ ] Develop data pipeline integrating FDA and other publicly available regulatory datasets
- [ ] Build Streamlit dashboard for compliance risk scoring
- [ ] Implement SHAP explainability for risk model outputs
- [ ] Pilot documentation validation module
- [ ] Expand traceability module with audit logging

---

## References

Bosona, T., & Gebresenbet, G. (2013). Food traceability as an integral part of logistics management in food and agricultural supply chain. *Food Control*, 33(1), 32-48.

Oldroyd, R.A., Morris, M.A., & Birkin, M. (2021). Predicting food safety compliance for informed food outlet inspections: A machine learning approach. *International Journal of Environmental Research and Public Health*, 18(23), 12635. https://doi.org/10.3390/ijerph182312635

FDA. (2011). FDA Food Safety Modernization Act. U.S. Food and Drug Administration.

U.S. Food and Drug Administration. (2023). *Import Refusal Reports.* https://www.fda.gov/food/compliance-enforcement-food/import-refusal-reports

Galvez, J.F., Mejuto, J.C., & Simal-Gandara, J. (2018). Future challenges on the use of blockchain for food traceability analysis. *TrAC Trends in Analytical Chemistry*, 107, 222–232.

Ge, L., Brewster, C., Spek, J., Smeenk, A., & Top, J. (2017). *Blockchain for agriculture and food: Findings from the pilot study.* Wageningen Economic Research Report 2017-112. https://doi.org/10.18174/426747

U.S. Department of Health and Human Services. (2022). Healthy People 2030: Food insecurity. Office of Disease Prevention and Health Promotion. https://odphp.health.gov/healthypeople/priority-areas/social-determinants-health/literature-summaries/food-insecurity

Hobbs, J.E. (2020). Food supply chain resilience and the COVID-19 pandemic. *Canadian Journal of Agricultural Economics*, 68(2), 171–176.

LeCun, Y., Bengio, Y., & Hinton, G. (2015). Deep learning. *Nature*, 521(7553), 436-444.

Shortliffe, E.H., & Cimino, J.J. (Eds.). (2014). *Biomedical Informatics: Computer Applications in Health Care and Biomedicine* (4th ed.). Springer. https://doi.org/10.1007/978-1-4471-4474-8

FDA. (2022). FDA Food Traceability Rule — FSMA Section 204. U.S. Food and Drug Administration. https://www.fda.gov/food/food-safety-modernization-act-fsma/fsma-final-rule-requirements-additional-traceability-records-certain-foods

FDA. (2023). Foreign Supplier Verification Programs (FSVP) for Importers of Food for Humans and Animals. U.S. Food and Drug Administration. https://www.fda.gov/food/food-safety-modernization-act-fsma/fsma-final-rule-foreign-supplier-verification-programs-fsvp-importers-food-humans-and-animals

WHO. (2022). WHO Global Strategy for Food Safety 2022–2030. World Health Organization. https://www.who.int/publications/i/item/9789240040519

---

## Contact

Janet Kolawole, MSc
Computational Health Informatics, University of Houston
janelandnet@gmail.com

