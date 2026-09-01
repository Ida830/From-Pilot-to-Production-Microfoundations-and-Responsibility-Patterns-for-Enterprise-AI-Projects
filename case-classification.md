# Table A1. Responsibility Classification

Supplementary material for: **From Pilot to Production: Microfoundations and Responsibility Patterns for Enterprise AI Projects**  
ICIS 2026 — Daniel Hendriks, Ida Meier, Henrik Wiegand, Carina Benz, Daniel Heinz, Philipp Spitzer  
Karlsruhe Institute of Technology, Karlsruhe, Germany

---

| Case | Pattern | Piloting | Productionizing | Piloting Justification | Productionizing Justification |
|------|---------|----------|----------------|------------------------|-------------------------------|
| 1A | Domain-driven | Domain-led | Domain-led | Business unit initiates use case; embedded AI team builds prototype with domain feedback [I1] | Output accountability explicitly retained on domain side: "account teams are responsible for what this AI module produces" [I1] |
| 2B | Domain-driven | Domain-only | Domain-only | Process mining team originates and builds with process owners; no central IT involvement in piloting [I2, I3] | Chief POs (BU) prioritize and govern; BU handles training; technical team only maintains the model [I2, I3] |
| 3C | Domain-driven | Domain-led | Domain-led | Domain-specific development; business and digital teams in one organizational unit with daily joint standups [I4] | Integrated DevOps team develops and runs solution continuously; business use cases remain in domains [I4] |
| 6J | Domain-driven | Domain-led | Domain-led | Embedded data scientist and domain leads drive design; Partner advises on CRM integration [I11] | Business owns rollout planning, training materials, and maintenance; IT provides infrastructure support [I11] |
| 6I | Handover | Tech-led | Domain-led | Central AI team leads development: "for development it's 0–100" tech; business contributes testing [I10] | Business holds 100% go/no-go responsibility; owns FAQ data, communications, and rollout deadlines [I10] |
| 6K | Handover | Tech-led | Domain-led | Central IT and partner lead build; BU champion provides personas and content requirements [I12] | BU champion dedicates 50% of time to change management; BU owns backlog and community calls [I12] |
| 6L | Handover | Tech-led | Domain-led | Central AI team builds; legal department defines requirements and tests outputs iteratively [I13] | Legal department named as tool owner; runs demos and training; oversees rollout to thousands of users [I13] |
| 6M | Handover | Tech-led | Domain-only | "The lead was always on the central IT side"; Partner architect guides development direction [I14] | Domain runs all first- and second-level operations; IT reduced to third-level support only [I14] |
| 4D | Tech-driven | Tech-led | Tech-led | AI-affine IT department head drives identification; consultancy builds PoC; domain consulted [I5] | IT department leads workshops and enablement; consultancy remains for follow-up development [I5] |
| 7H | Tech-driven | Tech-led | Tech-led | AI/Data Science team owns pipeline and model development; site supports labeling only [I9] | AI/DS team retains data drift, model drift, and weekly KPI monitoring; site performs QC checks [I9] |
| 7N | Tech-driven | Tech-led | Balanced | Central AI hub builds after external innovation challenge; business PM absent initially [I15] | Business PM added for adoption; tech retains maintenance; enablement shifted to domain over time [I15] |
