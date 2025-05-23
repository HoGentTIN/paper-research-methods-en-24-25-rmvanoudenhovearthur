# Phase 5. Methodology

- **Working title research proposal:** Ensuring Transparency and Accountability in Autonomous AI Agents: Ethical Implications and Practical Frameworks for Decision-Making Roles
- **Name Student:** Van Oudenhove, Arthur
- **URL Github repo:** <https://github.com/HoGentTIN/paper-research-methods-en-24-25-rmvanoudenhovearthur.git>

## Action plan

This research will employ a mixed-methods approach, combining qualitative and conceptual analysis to address research questions. The core of the methodology will involve an in-depth literature review, comparative case study analysis (based on documented existing systems or detailed hypothetical scenarios if direct access is not feasible within the scope of a bachelor's thesis), and the development of a conceptual framework and practical guidelines. The research process is designed to be iterative, allowing for refinement as insights emerge.

---
**Phase 1: Literature Review & Grounding (approx. Wks 1-5 of thesis period)**
-   **Goal:** Establish a strong theoretical foundation by reviewing literature on AI ethics, XAI, accountability, AI governance, and relevant applications, including a survey of existing tools and best practices.
-   **Approach:** Systematically search academic databases and review policy, industry, and legal documents (e.g., EU AI Act). Synthesize findings to identify key concepts, theories, solutions, and research gaps, addressing subquestions on risks, frameworks, barriers, XAI, and governance models.
-   **Result, deliverable(s):** Structured literature review chapter, refined sub-questions, preliminary conceptual model.
-   **Timing/Deadline:** End of Week 5 (of thesis period) for initial comprehensive draft.

---
**Phase 2: Case Study Design & Selection (approx. Wks 4-7 of thesis period, overlaps P1)**
-   **Goal:** Select and define parameters for three illustrative case studies of autonomous AI agents in healthcare, finance, and criminal justice.
-   **Approach:** Identify documented AI systems or construct realistic hypothetical scenarios based on literature. Selection criteria include impact, information availability, and relevance. Develop an analysis protocol defining "AS IS" and desired "TO BE" states for transparency/accountability.
-   **Result, deliverable(s):** Detailed case study descriptions/scenarios, case study analysis protocol.
-   **Timing/Deadline:** End of Week 7 (of thesis period).

---
**Phase 3: Data Collection & Analysis (approx. Wks 6-12 of thesis period, overlaps P2)**
This phase has two streams:
* **Stream 3a: Case Study Analysis (Technical/Ethical Audit Simulation)**
    -   **Goal:** Analyze cases for ethical risks, transparency challenges, and accountability gaps. Conceptually explore or simulate XAI technique effectiveness on illustrative models using public/synthetic data.
    -   **Approach:** Apply the analysis protocol. For technical aspects, simulate decision processes with simplified models (Python, scikit-learn, TensorFlow/PyTorch, SHAP) to demonstrate XAI application, evaluating outputs for clarity/fidelity. Analyze ethical implications using established frameworks and perform comparative synthesis across cases.
    -   **Result, deliverable(s):** In-depth case analysis reports, preliminary XAI applicability findings.
* **Stream 3b: Stakeholder Perspectives (via Expert Literature)**
    -   **Goal:** Gather insights on practical challenges and requirements for AI transparency/accountability from diverse stakeholder viewpoints, primarily via existing literature due to thesis scope.
    -   **Approach:** Conduct thematic analysis of published expert opinions, interviews, and surveys. If feasible, supplement with a few (3-5) informational interviews with local experts focusing on risks, explainability needs, and accountability features.
    -   **Result, deliverable(s):** Synthesis of stakeholder perspectives and requirements.
-   **Timing/Deadline:** End of Week 12 (of thesis period) for completion of analysis and synthesis.

---
**Phase 4: Framework & Guideline Development (approx. Wks 10-15 of thesis period, overlaps P3)**
-   **Goal:** Develop a novel conceptual framework and practical guidelines for transparent and accountable AI.
-   **Approach:** Synthesize findings from literature, case studies, and stakeholder perspectives. The framework will integrate technical (XAI, data governance, debiasing) and governance/operational (roles, audits, oversight, redress) components. Derive practical guidelines from this framework.
-   **Result, deliverable(s):** Detailed framework description, actionable guidelines for ethical AI deployment.
-   **Timing/Deadline:** End of Week 15 (of thesis period) for draft framework and guidelines.

---
**Phase 5: Validation & Refinement (approx. Wks 14-17 of thesis period, overlaps P4)**
-   **Goal:** Validate the proposed framework and guidelines.
-   **Approach:** Evaluate the framework/guidelines against research questions/objectives. Seek feedback from supervisors and potentially external experts/peers for refinement.
-   **Result, deliverable(s):** Refined framework and guidelines, validation process report.
-   **Timing/Deadline:** End of Week 17 (of thesis period).

---
**Phase 6: Thesis Writing & Finalization (Iterative, Wks 1-18; final push Wks 16-18 of thesis period)**
-   **Goal:** Produce a comprehensive, well-structured, and clearly written bachelor thesis.
-   **Approach:** Write iteratively throughout all phases. Consolidate sections, ensure coherence, address feedback, and finalize according to academic standards.
-   **Result, deliverable(s):** Completed RM course proposal (May 2025), final bachelor thesis document.
-   **Timing/Deadline:** Final thesis submission by end of Week 18 (of thesis period - adjust to specific date).

---
## Visualisation

(Gantt Chart - Mermaid Code)
```mermaid
%%{init: { "theme": "neutral" } }%%
gantt
    dateFormat  YYYY-MM-DD
    title Research Thesis Timeline (Example ~18 Weeks for 2026 - Durations in Days)
    excludes    weekends
    %% Example Start Date: Monday, Feb 09, 2026 (adjust as needed)
    %% Example End Date (Submission): Friday, June 19, 2026 (adjust as needed)

    section P1: Lit. & Theory (25d)
    Literature Review        :crit, p1_lit, 2026-02-09, 25d

    section P2: Case Study Design (10d + 10d)
    %% Case Study Sel. starts approx. week 4
    Case Study Sel.     :p2_sel, 2026-03-02, 10d
    %% Protocol Dev. ends approx. end of week 7
    Protocol Dev.       :p2_prot, after p2_sel, 10d 

    section P3: Data Collection & Analysis (35d)
    %% Case Study Analysis starts approx. week 6
    Case Study Analysis :crit, p3_csa, 2026-03-16, 35d
    %% Stakeholder Elic. is parallel with Case Study Analysis
    Stakeholder Elic.   :p3_stake, 2026-03-16, 35d 

    section P4: Framework & Guidelines (30d)
    %% Framework Dev. starts approx. week 11
    Framework Dev.      :crit, p4_frame, 2026-04-20, 30d 

    section P5: Validation (10d + 10d)
    %% Expert Feedback starts approx. week 16
    Expert Feedback     :p5_val, 2026-05-25, 10d 
    Refinement          :p5_ref, after p5_val, 10d 

    section P6: Thesis Writing & Submission
    %% Drafting is 18 work weeks
    Drafting (Ongoing)  :p6_draft, 2026-02-09, 90d  
    %% Final Revisions are the last 2 work weeks, overlapping end of drafting
    Final Revisions     :crit, p6_final, 2026-06-08, 10d 
    Submission          :milestone, 2026-06-19, 0d

