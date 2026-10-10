# Prioritized Scientific Roadmap

Date: 2026-10-11
Scope: RingoStrike research paper, prototype evidence, and next user-study steps.

## Current scientific position

RingoStrike is currently strongest as an evidence-informed design framework and early product case study. It is not yet strong as an effectiveness paper.

The credible contribution today is:

> a behavior-aware micro-mission design framework, mapped to habit formation, adaptive intervention, motivation, gamification, reminder, companion-agent, and ethical persuasive-design literature, with a transparent plan for formative evaluation.

The paper should not claim:

- proven habit formation;
- improved wellbeing;
- improved productivity;
- improved mental health;
- improved retention;
- causal impact of Ringo;
- causal impact of tiny missions;
- superiority over other habit apps.

## Roadmap overview

Priority order:

1. Evidence hygiene and claim control.
2. Current product audit.
3. Re-entry and inactivity research integration.
4. Formative usability study.
5. Product revision based on findings.
6. Short pilot with logs and interviews.
7. Paper revision and preprint preparation.
8. Longer-term comparative study only after the prototype is stable.

---

# Phase 1 — Evidence hygiene and claim control

Priority: Critical
Timing: Now

## Tasks

- Keep `claims-to-support.md` as the source of truth for claim boundaries.
- Add the Oct 11 founder reflection only as retrospective qualitative case material.
- Ensure every paper section distinguishes literature-backed design rationale from RingoStrike-specific evidence.
- Add a founder reflexivity statement if the paper uses founder experience.
- Keep sensitive personal and wartime details out of public drafts unless approved and anonymized.

## Acceptance criteria

- No draft states or implies that RingoStrike has proven effectiveness.
- Founder reflection is labeled as hypothesis generation.
- Claims about Return Mode and progress without check-in are framed as research questions.

---

# Phase 2 — Current product audit

Priority: Critical
Timing: Before any user study

## Tasks

- Audit the current RingoStrike app against research claims.
- Document which features actually exist, which are prototypes, and which are future design concepts.
- Capture dated screenshots of onboarding, mission center, tiny mission flow, reminder settings, rewards, streaks, Ringo messages, and any re-entry-related screens.
- Verify whether current implementation supports logs needed for the study.

## Acceptance criteria

- A dated prototype evidence file says what exists and what does not.
- The study plan does not ask participants to test nonexistent features.
- The paper does not describe planned features as implemented features.

---

# Phase 3 — Re-entry and inactivity research integration

Priority: High
Timing: After Phase 1, before user testing

## Tasks

- Treat inactivity as an ambiguous signal in the framework.
- Add a Return Mode prototype or low-fidelity mockup.
- Test backlog/streak-oriented vs preserved-progress/one-next-action return screens.
- Add optional, skippable off-app progress reflection.
- Create a data dictionary for return_after_inactivity events.

## Acceptance criteria

- Return Mode is documented as a hypothesis, not a product claim.
- The user-study script includes a re-entry scenario.
- Measures include clarity, autonomy, pressure/guilt, and next-action identification.

---

# Phase 4 — Formative usability study

Priority: High
Timing: First actual participant study

## Recommended design

- 5-8 adult participants.
- Moderated sessions, 45-60 minutes.
- Think-aloud protocol.
- Task observation, short survey, short interview.
- Convenience sample allowed only if reported honestly.

## Must-test areas

- First impression.
- Path/challenge/mission clarity.
- Today mission identification.
- Tiny mission and Make it smaller flow.
- I am too tired flow.
- Skip and Remind Later flow.
- Rewards and streak interpretation.
- Ringo tone.
- Re-entry scenario.
- Pressure and guilt risks.

## Acceptance criteria

- At least 5 completed sessions.
- Clear table of findings with severity and design implication.
- At least 5 direct participant quotes, anonymized.
- List of product changes before a longer pilot.

---

# Phase 5 — Product revision

Priority: High
Timing: Immediately after Phase 4

## Tasks

- Fix blocking usability issues.
- Simplify any confusing mission hierarchy or navigation.
- Revise Ringo messages that feel guilt-inducing, childish, manipulative, or unclear.
- Reduce backlog pressure in return flow if participants react negatively.
- Remove or defer features that cannot be explained clearly.

## Acceptance criteria

- Each major study finding maps to an action: fixed, deferred, rejected with reason, or needs more evidence.
- The next pilot version has stable core flows.

---

# Phase 6 — 7-14 day formative pilot

Priority: Medium-high
Timing: After the prototype is stable enough for daily use

## Recommended design

- 10-20 adult participants.
- 7 days minimum, 14 days preferred.
- Real-world use.
- Behavior logs plus daily micro-feedback.
- Exit survey and follow-up interviews.

## Core logs

- onboarding completed;
- mission shown/completed/skipped;
- tiny mission shown/selected/completed;
- Make it smaller clicked;
- I am too tired clicked;
- Remind Later clicked;
- reminder sent/opened/clicked;
- reward sequence started/completed/exited;
- inactive days;
- return_after_inactivity;
- return option selected;
- first action after return.

## Acceptance criteria

- Basic engagement patterns can be described without causal claims.
- Interviews explain some reasons behind logs.
- Drop-off points and return points are identified.
- Pressure/guilt risks are reported honestly.

---

# Phase 7 — Paper revision and preprint preparation

Priority: Medium
Timing: After Phase 4, stronger after Phase 6

## Best paper framing after Phase 4 only

> Evidence-informed design framework plus formative usability evaluation.

## Best paper framing after Phase 6

> Evidence-informed design framework plus formative usability evaluation and short real-world pilot.

## Required sections

- Introduction and problem framing.
- Literature review.
- Behavior-Aware Micro-Mission Framework.
- RingoStrike case/prototype description.
- Methods: formative UX study and/or pilot.
- Findings: only if study is actually completed.
- Discussion: design implications and limitations.
- Ethics and AI usage.
- Future work.

## Venue direction

Most realistic first outputs:

- portfolio case-study paper;
- arXiv-style preprint after cleanup;
- HCI/UX workshop submission;
- student or early-stage design research venue;
- CHI-style late-breaking work only if the study is completed and written rigorously.

A full top-tier HCI paper is unlikely without stronger user data, clearer novelty, and a robust study.

---

# Phase 8 — Longer-term comparative study

Priority: Later
Timing: Only after product and measures are stable

## Possible design

- Compare adaptive micro-missions vs static missions.
- Compare supportive re-entry vs backlog/streak-oriented re-entry.
- Use validated habit-strength or automaticity measures if making habit claims.
- Include follow-up beyond the novelty period.

## Acceptance criteria for stronger claims

To make stronger claims, the project needs:

- predefined hypotheses;
- sufficient sample size;
- comparison condition;
- reliable logging;
- validated measures where relevant;
- follow-up beyond 14 days;
- transparent reporting of null or negative results.

## Current no-go claims

Do not claim these until evidence exists:

- RingoStrike builds habits.
- Ringo improves motivation.
- Tiny missions increase retention.
- Return Mode helps users resume habits.
- Companion messages reduce guilt.
- Rewards improve behavior change.
- AI personalization improves outcomes.

## Immediate next actions

1. Review and merge the Oct 11 research addenda if accurate.
2. Audit the current product implementation and screenshot evidence.
3. Build or mock the re-entry screen variants.
4. Prepare a 5-8 participant usability script using `user-study-plan.md` plus `user-study-re-entry-addendum.md`.
5. Run one pilot usability session as a rehearsal before recruiting the full small sample.
6. Revise the paper only after study findings exist, or clearly mark all results sections as planned/future work.
