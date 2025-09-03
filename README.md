# AcrobatUx

Research and development at the intersection of **user experience**, **security and privacy**, and **decentralized infrastructure**.
Goal: publish **reproducible** UX research, prototypes, and tools that shorten time-to-value in **healthcare**, **cybersecurity**, **DePIN**, and **accessible AI**.

---

## Domains and canonical problems

### Healthcare

* Patient intake, surgical coordination, clinician decision support under cognitive load
* Accessibility in clinical UIs (WCAG 2.2 AA), audit trails, safety-critical interaction
* Data handling without PHI leakage; de-identification and synthetic data workflows

### Cybersecurity and privacy

* Usable cryptography: key management, MFA, threshold shares and recovery
* Interfaces for consent, auditability, data minimization, and policy enforcement
* Operator tooling to reduce misconfiguration; explainability of security outcomes
* Threat and privacy modeling applied to UX (STRIDE, LINDDUN)

### DePIN

* Operator dashboards for GPU, storage, bandwidth participation; resource scheduling
* Observability of decentralized systems: reliability, rewards, faults, latency
* Incentive design surfaced in UI; failure-mode communication and recovery paths

### Accessible AI

* AI-assisted accessibility audits and usability clustering for large datasets
* Privacy-preserving ML: federated learning, differential privacy, zkML
* Prototypes for rapid deployment with minimal adoption barriers
* Evaluation of user trust, explainability, and transparency in AI-driven systems

---

## Outputs

* **Studies**: protocols, instruments, sanitized or synthetic datasets, analysis notebooks
* **Prototypes**: minimal working systems that expose interaction patterns before scale
* **Tooling**: auditors, linters, collectors, visualization components, test harnesses
* **Curations**: “awesome” lists, standards mappings, reference implementations

---

## Methods and standards

* Empirical design: task analyses, cognitive walkthroughs, SUS, NASA-TLX, time-on-task, error rate; inter-rater agreement (Cohen’s kappa)
* Pre-registered protocols where relevant; A/B and counterfactual evaluation
* Reproducibility: deterministic seeds, pinned environments (`requirements.txt`, `package-lock.json`), container specs (Dockerfile), data schemas
* Security and privacy alignment: **NIST SP 800-63/53**, **HIPAA 45 CFR Part 164**, **GDPR Art. 5/25**, **ISO 9241-210**, **IEC 62366**, **WCAG 2.2**
* Adoption metric focus: install → first insight (TTFI) in minutes

---

## Repository topology (initial)

* `ux-methods` — study templates, consent language, instruments, analysis notebooks
* `ai-ux-auditor` — AI-assisted accessibility and usability audit CLI with report artifacts
* `healthcare-ux` — patient and clinician workflow prototypes with safety checks and logs
* `security-ux` — key, MFA, and consent flows; error-proofing, recovery, threat models
* `depin-ux` — operator dashboards, schedulers, reliability and reward visualizations
* `ai-research-demos` — federated learning, differential privacy, zkML examples with UX harnesses
* `awesome-accessible-ai` — curated research, standards, and tooling

---

## Reuse, licensing, citation

* **Code**: MIT by default. **Docs and data**: CC BY 4.0. **Models**: Apache-2.0 unless noted
* Each repo declares dataset license, schema, provenance, and limitations
* DOIs via Zenodo for citable releases; semantic versioning for artifacts

---

## Contribution principles

* Evidence over assertion; publish limitations and negative results
* No sensitive data; PHI and PII prohibited. Use de-identification or synthetic generation
* Issues and PRs reference tasks, metrics, and standards mappings
