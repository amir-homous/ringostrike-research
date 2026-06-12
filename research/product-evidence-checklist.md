# Product Evidence Checklist — RingoStrike

## 1. Purpose of this file

This file defines the product evidence needed before RingoStrike can be described more confidently in the paper, portfolio, preprint, or academic submission.

The purpose is to answer:

> What screenshots, code references, user-flow evidence, data-model evidence, screen recordings, logs, and artifacts are needed to prove the current implementation status of RingoStrike features?

This checklist exists to prevent the paper from describing design concepts, planned features, prototype ideas, or framework logic as if they are already implemented, tested, or effective.

The file should be used when preparing:

* portfolio case studies
* product documentation
* paper revisions
* preprint material
* academic submission material
* user-study preparation
* implementation-status reviews

The core rule is:

> A feature should not be described as implemented unless direct product evidence exists.

---

## 2. Evidence boundary

This file uses only the current uploaded repository materials:

* `paper-implementation-alignment-review.md`
* `paper-implementation-aligned-draft.md`
* `prototype-implementation-status.md`
* `paper-claim-audit.md`
* `references-draft.md`
* `claims-to-support.md`
* `article-master-brief.md`
* `ai-usage-log.md`
* `feature-theory-map.md`
* `micro-mission-framework.md`
* `user-study-plan.md`

No new research was added.

No external browsing was performed.

No implementation details were invented.

No screenshots were invented.

No code references were invented.

No user-flow evidence was invented.

No data-model evidence was invented.

No behavior logs were invented.

No user study results were invented.

The current repository materials are strong as research, framework, writing, and claim-safety documents. They are weak as direct implementation evidence. Most RingoStrike features are currently best treated as proposed features, design concepts, planned features, prototype-stage ideas, or features requiring clarification unless direct product artifacts are added.

---

## 3. Why product evidence is needed now

Product evidence is needed because the paper now includes a strong implementation-status boundary, but the repository still lacks the artifacts needed to prove the current state of the product.

The current draft can safely present RingoStrike as:

> An evidence-informed design framework and early product case study.

It cannot yet safely present RingoStrike as:

> A fully implemented habit-building system.

or:

> A validated adaptive habit companion.

The next evidence gap is not mainly literature evidence. The next gap is product evidence.

The paper and portfolio need proof of:

* what screens exist
* what flows are working
* what features are only conceptual
* what features are prototype-stage
* what data is captured
* what logs are available
* what messages Ringo actually shows
* what reminders actually do
* how rewards and streaks are calculated
* whether adaptation is implemented as rules, static examples, manual logic, or not implemented yet
* whether user-study tasks can be performed in the actual product or only in a prototype

Without this evidence, the safest wording remains:

> RingoStrike is designed around these features, but implementation status requires clarification.

---

## 4. Evidence types and definitions

| Evidence type | Definition | Why it matters |
| --- | --- | --- |
| Screenshot | A still image of an actual product screen. | Proves that a UI state or feature surface exists visually. |
| Screen recording | A video showing a user or tester moving through the product flow. | Proves interaction continuity, not just isolated screens. |
| Code reference | A specific source file, function, component, route, or logic block. | Proves that a feature is represented in implementation. |
| Component or file path | The exact path to a relevant frontend or backend file. | Helps reviewers verify product implementation without guessing. |
| Data model or schema | Database, API, Notion, backend, or frontend state structure. | Proves whether the product can store and retrieve required feature data. |
| User-flow diagram | A diagram showing the user path through screens, actions, and states. | Clarifies whether a feature exists as a complete flow. |
| Real mission example | A real mission currently available in the product or prototype. | Proves that mission content exists beyond abstract theory. |
| Ringo message example | Exact copy shown by Ringo in a real product state. | Proves companion tone, message logic, and ethical wording. |
| State-transition example | Before-and-after evidence showing how one user action changes system state. | Proves adaptation, completion, skipping, or reward behavior. |
| Behavior event log | A record showing an interaction event such as completion, skip, or remind later. | Proves that behavior signals are captured. |
| Anonymized sample log | A privacy-safe example of logged user behavior. | Supports evaluation readiness without exposing personal data. |
| Reminder scheduling proof | Evidence that a reminder is actually scheduled, sent, received, opened, or clicked. | Distinguishes real reminders from design intent. |
| Reward/streak calculation rule | A documented rule explaining how XP, rewards, or streaks are calculated. | Prevents vague or unsupported claims about progress feedback. |
| User-study protocol | The documented study procedure. | Shows that formative evaluation is planned responsibly. |
| Consent text | Participant-facing consent wording. | Needed before collecting user behavior, recordings, or feedback. |
| Survey/interview instrument | Actual survey questions, interview questions, and rating scales. | Proves that the user study can collect relevant evidence. |

---

## 5. Feature evidence checklist table

| Feature | Current evidence status | Evidence needed | Priority | Safe paper wording until evidence exists |
| ------- | ----------------------- | --------------- | -------- | ---------------------------------------- |
| Paths | Requires clarification | Screenshot of path selection; real path examples; data model or schema; user-flow diagram; code/component reference. | High | “Paths are part of the proposed product hierarchy.” |
| Challenges | Requires clarification | Screenshot of challenge list/detail; real challenge examples; challenge data model; enrollment/progress flow; code/component reference. | High | “Challenges are described as structured programs within paths.” |
| Daily missions | Requires clarification | Screenshot of today’s mission; real mission examples; completion flow recording; mission assignment logic; data model; code reference. | Critical | “Daily missions are a core product concept intended to translate goals into concrete daily actions.” |
| Tiny missions | Design concept | Tiny mission screenshot; normal-to-tiny transition; real tiny mission examples; selection/completion logs; Ringo response example. | Critical | “Tiny missions are designed as lower-effort alternatives.” |
| Bonus missions | Design concept | Bonus mission screenshot; optional framing proof; real bonus mission examples; completion and reward logs. | Medium | “Bonus missions are designed as optional higher-intensity actions.” |
| Mission intensity | Design concept | Mission intensity labels; rule table; before/after adaptation example; code reference; state-transition evidence. | Critical | “Mission intensity is a proposed behavior-aware design mechanism.” |
| Make it smaller | Design concept | Button screenshot; screen recording of interaction; original mission and smaller mission example; log event; code reference. | Critical | “‘Make it smaller’ is designed as an adaptation pattern.” |
| I’m too tired | Design concept | Button screenshot; Ringo response copy; tiny/recovery mission transition; log event; safety wording. | Critical | “‘I’m too tired’ is designed as a user-reported low-energy signal.” |
| Remind later | Requires clarification | Button screenshot; scheduling confirmation; reminder timing rule; notification proof; log event; code reference. | Critical | “‘Remind later’ is intended as a timing-adjustment option.” |
| Skip | Requires clarification | Button screenshot; post-skip state; Ringo response copy; log event; effect on streak/reward rules. | High | “Skip is intended as a non-shaming option for declining a mission.” |
| Streaks | Requires clarification | Streak UI screenshot; calculation rule; reset/preserve logic; edge cases; sample data. | High | “Streaks are intended as continuity feedback, not evidence of habit formation.” |
| XP and rewards | Requires clarification | Reward screen screenshots; XP rules; reward values; completion flow recording; code reference. | High | “XP and rewards are designed as feedback mechanisms.” |
| Step-by-step reward moment | Design concept | Screen recording of complete reward sequence; screenshots of each step; next-action state; exit behavior. | High | “The step-by-step reward moment is a proposed UX pattern.” |
| Ringo companion | Design concept | Screenshots showing Ringo in product; message examples; interaction points; visual asset references. | Critical | “Ringo is designed as the companion interface.” |
| Ringo moods | Design concept | Mood asset list; screenshots of each mood; trigger map; state-transition examples. | Medium | “Ringo moods are part of the proposed companion design.” |
| Adaptive messages | Design concept | Message library; decision rules; before/after examples; code or content source; state-trigger evidence. | Critical | “Adaptive messages are proposed as behavior-aware responses.” |
| Reminders and notifications | Planned | Notification channel proof; scheduling logic; reminder screenshots; opt-out controls; reminder logs. | Critical | “Reminders are planned or intended as supportive re-engagement cues.” |
| Mission logs | Requires clarification | Event list; database schema; anonymized sample logs; export method; privacy notes. | Critical | “Mission logs are needed to support evaluation and future adaptation.” |
| Onboarding and guided flow | Requires clarification | Onboarding screenshots; first-use flow recording; user-flow diagram; code/component references. | High | “Guided flow is intended to reduce decision burden and should be tested.” |
| User behavior signals | Design concept | Event tracking list; log examples for completion, skip, remind later, tiredness, inactivity, tiny mission selection, bonus mission selection. | Critical | “Behavior signals are proposed as possible inputs for adaptation.” |
| Rule-based adaptation | Design concept | Rule table; code reference; state-transition examples; mission replacement evidence; explanation copy. | Critical | “RingoStrike frames adaptation as rule-based or behavior-aware design logic.” |
| AI-assisted personalization | Planned | Technical plan; AI disclosure text; data-use boundary; safety rules; evaluation plan; implementation proof if built. | Later | “AI-assisted personalization is a possible future extension, not a validated current feature.” |
| User study / formative evaluation | Planned | Study protocol; consent text; survey/interview instruments; recruitment criteria; task script; data collection plan. | Critical | “A formative UX study is proposed to evaluate clarity, perceived support, friction, reminders, rewards, and pressure risks.” |

---

## 6. Screenshot checklist

Screenshots should be taken from the actual product or a clearly labeled clickable prototype. Each screenshot should include the date, product version or commit reference if available, and a short caption explaining what the screenshot proves.

### Required screenshots

- [ ] Landing or first screen showing what RingoStrike is.
- [ ] Onboarding start screen.
- [ ] Path selection screen, if paths are implemented.
- [ ] Challenge selection or challenge detail screen, if challenges are implemented.
- [ ] Mission Center or main daily mission screen.
- [ ] Daily mission card.
- [ ] Tiny mission card.
- [ ] Bonus mission card.
- [ ] “Make it smaller” button or interaction state.
- [ ] “I’m too tired” button or interaction state.
- [ ] “Remind later” button or interaction state.
- [ ] Skip button or skip state.
- [ ] Post-completion confirmation.
- [ ] XP or reward feedback.
- [ ] Streak display.
- [ ] Step-by-step reward sequence screens, if implemented.
- [ ] Ringo companion visible in the UI.
- [ ] Ringo mood examples, if implemented.
- [ ] Ringo message examples for completion, tiredness, skip, and return.
- [ ] Reminder notification screenshot, if implemented.
- [ ] Reminder settings or opt-out screen, if implemented.
- [ ] Mission log or history screen, if implemented.
- [ ] User profile or progress screen, if implemented.
- [ ] Empty state or inactive/returning user state, if implemented.

### Screenshot quality requirements

- [ ] Use real UI, not imagined mockups.
- [ ] Label prototype screenshots as prototype screenshots.
- [ ] Do not crop out important navigation or state indicators.
- [ ] Avoid showing private user data.
- [ ] Use anonymized test accounts.
- [ ] Capture both English and Persian screens if both languages are part of the product claim.
- [ ] Do not use screenshots to imply a feature is working if the screen is static or manually mocked.

---

## 7. Code reference checklist

Code references should be exact enough that another person can verify the implementation. Do not invent file paths. Add file paths only after inspecting the repository.

### Required code evidence

- [ ] Frontend component or route for Mission Center.
- [ ] Frontend component or route for paths, if implemented.
- [ ] Frontend component or route for challenges, if implemented.
- [ ] Frontend component or route for daily missions.
- [ ] UI logic for tiny missions.
- [ ] UI logic for bonus missions.
- [ ] UI logic for “Make it smaller.”
- [ ] UI logic for “I’m too tired.”
- [ ] UI logic for “Remind later.”
- [ ] UI logic for Skip.
- [ ] Completion action handler.
- [ ] Reward or XP display logic.
- [ ] Streak display logic.
- [ ] Ringo companion component or visual asset reference.
- [ ] Ringo mood state logic, if implemented.
- [ ] Ringo message source or message library.
- [ ] Backend endpoint for mission retrieval, if implemented.
- [ ] Backend endpoint for mission completion, if implemented.
- [ ] Backend endpoint or handler for skip, if implemented.
- [ ] Backend endpoint or handler for remind later, if implemented.
- [ ] Backend endpoint or handler for tiredness signal, if implemented.
- [ ] Data persistence logic for mission logs.
- [ ] Reminder scheduling logic, if implemented.
- [ ] Notification sending logic, if implemented.
- [ ] Rule-based adaptation logic, if implemented.
- [ ] AI-assisted personalization logic, only if actually implemented.

### Code reference format

Use this format when evidence is added:

```text id="uw6f99"
Feature:
Evidence type:
File path:
Relevant component/function:
What this proves:
What this does not prove:
```

Example structure only:

```text id="j4psn2"
Feature: Tiny missions
Evidence type: Code reference
File path: [add exact path after repository inspection]
Relevant component/function: [add exact function/component after inspection]
What this proves: The UI includes a tiny mission state.
What this does not prove: Users find tiny missions useful or supportive.
```

---

## 8. User-flow evidence checklist

User-flow evidence should show complete sequences, not isolated screens.

### Required flows

- [ ] First-time user opens RingoStrike.
- [ ] User understands what Ringo does.
- [ ] User selects a path, if implemented.
- [ ] User selects or enters a challenge, if implemented.
- [ ] User reaches today’s mission.
- [ ] User completes a normal mission.
- [ ] User sees completion feedback.
- [ ] User sees XP or reward feedback.
- [ ] User sees streak or continuity feedback.
- [ ] User chooses “Make it smaller.”
- [ ] User receives a smaller mission.
- [ ] User taps “I’m too tired.”
- [ ] User receives a tiny, recovery, reminder, or supportive response.
- [ ] User taps “Remind later.”
- [ ] User receives scheduling confirmation.
- [ ] User later receives the reminder, if implemented.
- [ ] User skips a mission.
- [ ] User receives non-shaming skip feedback.
- [ ] User returns after inactivity.
- [ ] User receives soft re-entry guidance.
- [ ] User completes a tiny mission.
- [ ] User completes a bonus mission, if implemented.
- [ ] User exits after completing the daily flow.
- [ ] User understands what to do next.

### Flow documentation requirements

Each flow should include:

- [ ] Starting state.
- [ ] User action.
- [ ] System response.
- [ ] Ringo response, if any.
- [ ] Data recorded, if any.
- [ ] Final state.
- [ ] Evidence type used.
- [ ] Known limitations.

---

## 9. Data-model evidence checklist

Data-model evidence is needed before claiming that features are supported by actual product structure.

### Required data-model evidence

- [ ] User model or user record structure.
- [ ] Path model or schema, if implemented.
- [ ] Challenge model or schema, if implemented.
- [ ] Mission model or schema.
- [ ] Mission type field, if tiny/normal/bonus/recovery missions are implemented.
- [ ] Mission intensity field or equivalent logic, if implemented.
- [ ] Mission completion record.
- [ ] Skip record.
- [ ] Remind-later record.
- [ ] Tiredness signal record.
- [ ] Make-it-smaller event record.
- [ ] Tiny mission selected record.
- [ ] Bonus mission selected record.
- [ ] Reminder scheduled record, if implemented.
- [ ] Reminder sent/opened/clicked record, if implemented.
- [ ] XP or reward record.
- [ ] Streak record.
- [ ] Ringo message state or message ID, if implemented.
- [ ] Ringo mood state or mood ID, if implemented.
- [ ] User consent or study participation status, if user study data is collected.
- [ ] Data deletion or privacy handling notes.

### Data-model caution

A data field alone does not prove that the feature works. It only proves that the system has a place to store the data. Working product evidence still requires UI, interaction, and state-transition proof.

---

## 10. Behavior-log evidence checklist

Behavior logs are required before claiming that RingoStrike captures behavior signals or can support adaptive evaluation.

### Required event logs

- [ ] User account created or user session started.
- [ ] Onboarding started.
- [ ] Onboarding completed.
- [ ] Path selected.
- [ ] Challenge selected.
- [ ] Daily mission shown.
- [ ] Normal mission completed.
- [ ] Tiny mission shown.
- [ ] Tiny mission selected.
- [ ] Tiny mission completed.
- [ ] Bonus mission shown.
- [ ] Bonus mission selected.
- [ ] Bonus mission completed.
- [ ] “Make it smaller” clicked.
- [ ] “I’m too tired” clicked.
- [ ] “Remind later” clicked.
- [ ] Reminder scheduled.
- [ ] Reminder sent.
- [ ] Reminder opened or clicked.
- [ ] Skip clicked.
- [ ] Reward sequence started.
- [ ] Reward sequence completed.
- [ ] Reward sequence exited early.
- [ ] XP awarded.
- [ ] Streak continued.
- [ ] Streak lost or reset.
- [ ] User returned next day.
- [ ] Inactivity period detected.
- [ ] Soft re-entry message shown.

### Anonymized sample log requirements

Each anonymized sample log should include:

- [ ] Event name.
- [ ] Timestamp.
- [ ] Anonymous user ID.
- [ ] Mission ID or mission type.
- [ ] Relevant state before event.
- [ ] Relevant state after event.
- [ ] No personal or sensitive data.
- [ ] Explanation of what the log proves.
- [ ] Explanation of what the log does not prove.

### Behavior-log interpretation warning

Behavior logs do not prove motivation, emotional state, habit formation, wellbeing, productivity, discipline, or mental health outcomes.

A skipped mission may mean:

* low energy
* confusion
* lack of time
* poor mission fit
* technical difficulty
* dislike of the app
* simple lack of interest
* no clear cause

Logs must be combined with user interviews and survey data before interpreting user experience.

---

## 11. Copy and companion-message evidence checklist

Ringo’s messages are central to the product identity, but they require direct evidence before being described as implemented.

### Required copy evidence

- [ ] Ringo welcome message.
- [ ] Ringo onboarding guidance.
- [ ] Ringo daily mission prompt.
- [ ] Ringo completion message.
- [ ] Ringo tiny mission message.
- [ ] Ringo “Make it smaller” response.
- [ ] Ringo “I’m too tired” response.
- [ ] Ringo “Remind later” response.
- [ ] Ringo skip response.
- [ ] Ringo inactivity or return message.
- [ ] Ringo streak continuation message.
- [ ] Ringo streak-risk message, if implemented.
- [ ] Ringo reward message.
- [ ] Ringo bonus mission message.
- [ ] Ringo error or empty-state message.
- [ ] Persian copy examples, if Persian is part of the product.
- [ ] English copy examples, if English is part of the product.

### Message evidence requirements

For each message, document:

```text id="2odty1"
Message ID or label:
Trigger:
Exact message text:
Language:
Ringo mood, if any:
Screen or component where it appears:
What this message is intended to do:
Pressure/guilt risk:
Evidence source:
```

### Companion safety checks

- [ ] Does the message avoid shame?
- [ ] Does the message avoid guilt?
- [ ] Does the message avoid clinical or therapeutic claims?
- [ ] Does the message avoid saying Ringo knows the user’s emotional state?
- [ ] Does the message preserve user choice?
- [ ] Does the message avoid making the user responsible for Ringo’s feelings?
- [ ] Does the message avoid overstating progress?
- [ ] Does the message avoid claiming habit formation?

---

## 12. Reminder and notification evidence checklist

Reminders and notifications should not be described as implemented unless scheduling and delivery evidence exists.

### Required reminder evidence

- [ ] Reminder UI or user control screen.
- [ ] “Remind later” confirmation state.
- [ ] Reminder time selection or default timing rule.
- [ ] Reminder scheduling logic.
- [ ] Notification channel evidence.
- [ ] Example notification screenshot.
- [ ] Reminder sent log.
- [ ] Reminder opened or clicked log, if tracked.
- [ ] Reminder cancellation or opt-out control.
- [ ] Reminder frequency rule.
- [ ] Streak-risk reminder rule, if implemented.
- [ ] Missed mission reminder rule, if implemented.
- [ ] Inactivity reminder rule, if implemented.
- [ ] Ringo reminder copy examples.
- [ ] Privacy and consent note for reminders.

### Safe reminder wording

Use:

> Reminders are planned as supportive, autonomy-respecting re-engagement cues.

or, if implementation proof exists:

> The prototype includes reminder controls for [specific documented reminder type].

Avoid:

> RingoStrike reminds users at the right time.

Avoid:

> Ringo reminders feel caring.

Avoid:

> Ringo reminders improve return rate.

Those claims require user evidence and reminder-response data.

---

## 13. Reward and streak evidence checklist

Rewards and streaks need calculation evidence before they can be described as implemented mechanisms.

### Required reward evidence

- [ ] Completion confirmation screen.
- [ ] XP award screen.
- [ ] XP value rule.
- [ ] Reward type list.
- [ ] Reward trigger rule.
- [ ] Tiny mission reward rule.
- [ ] Bonus mission reward rule.
- [ ] Reward sequence screenshots or recording.
- [ ] Reward sequence exit behavior.
- [ ] Reward sequence completion log.
- [ ] Ringo reward message.
- [ ] Code reference for XP or reward logic.

### Required streak evidence

- [ ] Streak display screenshot.
- [ ] Streak calculation rule.
- [ ] Streak start rule.
- [ ] Streak continuation rule.
- [ ] Streak reset rule.
- [ ] Streak preservation rule for tiny missions, if implemented.
- [ ] Streak effect of skip.
- [ ] Streak effect of remind later.
- [ ] Streak effect of inactivity.
- [ ] Time zone handling rule.
- [ ] Edge case examples.
- [ ] Code reference for streak logic.
- [ ] Sample anonymized streak data.

### Reward and streak wording boundary

Safe:

> XP, rewards, and streaks are designed as feedback mechanisms.

Safe:

> Streaks are continuity markers.

Unsafe without evidence:

> Rewards motivate users.

Unsafe without evidence:

> Streaks help users build habits.

Unsafe without evidence:

> XP improves engagement.

Unsafe without evidence:

> Tiny missions preserve habit progress.

---

## 14. User-study readiness evidence checklist

Before running or describing a formative evaluation, the repository should contain study materials.

### Required study materials

- [ ] Study purpose.
- [ ] Study type.
- [ ] Participant criteria.
- [ ] Recruitment text.
- [ ] Consent text.
- [ ] Data collection statement.
- [ ] Privacy statement.
- [ ] Screen recording permission text.
- [ ] Behavior logging permission text.
- [ ] Moderator script.
- [ ] Task list.
- [ ] Survey instrument.
- [ ] Interview questions.
- [ ] Pressure/guilt risk questions.
- [ ] Reminder reaction questions.
- [ ] Ringo companion perception questions.
- [ ] Tiny mission usefulness questions.
- [ ] Reward/streak perception questions.
- [ ] Data analysis plan.
- [ ] Criteria for excluding incomplete sessions.
- [ ] Statement that the study does not test clinical outcomes.
- [ ] Statement that the study does not prove long-term habit formation.

### Required product readiness before usability test

- [ ] Participant can open the product or prototype.
- [ ] Participant can understand the first screen.
- [ ] Participant can find today’s mission.
- [ ] Participant can complete a mission.
- [ ] Participant can trigger or view tiny mission flow, if tested.
- [ ] Participant can use or view “Make it smaller,” if tested.
- [ ] Participant can use or view “I’m too tired,” if tested.
- [ ] Participant can use or view “Remind later,” if tested.
- [ ] Participant can skip a mission, if tested.
- [ ] Participant can see reward/streak feedback, if tested.
- [ ] Participant can react to Ringo messages.
- [ ] Researcher can collect notes safely.
- [ ] Researcher can collect recordings only with consent.
- [ ] Researcher can collect logs only with consent.

### User-study wording boundary

Safe:

> A formative UX study is planned to evaluate clarity, usability, perceived support, friction, reminders, rewards, and pressure risks.

Unsafe without completed study:

> Users found Ringo supportive.

Unsafe without completed study:

> Tiny missions reduced skipping.

Unsafe without completed study:

> Reminders improved return rate.

Unsafe without completed study:

> RingoStrike improved user motivation.

---

## 15. Evidence priority levels

| Priority | Meaning | Examples |
| --- | --- | --- |
| Critical | Needed before making even cautious product-implementation claims. | Mission flow screenshots, completion recording, behavior logs, rule-based adaptation proof, Ringo message examples. |
| High | Needed before strong portfolio presentation. | Onboarding flow, path/challenge evidence, reward/streak rules, user-flow diagrams. |
| Medium | Useful for strengthening the case study but not required for minimum product description. | Bonus mission evidence, Ringo mood asset map, secondary progress screens. |
| Low | Helpful polish evidence. | Visual variants, minor UI states, optional profile screens. |
| Later | Needed only for future claims or advanced versions. | AI-assisted personalization, long-term pilot data, comparative studies, microrandomized trial design. |

### Critical evidence for the current paper

- [ ] Actual Mission Center screenshot.
- [ ] Actual daily mission example.
- [ ] Mission completion recording.
- [ ] Ringo message examples.
- [ ] Feature-status table based on product artifacts.
- [ ] Code references for implemented core features.
- [ ] Data model for mission completion.
- [ ] Behavior log examples for completion, skip, remind later, and tiredness if those are claimed.
- [ ] Reward/streak rules if rewards or streaks are described as implemented.
- [ ] Reminder scheduling proof if reminders are described as implemented.
- [ ] Study protocol if formative evaluation is discussed.

---

## 16. Minimum evidence needed for portfolio use

For portfolio use, the evidence can be lighter than academic submission, but it must still be honest.

### Minimum portfolio evidence

- [ ] 5–8 screenshots showing the core product or prototype.
- [ ] 1 screen recording of the main mission flow.
- [ ] 1 user-flow diagram from onboarding to mission completion.
- [ ] Clear feature-status labels: implemented, prototype-stage, design concept, planned.
- [ ] Real mission examples.
- [ ] Ringo message examples.
- [ ] At least one example of tiny mission or “Make it smaller” flow, if claimed.
- [ ] Reward or streak screenshot, if claimed.
- [ ] Code references for any feature described as implemented.
- [ ] Clear note that the product is not validated for habit formation.
- [ ] Clear note that user study results are not available unless actually collected.

### Portfolio-safe framing

Use:

> This case study presents an evidence-informed design framework and early prototype direction for RingoStrike.

Use:

> Several features remain design concepts or require implementation evidence.

Avoid:

> RingoStrike is a proven habit-building app.

Avoid:

> Users build better habits with Ringo.

Avoid:

> AI personalizes the user journey.

---

## 17. Minimum evidence needed before preprint

Before preprint, the project needs stronger evidence than a portfolio case study.

### Minimum preprint evidence

- [ ] Complete product-evidence appendix.
- [ ] Screenshots for all features discussed as implemented.
- [ ] Screen recordings for core flows.
- [ ] Code references for implemented features.
- [ ] Data model documentation.
- [ ] Behavior event taxonomy.
- [ ] Anonymized sample logs.
- [ ] Reward/streak calculation documentation.
- [ ] Reminder implementation evidence if reminders are discussed as implemented.
- [ ] Clear implementation-status table in the paper or appendix.
- [ ] Verified references.
- [ ] Consistent citation style.
- [ ] User-study protocol.
- [ ] Consent text.
- [ ] Survey/interview instruments.
- [ ] If no study has been completed, the paper must say the study is proposed.
- [ ] If a study has been completed, results must be reported accurately with sample size, method, limitations, and no overclaiming.

### Preprint-safe framing

Use:

> This paper presents a design framework and documents the implementation status of an early prototype.

Use:

> Future formative evaluation is required to assess usability and perceived support.

Avoid:

> This paper evaluates RingoStrike’s effectiveness.

unless actual evaluation data exists.

---

## 18. Minimum evidence needed before academic submission

Academic submission requires the strongest evidence discipline.

### Minimum academic evidence

- [ ] Verified final reference list.
- [ ] Consistent academic citation style.
- [ ] Clear paper type stated.
- [ ] Explicit non-clinical scope.
- [ ] Complete implementation-status documentation.
- [ ] Product screenshots in appendix or supplementary material.
- [ ] Code references or technical appendix where appropriate.
- [ ] Data model or event taxonomy.
- [ ] Ethics and privacy statement.
- [ ] AI usage disclosure.
- [ ] User-study protocol.
- [ ] Consent text.
- [ ] Survey/interview instruments.
- [ ] Recruitment method.
- [ ] Participant demographics, if a study is conducted and consent allows reporting.
- [ ] Actual user-study results, if making user-experience claims.
- [ ] Behavior logs, if making behavior-pattern claims.
- [ ] Clear limitations.
- [ ] No claims of habit formation without long-term evidence.
- [ ] No claims of wellbeing, productivity, discipline, mental health, or retention improvement without valid data.
- [ ] No claims of AI personalization without implementation and evaluation evidence.
- [ ] No claims that Ringo is perceived as supportive without user perception data.
- [ ] No claims that reminders are caring or effective without user feedback and reminder-response data.
- [ ] No claims that tiny missions improve continuation without logs or study evidence.

### Academic-submission warning

At the current evidence level, RingoStrike is not ready to be submitted as an empirical behavior-change paper.

It may become suitable as:

> A design framework paper.

or:

> A case-study paper with implementation documentation.

or:

> A formative UX study paper.

But only after the required product and/or user evidence is added.

---

## 19. What should not be claimed without evidence

The following claims should not appear in the paper, portfolio, preprint, or academic submission unless direct evidence exists.

### Do not claim product implementation without evidence

Do not claim:

> Users can choose paths.

unless path selection screenshots, flow evidence, and data/code references exist.

Do not claim:

> RingoStrike assigns daily missions.

unless mission assignment logic and UI evidence exist.

Do not claim:

> Users can make any mission smaller.

unless the “Make it smaller” flow is implemented and documented.

Do not claim:

> RingoStrike reminds users later.

unless reminder scheduling and notification proof exist.

Do not claim:

> RingoStrike tracks all behavior signals.

unless event logs and schema prove it.

Do not claim:

> RingoStrike adapts mission intensity.

unless rule logic and state-transition evidence exist.

Do not claim:

> RingoStrike uses AI personalization.

unless AI logic, disclosure, data-use boundaries, and evaluation evidence exist.

### Do not claim user outcomes without user data

Do not claim:

> Tiny missions reduce skipping.

Do not claim:

> Adaptive missions improve continuation.

Do not claim:

> Ringo makes users feel supported.

Do not claim:

> Ringo reminders feel more caring than normal reminders.

Do not claim:

> Rewards motivate users.

Do not claim:

> Streaks improve habit formation.

Do not claim:

> Guided flow reduces confusion.

Do not claim:

> RingoStrike improves wellbeing.

Do not claim:

> RingoStrike improves productivity.

Do not claim:

> RingoStrike improves discipline.

Do not claim:

> RingoStrike improves mental health.

Do not claim:

> RingoStrike improves retention.

Do not claim:

> RingoStrike builds long-term habits.

### Do not overinterpret logs

Do not claim:

> Skipping means low motivation.

Do not claim:

> Inactivity means the user dropped off because the app failed.

Do not claim:

> Completion means the user is forming a habit.

Do not claim:

> Repeated completion proves automaticity.

Do not claim:

> Tapping “I’m too tired” accurately measures the user’s psychological state.

### Safe alternatives

Use:

> is designed to

Use:

> is intended to

Use:

> is proposed as

Use:

> may be evaluated through

Use:

> requires user testing

Use:

> requires behavior logs

Use:

> requires direct product evidence

Use:

> should be treated as a design hypothesis

---

## 20. Final recommendation

The next strongest step for RingoStrike is not adding more theory. The next strongest step is collecting direct product evidence.

The repository should now add a product-evidence layer that includes:

1. Screenshots of every current product screen.
2. Screen recordings of the core flows.
3. Exact code references for implemented features.
4. Data-model documentation.
5. Behavior event taxonomy.
6. Anonymized sample logs.
7. Ringo message library.
8. Reminder implementation proof, if reminders exist.
9. Reward and streak calculation rules.
10. User-study protocol, consent text, and instruments.

Until this evidence exists, RingoStrike should be described as:

> An evidence-informed design framework and early product case study.

The paper and portfolio can discuss the intended feature system, but they must clearly separate:

* implemented features
* prototype-stage interactions
* design concepts
* planned features
* features requiring clarification
* future study claims

The safest current position is strict but useful:

> RingoStrike has a strong research direction and a promising behavior-aware micro-mission framework, but its product implementation evidence is not yet strong enough to support confident implementation claims, user-experience claims, or behavior-change claims.
