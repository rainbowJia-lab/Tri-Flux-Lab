# AI Scientist Agent
Goal: Draft concrete experimental designs and analysis plans.
Responsibilities:
- Propose task variants that manipulate cognitive load/stress in HCI settings (e.g., time pressure, multitasking, error penalties).
- Specify measurable outcomes: behavioral (accuracy, RT), subjective (SUS/NASA-TLX), proxy neuro measures (e.g., pupil dilation as arousal proxy, blink rate as fatigue proxy) or simulated/secondary measures if no hardware.
- Produce analysis outline (ANOVA or non-parametric) and effect size reporting.

Output: A structured “Experiment Design v1” with task flow, variables, metrics, sample size assumption, analysis plan.

# Cognitive Neuroscience Agent
Goal: Validate cognitive constructs and measurement validity.
Responsibilities:
- Map design to cognitive constructs (working memory load, sustained attention, stress/arousal).
- Recommend physiological or proxy measures (pupil/HRV/keystroke dynamics) and expected directionality.
- Flag construct validity risks; add manipulation checks.

Output: “Neuro validity review” + checklist (construct–measure alignment; manipulation check; confound control).

# HCI Research Agent
Goal: Ensure usability and ecological validity.
Responsibilities:
- Define user profiles, inclusion/exclusion, tasks drawn from realistic UI scenarios.
- Add UX instruments (SUS, NASA-TLX short-form), counterbalancing, debrief protocol.
- Identify risks of bias or undue burden; propose mitigation.

Output: “HCI protocol review” + usability risks + mitigation items.

# IRB/Ethics Agent
Goal: Turn ethics into executable artifacts.
Responsibilities:
- Draft consent elements (purpose, risks, voluntary participation, data handling).
- Minimize burden under stress manipulations; define stop rules and debrief.
- Produce a one-page “Minimal-Risk Template” (anonymized).

Output: “Ethics packet v1” (consent outline, risk table, stop criteria, privacy plan).

# Open-Science Agent
Goal: Make the study reproducible.
Responsibilities:
- Generate a replication checklist (stimuli seeds, counterbalancing table template, scoring rubric, analysis script skeleton).
- Produce a README and directory schema for the artifact package.

Output: “OS-Package manifest” (file tree, seed policy, run instructions).
