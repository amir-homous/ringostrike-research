# User Study Addendum — Return Mode and Progress Without Check-in

Date: 2026-10-11
Extends: `research/user-study-plan.md`
Related source: `research/raw/founder-reflection-2026-10-11.md`

## Purpose

This addendum adds a re-entry scenario to the formative RingoStrike study plan. It is designed to test whether returning after absence feels clear, supportive, autonomy-respecting, and low pressure.

The goal is not to prove that RingoStrike improves retention or habit formation. The goal is to evaluate re-entry UX and the risks of misinterpreting inactivity.

## Research questions

RQ9 — Re-entry clarity:
Do users returning after a break understand what to do next?

RQ10 — Re-entry emotional safety:
Does the return experience feel welcoming, pressuring, guilt-inducing, or judgmental?

RQ11 — Preserved continuity:
Does showing durable prior progress or achievements help users feel continuity, or does it feel irrelevant, confusing, or manipulative?

RQ12 — Progress without check-in:
Can users distinguish app inactivity from real-world goal progress, and do they want a lightweight way to mention off-app progress?

RQ13 — Return choice burden:
Do choices such as Continue, Adjust, Start Small, and Rest help users, or do they add decision load?

## Version A usability-test addition

Add one scenario after the existing skip/reminder/reward tasks.

### Task 12 — Return after several weeks away

Prompt:

> Imagine you have not opened RingoStrike for several weeks. During that time, some parts of life changed. You may have made progress outside the app, or you may simply want to restart. Open the app and decide what to do next.

Observe:

- Does the participant know where to begin?
- Do they feel welcomed or judged?
- Do they notice preserved progress or prior achievements?
- Does any backlog, streak loss, or task list feel heavy?
- Do they prefer Continue, Adjust, Start Small, Rest, or another action?
- Do they want to explain what happened while away, or skip explanation?
- Does the app imply that inactivity equals failure?

Follow-up questions:

1. What did the app seem to assume about your absence?
2. Did the return screen feel supportive, neutral, or pressuring?
3. Would you want the app to ask whether you made progress outside the app?
4. Would you want to record off-app progress, ignore it, or just continue?
5. What should Ringo say when someone comes back after a long break?
6. What should Ringo never say in this situation?
7. Did the number of return options feel helpful or too much?

## Version B pilot addition

For a 7-14 day pilot, do not force participants to leave and return unless the study design explicitly includes a simulated break. Instead, use natural inactivity patterns when they occur.

Add logs:

- return_after_inactivity event;
- number of inactive days before return;
- return screen variant shown;
- return option selected: Continue, Adjust, Start Small, Rest, Skip explanation, Other;
- optional off-app progress response shown/not shown;
- optional off-app progress response submitted/skipped;
- first action after return;
- whether user completed any mission after return;
- whether user left immediately after return screen.

Add daily or exit questions only for participants who had inactivity or saw the re-entry scenario:

1. When you came back, did the app make it clear what to do next?
2. Did it feel like your earlier progress still counted?
3. Did anything about returning feel guilt-inducing or heavy?
4. Did the app ask too much about your absence?
5. Would you have preferred one recommended action or several choices?

## Variant comparison for early testing

Test two low-fidelity or prototype variants before building a complex feature.

### Variant A — Backlog/streak-oriented return

Shows missed days, incomplete missions, streak status, and pending tasks.

Hypothesis to test:

- May increase urgency or clarity for some users.
- May increase guilt, avoidance, or cognitive load for others.

### Variant B — Preserved-progress/one-next-action return

Shows a brief welcome back, preserved durable progress, and one recommended tiny or adjusted next action, with optional buttons for Continue, Adjust, Start Small, or Rest.

Hypothesis to test:

- May reduce pressure and improve perceived autonomy.
- May hide useful context for users who want a full backlog.

## Measures

Use 1-5 agreement ratings:

- The return screen made it clear what to do next.
- The return screen felt welcoming.
- The return screen made me feel guilty. Risk item.
- The return screen respected that life may have changed while I was away.
- Seeing previous progress made me feel able to continue.
- Seeing missed tasks or streak loss made me feel pressure. Risk item.
- I wanted one recommended next action.
- I wanted more control over how to restart.
- I would use an optional note for progress made outside the app.
- I would prefer to skip any explanation and just continue.

## Analysis plan

Analyze re-entry data descriptively. Report:

- task success for identifying a next action;
- qualitative reactions to Ringo's return tone;
- pressure/guilt ratings;
- preferred return option;
- whether participants wanted optional off-app progress reflection;
- differences between backlog/streak-oriented and preserved-progress variants.

Do not report:

- that Return Mode improves retention;
- that preserved progress improves motivation;
- that off-app progress is a validated construct;
- that returning users have maintained habits.

## Publication wording

Safe wording:

> A re-entry scenario was added to the formative study to examine how participants interpret app inactivity, preserved progress, and return options. The scenario evaluated perceived clarity, autonomy, guilt risk, and next-action identification.

Unsafe wording:

> Return Mode helps users recover their habits after disruption.

## Consent and privacy note

Off-app progress reflection can reveal sensitive life context. Keep it optional, skippable, and unnecessary for continuing the app.

Avoid asking for details about war, finances, mental health, medical issues, or personal crises. If participants voluntarily disclose sensitive context, treat it as confidential research data and do not publish identifiable details.
