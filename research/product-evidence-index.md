# Product Evidence Index — RingoStrike

## 1. Purpose of this file

This file is a living evidence index for RingoStrike.

Its purpose is to provide one structured place to record product evidence as it is collected, reviewed, and verified. The index should help the author track screenshots, screen recordings, code references, data-model evidence, user-flow evidence, behavior logs, Ringo message examples, reminder evidence, reward and streak evidence, and user-study materials.

This file does not claim that evidence already exists.

It should be used to prevent the paper, portfolio case study, preprint draft, or academic-style submission from describing design concepts, planned features, prototype-stage ideas, or framework logic as if they are fully implemented, tested, or effective.

Core rule:

> A feature should not be described as implemented unless direct product evidence exists and has been reviewed.

---

## 2. Evidence boundary

This file is based only on the current repository context and uploaded research materials:

* `product-evidence-checklist.md`
* `paper-implementation-alignment-review.md`
* `paper-implementation-aligned-draft.md`
* `prototype-implementation-status.md`
* `claims-to-support.md`
* `article-master-brief.md`
* `ai-usage-log.md`
* `user-study-plan.md`

No browsing was performed.

No new research was added.

No implementation details were invented.

No screenshots were invented.

No file paths were invented as existing evidence.

No code references were invented.

No user-flow evidence was invented.

No data-model evidence was invented.

No behavior logs were invented.

No user study results were invented.

The current materials support RingoStrike as an evidence-informed design framework, early product concept, and early case-study direction. They do not yet provide enough direct product evidence to confirm most features as stable working implementation.

Therefore, most evidence entries in this index are marked as **Missing** or **Needed** until real artifacts are collected.

---

## 3. How to use this evidence index

Use this file as a repository-level tracking document.

When evidence is collected, add it to the relevant table with:

1. A stable evidence ID.
2. The evidence type.
3. The feature area.
4. The actual file or repository location.
5. What the evidence proves.
6. What the evidence does not prove.
7. The current review status.

Do not mark evidence as **Verified** until it has been checked against the actual product, repository, prototype, or study material.

Do not use screenshots, recordings, or mockups to imply working behavior unless the artifact clearly shows that behavior.

Do not use code references to claim user experience, motivation, usability, or effectiveness. Code can prove that logic exists; it does not prove that users understand or benefit from it.

Do not use behavior logs to infer internal psychological states without survey or interview evidence. For example, skipping a mission may indicate low energy, lack of time, confusion, poor mission fit, technical friction, or lack of interest.

Do not use user-study materials as user-study results. A protocol, consent form, or survey script proves study readiness only; it does not prove user perception or behavior.

### Status labels

| Status | Meaning |
| ------ | ------- |
| Missing | The evidence does not currently exist in the repository or has not been collected. |
| Needed | The evidence is required before stronger claims can be made. |
| Collected | The artifact has been collected, but it has not yet been fully reviewed. |
| Verified | The artifact has been reviewed and can support a limited claim. |
| Needs review | The artifact exists but needs checking, cleaning, anonymization, or interpretation. |
| Not applicable yet | The feature is not implemented or not active enough for this evidence type to apply. |

---

## 4. Evidence folder structure

The following folder structure is recommended for future evidence collection. These folders should not be treated as existing until they are created in the repository.

```text
product-evidence/
  screenshots/
  screen-recordings/
  code-references/
  data-models/
  user-flows/
  behavior-logs/
  ringo-messages/
  reminders/
  rewards-streaks/
  user-study-materials/
  review-notes/
```

### Recommended folder purpose

| Folder | Purpose | Current status |
| ------ | ------- | -------------- |
| `product-evidence/screenshots/` | Product or prototype screenshots. | Needed |
| `product-evidence/screen-recordings/` | Videos showing complete flows. | Needed |
| `product-evidence/code-references/` | Notes linking features to exact code locations after repository inspection. | Needed |
| `product-evidence/data-models/` | Database schemas, Notion schemas, API schemas, or state models. | Needed |
| `product-evidence/user-flows/` | Flow diagrams and step-by-step interaction evidence. | Needed |
| `product-evidence/behavior-logs/` | Anonymized event logs and event dictionaries. | Needed |
| `product-evidence/ringo-messages/` | Ringo message library, trigger map, and screenshots. | Needed |
| `product-evidence/reminders/` | Reminder copy, scheduling proof, notification screenshots, and logs. | Needed |
| `product-evidence/rewards-streaks/` | Reward sequence, XP rules, streak rules, and evidence. | Needed |
| `product-evidence/user-study-materials/` | Protocol, consent text, task script, survey, interview guide, and analysis templates. | Partially collected through planning documents |
| `product-evidence/review-notes/` | Evidence review notes and verification decisions. | Needed |

---

## 5. Evidence naming convention

Use stable IDs so evidence can be referenced across the paper, portfolio, and review files.

### Evidence ID prefixes

| Prefix | Evidence type |
| ------ | ------------- |
| `SS` | Screenshot |
| `SR` | Screen recording |
| `CR` | Code reference |
| `DM` | Data model |
| `UF` | User-flow evidence |
| `LOG` | Behavior log |
| `MSG` | Ringo message evidence |
| `REM` | Reminder evidence |
| `RW` | Reward and streak evidence |
| `UX` | User-study material |

### ID format

Use three digits for each evidence item:

```text
SS-001
SR-001
CR-001
DM-001
UF-001
LOG-001
MSG-001
REM-001
RW-001
UX-001
```

### Recommended file naming format

Use this format after evidence is captured:

```text
<EVIDENCE-ID>__<feature-area>__<short-description>__<YYYY-MM-DD>.<extension>
```

Examples for future use only:

```text
SS-001__mission-center__daily-mission-screen__[add date after capture].png
SR-001__mission-flow__normal-mission-completion__[add date after capture].mp4
CR-001__tiny-missions__component-reference__[add date after repository inspection].md
```

The examples above are naming templates only. They are not evidence that these files currently exist.

---

## 6. Current evidence status summary

Current verdict:

> Product evidence is not yet strong enough to describe most RingoStrike features as implemented, stable, tested, or effective.

The current repository materials are useful for:

* research framing
* claim safety
* implementation-status caution
* product evidence planning
* user-study planning
* paper revision guidance
* AI usage disclosure

The current repository materials are not yet sufficient for:

* proving that most features are implemented
* proving that users understand the flow
* proving that Ringo feels supportive
* proving that tiny missions reduce friction
* proving that reminders are helpful
* proving that rewards or streaks improve engagement
* proving that mission intensity adapts correctly
* proving that behavior logs are collected reliably
* proving that RingoStrike forms long-term habits

### Summary by evidence type

| Evidence type | Current status | Summary |
| ------------- | -------------- | ------- |
| Screenshots | Missing | No actual product screenshot evidence has been indexed yet. |
| Screen recordings | Missing | No complete flow recordings have been indexed yet. |
| Code references | Missing | No inspected code paths or functions have been indexed yet. |
| Data models | Missing | No verified schemas or state models have been indexed yet. |
| User-flow evidence | Missing | No complete flow diagrams or interaction walkthroughs have been indexed yet. |
| Behavior logs | Missing | No anonymized behavior logs have been indexed yet. |
| Ringo messages | Needed | Ringo message examples are needed to prove tone and trigger logic. |
| Reminders | Needed | Reminder implementation, copy, scheduling, and notification proof are needed. |
| Rewards and streaks | Needed | XP, reward, streak, and sequence evidence are needed. |
| User-study materials | Partially collected | `user-study-plan.md` exists as a planning document, but consent text, scripts, survey forms, and collected results are still needed. |

---

## 7. Product evidence inventory table

| Evidence ID | Evidence type | Feature area | File/location | What it proves | What it does not prove | Status |
| ----------- | ------------- | ------------ | ------------- | -------------- | ---------------------- | ------ |
| SS-001 | Screenshot | Landing / first screen | [add screenshot path after capture] | Would show the actual first screen users see. | Would not prove onboarding clarity or user understanding. | Missing |
| SS-002 | Screenshot | Path selection | [add screenshot path after capture] | Would show whether path selection exists visually. | Would not prove users understand paths or complete the flow. | Needed |
| SS-003 | Screenshot | Challenge list or detail | [add screenshot path after capture] | Would show whether challenges exist visually. | Would not prove challenge logic, progression, or motivation. | Needed |
| SS-004 | Screenshot | Daily mission screen | [add screenshot path after capture] | Would show the current mission UI state. | Would not prove mission assignment, completion, or habit formation. | Missing |
| SS-005 | Screenshot | Tiny mission | [add screenshot path after capture] | Would show whether a tiny mission appears in the product or prototype. | Would not prove tiny missions reduce skipping or friction. | Missing |
| SS-006 | Screenshot | Bonus mission | [add screenshot path after capture] | Would show whether optional bonus missions appear. | Would not prove bonus missions motivate users or avoid pressure. | Needed |
| SS-007 | Screenshot | Make it smaller | [add screenshot path after capture] | Would show the interaction surface for reducing mission difficulty. | Would not prove the adaptation logic works. | Missing |
| SS-008 | Screenshot | I’m too tired | [add screenshot path after capture] | Would show the low-energy signal UI. | Would not prove users feel supported by it. | Missing |
| SS-009 | Screenshot | Remind later | [add screenshot path after capture] | Would show the postponement or reminder option. | Would not prove that a real reminder is scheduled or sent. | Missing |
| SS-010 | Screenshot | Skip state | [add screenshot path after capture] | Would show whether skipping is available or how post-skip feedback appears. | Would not prove skipping is non-shaming for users. | Needed |
| SS-011 | Screenshot | Ringo companion | [add screenshot path after capture] | Would show Ringo’s presence in the interface. | Would not prove emotional support or user attachment. | Missing |
| SS-012 | Screenshot | Ringo moods | [add screenshot path after capture] | Would show a specific Ringo mood state. | Would not prove mood trigger logic or emotional effect. | Needed |
| SS-013 | Screenshot | Reward screen | [add screenshot path after capture] | Would show XP, reward, or completion feedback visually. | Would not prove reward clarity, motivation, or habit formation. | Needed |
| SS-014 | Screenshot | Streak display | [add screenshot path after capture] | Would show how streaks are displayed. | Would not prove streak accuracy or user motivation. | Needed |
| SS-015 | Screenshot | Reminder notification | [add screenshot path after capture] | Would show an actual reminder notification if implemented. | Would not prove reminder effectiveness or user receptivity. | Needed |
| SR-001 | Screen recording | First-use flow | [add screen recording path after capture] | Would show interaction continuity from first screen to next action. | Would not prove that users can do it without help. | Missing |
| SR-002 | Screen recording | Normal mission completion | [add screen recording path after capture] | Would show a complete mission completion sequence. | Would not prove long-term engagement or habit formation. | Missing |
| SR-003 | Screen recording | Make it smaller flow | [add screen recording path after capture] | Would show whether a normal mission can become smaller. | Would not prove the smaller mission feels useful. | Missing |
| SR-004 | Screen recording | I’m too tired flow | [add screen recording path after capture] | Would show the system response to a low-energy signal. | Would not prove emotional support or correct interpretation. | Missing |
| SR-005 | Screen recording | Step-by-step reward moment | [add screen recording path after capture] | Would show whether reward feedback is shown gradually. | Would not prove the sequence is satisfying or clear. | Missing |
| CR-001 | Code reference | Mission retrieval/display | [add code path after repository inspection] | Would show where missions are fetched or displayed. | Would not prove mission quality or user clarity. | Missing |
| CR-002 | Code reference | Mission completion | [add code path after repository inspection] | Would show completion logic or handler. | Would not prove behavior change. | Missing |
| CR-003 | Code reference | Tiny missions | [add code path after repository inspection] | Would show whether tiny mission logic exists in code. | Would not prove users choose or value tiny missions. | Missing |
| CR-004 | Code reference | Bonus missions | [add code path after repository inspection] | Would show whether bonus mission logic exists in code. | Would not prove motivation or optionality perception. | Needed |
| CR-005 | Code reference | Rule-based adaptation | [add code path after repository inspection] | Would show whether decision rules are implemented. | Would not prove that rules match user needs. | Missing |
| CR-006 | Code reference | Ringo messages | [add code path after repository inspection] | Would show where message copy or trigger logic lives. | Would not prove users perceive messages as supportive. | Needed |
| CR-007 | Code reference | Reminder scheduling | [add code path after repository inspection] | Would show whether reminder scheduling exists. | Would not prove reminders are sent, opened, or helpful. | Needed |
| CR-008 | Code reference | Reward and streak logic | [add code path after repository inspection] | Would show calculation or display logic. | Would not prove calculations are correct without test cases. | Needed |
| DM-001 | Data model | Paths | [add schema path after inspection] | Would show whether path data exists as a model or schema. | Would not prove path UX clarity. | Needed |
| DM-002 | Data model | Challenges | [add schema path after inspection] | Would show whether challenge data exists. | Would not prove challenge progression or quality. | Needed |
| DM-003 | Data model | Missions | [add schema path after inspection] | Would show whether mission data exists. | Would not prove mission relevance or effectiveness. | Missing |
| DM-004 | Data model | Behavior events | [add schema path after inspection] | Would show whether behavior signals can be stored. | Would not prove events are interpreted correctly. | Missing |
| DM-005 | Data model | Rewards and streaks | [add schema path after inspection] | Would show stored reward or streak fields. | Would not prove streak correctness or user response. | Needed |
| UF-001 | User-flow evidence | Onboarding to first mission | [add user-flow diagram path after creation] | Would show the intended first-use sequence. | Would not prove users complete it without confusion. | Missing |
| UF-002 | User-flow evidence | Daily mission completion | [add user-flow diagram path after creation] | Would show the steps from mission to completion feedback. | Would not prove technical implementation unless matched with product evidence. | Needed |
| UF-003 | User-flow evidence | Low-energy adaptation | [add user-flow diagram path after creation] | Would show how “I’m too tired” or “Make it smaller” should behave. | Would not prove the flow exists in code. | Needed |
| UF-004 | User-flow evidence | Return after inactivity | [add user-flow diagram path after creation] | Would show the intended soft re-entry flow. | Would not prove inactivity detection or reminder behavior. | Needed |
| LOG-001 | Behavior log | Mission completion | [add anonymized log sample after collection] | Would show completion events are recorded. | Would not prove habit formation or motivation. | Missing |
| LOG-002 | Behavior log | Tiny mission selection | [add anonymized log sample after collection] | Would show tiny mission selection events are recorded. | Would not prove tiny missions reduce friction. | Missing |
| LOG-003 | Behavior log | Skip | [add anonymized log sample after collection] | Would show skip events are recorded. | Would not explain why users skipped. | Needed |
| LOG-004 | Behavior log | Remind later | [add anonymized log sample after collection] | Would show postponement events are recorded. | Would not prove reminder scheduling or completion later. | Needed |
| LOG-005 | Behavior log | Reward sequence | [add anonymized log sample after collection] | Would show whether users start or complete reward feedback. | Would not prove reward satisfaction. | Needed |
| MSG-001 | Ringo message evidence | Completion message | [add message library path or screenshot after collection] | Would show exact completion copy. | Would not prove users find it supportive. | Needed |
| MSG-002 | Ringo message evidence | Low-energy message | [add message library path or screenshot after collection] | Would show exact response to tiredness or smaller mission request. | Would not prove emotional safety. | Needed |
| MSG-003 | Ringo message evidence | Skip message | [add message library path or screenshot after collection] | Would show non-shaming skip copy if implemented. | Would not prove users feel non-judged. | Needed |
| MSG-004 | Ringo message evidence | Return message | [add message library path or screenshot after collection] | Would show soft re-entry language. | Would not prove it improves return behavior. | Needed |
| REM-001 | Reminder evidence | Reminder copy | [add reminder copy path after collection] | Would show exact reminder wording. | Would not prove reminders are delivered or helpful. | Needed |
| REM-002 | Reminder evidence | Reminder scheduling | [add scheduling evidence after inspection] | Would show whether reminders can be scheduled. | Would not prove notification receipt or response. | Needed |
| REM-003 | Reminder evidence | Reminder notification | [add notification screenshot after capture] | Would show actual notification delivery if implemented. | Would not prove reminder effectiveness. | Needed |
| RW-001 | Reward and streak evidence | XP rule | [add reward rule path after inspection] | Would show how XP is assigned. | Would not prove XP motivates users. | Needed |
| RW-002 | Reward and streak evidence | Streak rule | [add streak rule path after inspection] | Would show how streaks are calculated or reset. | Would not prove streaks support habit formation. | Needed |
| RW-003 | Reward and streak evidence | Reward sequence | [add screen recording path after capture] | Would show the step-by-step reward moment if implemented. | Would not prove the sequence is clear or emotionally satisfying. | Needed |
| UX-001 | User-study material | Study plan | `user-study-plan.md` | Shows a formative UX/product research plan exists. | Does not prove that the study has been conducted or produced results. | Collected |
| UX-002 | User-study material | Consent text | [add consent document path after creation] | Would show participant consent language. | Would not prove participants consented unless completed consent records exist. | Needed |
| UX-003 | User-study material | Task script | [add task script path after creation] | Would show usability-test tasks. | Would not prove task performance. | Needed |
| UX-004 | User-study material | Survey instrument | [add survey form path after creation] | Would show survey questions and scales. | Would not prove user perception until responses are collected. | Needed |
| UX-005 | User-study material | Interview guide | [add interview guide path after creation] | Would show qualitative interview questions. | Would not prove user feedback until interviews are conducted and analyzed. | Needed |
| UX-006 | User-study material | Study results | [add anonymized results path after study completion] | Would show study findings after collection. | Would not prove long-term habit formation unless the study design supports that claim. | Missing |

---

## 8. Feature-by-feature evidence index

### 8.1 Paths

Current evidence status: **Needed**

Current safe status: **Requires clarification**

Evidence needed:

| Evidence ID | Evidence type | File/location | What it should prove | Status |
| ----------- | ------------- | ------------- | -------------------- | ------ |
| SS-002 | Screenshot | [add screenshot path after capture] | Path selection or path overview exists visually. | Needed |
| DM-001 | Data model | [add schema path after inspection] | Path records or path-like structure exist. | Needed |
| UF-001 | User-flow evidence | [add user-flow diagram path after creation] | User can move from first screen toward a path or first mission. | Needed |
| CR-001 | Code reference | [add code path after repository inspection] | Code supports displaying or retrieving path-related content, if implemented. | Needed |

Safe wording until evidence exists:

> Paths are part of RingoStrike’s proposed product hierarchy and are intended to organize missions into broader self-improvement directions.

Avoid:

> Users choose paths in the current product.

unless screenshots, flow evidence, data model evidence, and code references support it.

### 8.2 Challenges

Current evidence status: **Needed**

Current safe status: **Requires clarification**

Evidence needed:

| Evidence ID | Evidence type | File/location | What it should prove | Status |
| ----------- | ------------- | ------------- | -------------------- | ------ |
| SS-003 | Screenshot | [add screenshot path after capture] | Challenge list or challenge detail exists visually. | Needed |
| DM-002 | Data model | [add schema path after inspection] | Challenge records or challenge-like structure exist. | Needed |
| UF-002 | User-flow evidence | [add user-flow diagram path after creation] | User can move from challenge to mission or progress state. | Needed |
| CR-001 | Code reference | [add code path after repository inspection] | Code supports challenge display, selection, or enrollment, if implemented. | Needed |

Safe wording until evidence exists:

> Challenges are described as structured programs within paths.

Avoid:

> Challenges are fully functional programs in the current app.

unless direct product evidence supports it.

### 8.3 Daily missions

Current evidence status: **Missing**

Current safe status: **Requires clarification**

Evidence needed:

| Evidence ID | Evidence type | File/location | What it should prove | Status |
| ----------- | ------------- | ------------- | -------------------- | ------ |
| SS-004 | Screenshot | [add screenshot path after capture] | Today’s mission screen exists visually. | Missing |
| SR-002 | Screen recording | [add screen recording path after capture] | A normal mission can be completed through the product flow. | Missing |
| DM-003 | Data model | [add schema path after inspection] | Mission content or mission state can be stored. | Missing |
| CR-001 | Code reference | [add code path after repository inspection] | Mission retrieval or display logic exists. | Missing |
| CR-002 | Code reference | [add code path after repository inspection] | Mission completion logic exists. | Missing |
| LOG-001 | Behavior log | [add anonymized log sample after collection] | Mission completion events are recorded. | Missing |

Safe wording until evidence exists:

> Daily missions are a core product concept intended to translate larger goals into concrete daily actions.

Avoid:

> RingoStrike assigns daily missions to users.

unless the assignment and completion flow is documented.

### 8.4 Tiny missions

Current evidence status: **Missing**

Current safe status: **Design concept**

Evidence needed:

| Evidence ID | Evidence type | File/location | What it should prove | Status |
| ----------- | ------------- | ------------- | -------------------- | ------ |
| SS-005 | Screenshot | [add screenshot path after capture] | Tiny mission UI exists visually. | Missing |
| SR-003 | Screen recording | [add screen recording path after capture] | User can move from normal mission to smaller mission. | Missing |
| CR-003 | Code reference | [add code path after repository inspection] | Tiny mission logic exists in implementation. | Missing |
| LOG-002 | Behavior log | [add anonymized log sample after collection] | Tiny mission selection or completion is recorded. | Missing |
| MSG-002 | Ringo message evidence | [add message library path or screenshot after collection] | Ringo has a low-energy or tiny mission response. | Needed |

Safe wording until evidence exists:

> Tiny missions are designed as lower-effort alternatives for moments when the full mission may feel too difficult.

Avoid:

> Tiny missions help users continue or build habits.

unless future user data and logs support it.

### 8.5 Bonus missions

Current evidence status: **Needed**

Current safe status: **Design concept**

Evidence needed:

| Evidence ID | Evidence type | File/location | What it should prove | Status |
| ----------- | ------------- | ------------- | -------------------- | ------ |
| SS-006 | Screenshot | [add screenshot path after capture] | Bonus mission UI exists visually. | Needed |
| CR-004 | Code reference | [add code path after repository inspection] | Bonus mission logic exists, if implemented. | Needed |
| LOG-005 | Behavior log | [add anonymized log sample after collection] | Bonus mission selection or completion can be tracked, if implemented. | Needed |
| RW-001 | Reward and streak evidence | [add reward rule path after inspection] | Bonus mission reward rules exist, if implemented. | Needed |

Safe wording until evidence exists:

> Bonus missions are designed as optional higher-intensity actions for users who want more challenge.

Avoid:

> Bonus missions motivate high-energy users.

unless user testing supports it.

### 8.6 Mission intensity

Current evidence status: **Missing**

Current safe status: **Design concept**

Evidence needed:

| Evidence ID | Evidence type | File/location | What it should prove | Status |
| ----------- | ------------- | ------------- | -------------------- | ------ |
| CR-005 | Code reference | [add code path after repository inspection] | Rule-based adaptation or mission intensity logic exists. | Missing |
| DM-003 | Data model | [add schema path after inspection] | Mission intensity or variant state can be represented. | Missing |
| UF-003 | User-flow evidence | [add user-flow diagram path after creation] | The intended low-energy adaptation flow is documented. | Needed |
| SR-003 | Screen recording | [add screen recording path after capture] | Mission intensity changes can be demonstrated in the product. | Missing |

Safe wording until evidence exists:

> Mission intensity is a proposed behavior-aware design mechanism for offering different task levels based on selected user signals.

Avoid:

> RingoStrike adapts mission intensity in real time.

unless implementation evidence supports that claim.

### 8.7 Make it smaller

Current evidence status: **Missing**

Current safe status: **Design concept**

Evidence needed:

| Evidence ID | Evidence type | File/location | What it should prove | Status |
| ----------- | ------------- | ------------- | -------------------- | ------ |
| SS-007 | Screenshot | [add screenshot path after capture] | The “Make it smaller” control exists visually. | Missing |
| SR-003 | Screen recording | [add screen recording path after capture] | Pressing it changes the mission or offers a smaller version. | Missing |
| CR-003 | Code reference | [add code path after repository inspection] | Smaller mission logic exists, if implemented. | Missing |
| LOG-002 | Behavior log | [add anonymized log sample after collection] | The interaction is recorded as an event. | Missing |
| MSG-002 | Ringo message evidence | [add message library path or screenshot after collection] | Ringo responds in a supportive way. | Needed |

Safe wording until evidence exists:

> “Make it smaller” is designed as a low-friction adaptation pattern that lets users request a smaller version of a mission.

Avoid:

> Users can make any mission smaller.

unless supported by product evidence.

### 8.8 I’m too tired

Current evidence status: **Missing**

Current safe status: **Design concept**

Evidence needed:

| Evidence ID | Evidence type | File/location | What it should prove | Status |
| ----------- | ------------- | ------------- | -------------------- | ------ |
| SS-008 | Screenshot | [add screenshot path after capture] | The “I’m too tired” control exists visually. | Missing |
| SR-004 | Screen recording | [add screen recording path after capture] | The system responds to the low-energy signal. | Missing |
| CR-005 | Code reference | [add code path after repository inspection] | Rule logic exists for this signal, if implemented. | Missing |
| LOG-002 | Behavior log | [add anonymized log sample after collection] | Tiredness-related events are captured. | Missing |
| MSG-002 | Ringo message evidence | [add message library path or screenshot after collection] | The response copy is safe, non-clinical, and non-shaming. | Needed |

Safe wording until evidence exists:

> “I’m too tired” is designed as a user-reported low-energy signal that can guide lower-pressure support.

Avoid:

> RingoStrike knows when the user is tired.

### 8.9 Remind later

Current evidence status: **Missing**

Current safe status: **Requires clarification**

Evidence needed:

| Evidence ID | Evidence type | File/location | What it should prove | Status |
| ----------- | ------------- | ------------- | -------------------- | ------ |
| SS-009 | Screenshot | [add screenshot path after capture] | The “Remind later” option exists visually. | Missing |
| CR-007 | Code reference | [add code path after repository inspection] | Reminder scheduling or postponement logic exists, if implemented. | Needed |
| LOG-004 | Behavior log | [add anonymized log sample after collection] | Remind-later events are recorded. | Needed |
| REM-002 | Reminder evidence | [add scheduling evidence after inspection] | A reminder is actually scheduled, if implemented. | Needed |
| REM-003 | Reminder evidence | [add notification screenshot after capture] | A reminder is delivered, if implemented. | Needed |

Safe wording until evidence exists:

> “Remind later” is intended as a timing-adjustment option.

Avoid:

> RingoStrike schedules reminders after postponement.

unless scheduling evidence exists.

### 8.10 Skip

Current evidence status: **Needed**

Current safe status: **Requires clarification**

Evidence needed:

| Evidence ID | Evidence type | File/location | What it should prove | Status |
| ----------- | ------------- | ------------- | -------------------- | ------ |
| SS-010 | Screenshot | [add screenshot path after capture] | Skip option or post-skip state exists visually. | Needed |
| LOG-003 | Behavior log | [add anonymized log sample after collection] | Skip events are captured. | Needed |
| MSG-003 | Ringo message evidence | [add message library path or screenshot after collection] | Skip response avoids shame or guilt. | Needed |
| RW-002 | Reward and streak evidence | [add streak rule path after inspection] | The effect of skipping on streaks is documented. | Needed |

Safe wording until evidence exists:

> Skip is intended as a non-shaming option for declining a mission.

Avoid:

> Skip helps users feel safe.

unless user testing supports it.

### 8.11 Streaks

Current evidence status: **Needed**

Current safe status: **Requires clarification**

Evidence needed:

| Evidence ID | Evidence type | File/location | What it should prove | Status |
| ----------- | ------------- | ------------- | -------------------- | ------ |
| SS-014 | Screenshot | [add screenshot path after capture] | Streak display exists visually. | Needed |
| CR-008 | Code reference | [add code path after repository inspection] | Streak display or calculation logic exists. | Needed |
| DM-005 | Data model | [add schema path after inspection] | Streak data is stored or derived. | Needed |
| RW-002 | Reward and streak evidence | [add streak rule path after inspection] | Streak calculation, reset, and preservation rules are documented. | Needed |

Safe wording until evidence exists:

> Streaks are intended as continuity feedback, not evidence of habit formation.

Avoid:

> Streaks show that a habit has formed.

### 8.12 XP and rewards

Current evidence status: **Needed**

Current safe status: **Requires clarification**

Evidence needed:

| Evidence ID | Evidence type | File/location | What it should prove | Status |
| ----------- | ------------- | ------------- | -------------------- | ------ |
| SS-013 | Screenshot | [add screenshot path after capture] | XP or reward feedback exists visually. | Needed |
| CR-008 | Code reference | [add code path after repository inspection] | Reward or XP logic exists. | Needed |
| RW-001 | Reward and streak evidence | [add reward rule path after inspection] | Reward and XP rules are documented. | Needed |
| LOG-005 | Behavior log | [add anonymized log sample after collection] | Reward sequence events can be logged. | Needed |

Safe wording until evidence exists:

> XP and rewards are designed as feedback mechanisms.

Avoid:

> XP and rewards improve habit formation.

### 8.13 Step-by-step reward moment

Current evidence status: **Missing**

Current safe status: **Design concept**

Evidence needed:

| Evidence ID | Evidence type | File/location | What it should prove | Status |
| ----------- | ------------- | ------------- | -------------------- | ------ |
| SR-005 | Screen recording | [add screen recording path after capture] | The reward sequence appears step by step. | Missing |
| SS-013 | Screenshot | [add screenshot path after capture] | At least one reward step exists visually. | Needed |
| RW-003 | Reward and streak evidence | [add screen recording path after capture] | Sequence order, exit behavior, and next-action state are documented. | Needed |
| LOG-005 | Behavior log | [add anonymized log sample after collection] | Users start, advance, or exit reward steps, if tracked. | Needed |

Safe wording until evidence exists:

> The step-by-step reward moment is a proposed UX pattern.

Avoid:

> The reward sequence makes feedback clearer or more satisfying.

unless user testing supports it.

### 8.14 Ringo companion

Current evidence status: **Missing**

Current safe status: **Design concept**

Evidence needed:

| Evidence ID | Evidence type | File/location | What it should prove | Status |
| ----------- | ------------- | ------------- | -------------------- | ------ |
| SS-011 | Screenshot | [add screenshot path after capture] | Ringo appears in the product or prototype UI. | Missing |
| MSG-001 | Ringo message evidence | [add message library path or screenshot after collection] | Ringo has actual message copy in at least one state. | Needed |
| CR-006 | Code reference | [add code path after repository inspection] | Ringo message or component logic exists, if implemented. | Needed |
| UX-004 | User-study material | [add survey form path after creation] | Study instruments can evaluate Ringo perception. | Needed |

Safe wording until evidence exists:

> Ringo is designed as the companion interface.

Avoid:

> Ringo makes users feel supported.

unless user perception evidence supports it.

### 8.15 Ringo moods

Current evidence status: **Needed**

Current safe status: **Design concept**

Evidence needed:

| Evidence ID | Evidence type | File/location | What it should prove | Status |
| ----------- | ------------- | ------------- | -------------------- | ------ |
| SS-012 | Screenshot | [add screenshot path after capture] | Specific Ringo mood states exist visually. | Needed |
| CR-006 | Code reference | [add code path after repository inspection] | Mood trigger logic exists, if implemented. | Needed |
| MSG-001 | Ringo message evidence | [add message library path or screenshot after collection] | Mood and message pairing is documented. | Needed |
| UF-003 | User-flow evidence | [add user-flow diagram path after creation] | Mood changes are tied to user actions or states, if implemented. | Needed |

Safe wording until evidence exists:

> Ringo moods are part of the proposed companion design.

Avoid:

> Ringo moods adapt to user behavior.

unless trigger evidence exists.

### 8.16 Adaptive messages

Current evidence status: **Needed**

Current safe status: **Design concept**

Evidence needed:

| Evidence ID | Evidence type | File/location | What it should prove | Status |
| ----------- | ------------- | ------------- | -------------------- | ------ |
| MSG-001 | Ringo message evidence | [add message library path or screenshot after collection] | Exact completion message copy exists. | Needed |
| MSG-002 | Ringo message evidence | [add message library path or screenshot after collection] | Exact low-energy response copy exists. | Needed |
| MSG-003 | Ringo message evidence | [add message library path or screenshot after collection] | Exact skip response copy exists. | Needed |
| MSG-004 | Ringo message evidence | [add message library path or screenshot after collection] | Exact return-after-inactivity copy exists. | Needed |
| CR-006 | Code reference | [add code path after repository inspection] | Message source or trigger logic exists, if implemented. | Needed |

Safe wording until evidence exists:

> Adaptive messages are proposed as behavior-aware responses.

Avoid:

> Ringo understands the user and responds emotionally.

### 8.17 Reminders and notifications

Current evidence status: **Needed**

Current safe status: **Planned or requires clarification**

Evidence needed:

| Evidence ID | Evidence type | File/location | What it should prove | Status |
| ----------- | ------------- | ------------- | -------------------- | ------ |
| REM-001 | Reminder evidence | [add reminder copy path after collection] | Reminder copy exists and can be reviewed for tone. | Needed |
| REM-002 | Reminder evidence | [add scheduling evidence after inspection] | Reminder scheduling exists, if implemented. | Needed |
| REM-003 | Reminder evidence | [add notification screenshot after capture] | Reminder notification is delivered, if implemented. | Needed |
| CR-007 | Code reference | [add code path after repository inspection] | Reminder scheduling or notification code exists, if implemented. | Needed |
| LOG-004 | Behavior log | [add anonymized log sample after collection] | Reminder response events can be tracked, if implemented. | Needed |

Safe wording until evidence exists:

> Reminders are planned or intended as supportive re-engagement cues using autonomy-respecting language.

Avoid:

> Ringo reminders are more caring than normal reminders.

unless a user study or comparison supports it.

### 8.18 Mission logs and behavior signals

Current evidence status: **Missing**

Current safe status: **Requires clarification or design concept**

Evidence needed:

| Evidence ID | Evidence type | File/location | What it should prove | Status |
| ----------- | ------------- | ------------- | -------------------- | ------ |
| DM-004 | Data model | [add schema path after inspection] | Behavior events can be stored. | Missing |
| LOG-001 | Behavior log | [add anonymized log sample after collection] | Mission completion events are logged. | Missing |
| LOG-002 | Behavior log | [add anonymized log sample after collection] | Tiny mission or low-energy interaction events are logged. | Missing |
| LOG-003 | Behavior log | [add anonymized log sample after collection] | Skip events are logged. | Needed |
| LOG-004 | Behavior log | [add anonymized log sample after collection] | Remind-later or reminder response events are logged. | Needed |

Safe wording until evidence exists:

> Behavior signals are proposed as possible inputs for adaptation.

Avoid:

> RingoStrike detects user state.

### 8.19 Rule-based adaptation

Current evidence status: **Missing**

Current safe status: **Design concept**

Evidence needed:

| Evidence ID | Evidence type | File/location | What it should prove | Status |
| ----------- | ------------- | ------------- | -------------------- | ------ |
| CR-005 | Code reference | [add code path after repository inspection] | Adaptation or decision-rule logic exists. | Missing |
| UF-003 | User-flow evidence | [add user-flow diagram path after creation] | The intended decision flow is documented. | Needed |
| SR-003 | Screen recording | [add screen recording path after capture] | A visible state change occurs after a user signal. | Missing |
| MSG-002 | Ringo message evidence | [add message library path or screenshot after collection] | Adaptation response is explained safely to the user. | Needed |

Safe wording until evidence exists:

> RingoStrike frames adaptation as rule-based or behavior-aware design logic.

Avoid:

> RingoStrike uses advanced AI personalization.

unless implementation and evaluation evidence exists.

### 8.20 AI-assisted personalization

Current evidence status: **Not applicable yet**

Current safe status: **Planned future extension**

Evidence needed before any current-product claim:

| Evidence ID | Evidence type | File/location | What it should prove | Status |
| ----------- | ------------- | ------------- | -------------------- | ------ |
| CR-005 | Code reference | [add code path after repository inspection] | AI-assisted personalization is actually implemented, if built. | Not applicable yet |
| DM-004 | Data model | [add schema path after inspection] | Data inputs for personalization are documented and consented to. | Not applicable yet |
| MSG-001 | Ringo message evidence | [add message library path or screenshot after collection] | AI-generated or AI-selected messages are disclosed and bounded, if used. | Not applicable yet |
| UX-004 | User-study material | [add survey form path after creation] | User perception and safety of personalization can be evaluated. | Needed before testing |

Safe wording until evidence exists:

> AI-assisted personalization is a possible future extension, not a validated current feature.

Avoid:

> Ringo learns the user.

unless the system is implemented, documented, disclosed, and evaluated.

---

## 9. Screenshot evidence index

Screenshots should come from the actual product or from a clearly labeled clickable prototype. If a screenshot is from a prototype, label it as prototype evidence and do not use it to claim backend functionality.

| Evidence ID | Screenshot target | File/location | What it proves | Status |
| ----------- | ----------------- | ------------- | -------------- | ------ |
| SS-001 | Landing or first screen | [add screenshot path after capture] | Product entry point exists visually. | Missing |
| SS-002 | Path selection | [add screenshot path after capture] | Path selection exists visually, if implemented. | Needed |
| SS-003 | Challenge list or challenge detail | [add screenshot path after capture] | Challenge UI exists visually, if implemented. | Needed |
| SS-004 | Daily mission screen | [add screenshot path after capture] | Daily mission UI exists visually. | Missing |
| SS-005 | Tiny mission card or state | [add screenshot path after capture] | Tiny mission UI exists visually. | Missing |
| SS-006 | Bonus mission card or state | [add screenshot path after capture] | Bonus mission UI exists visually. | Needed |
| SS-007 | Make it smaller interaction | [add screenshot path after capture] | The control exists visually. | Missing |
| SS-008 | I’m too tired interaction | [add screenshot path after capture] | The low-energy signal exists visually. | Missing |
| SS-009 | Remind later interaction | [add screenshot path after capture] | The reminder/postpone option exists visually. | Missing |
| SS-010 | Skip interaction or post-skip state | [add screenshot path after capture] | Skip UI or feedback exists visually. | Needed |
| SS-011 | Ringo companion in UI | [add screenshot path after capture] | Ringo appears in the interface. | Missing |
| SS-012 | Ringo mood example | [add screenshot path after capture] | A specific Ringo mood appears visually. | Needed |
| SS-013 | Reward or XP feedback | [add screenshot path after capture] | Reward feedback exists visually. | Needed |
| SS-014 | Streak display | [add screenshot path after capture] | Streak feedback exists visually. | Needed |
| SS-015 | Reminder notification | [add screenshot path after capture] | Reminder notification is delivered, if implemented. | Needed |

Screenshot review rule:

> A screenshot proves only that a visual state exists. It does not prove complete functionality, user understanding, behavior change, or effectiveness.

---

## 10. Screen recording evidence index

Screen recordings should show full flows, not isolated states. Use anonymized test accounts and avoid private user data.

| Evidence ID | Recording target | File/location | What it proves | Status |
| ----------- | ---------------- | ------------- | -------------- | ------ |
| SR-001 | First-use flow | [add screen recording path after capture] | The user can move from first screen toward a first action. | Missing |
| SR-002 | Normal mission completion | [add screen recording path after capture] | A normal mission can be completed through the UI. | Missing |
| SR-003 | Make it smaller flow | [add screen recording path after capture] | A mission can be reduced or replaced with a smaller version, if implemented. | Missing |
| SR-004 | I’m too tired flow | [add screen recording path after capture] | The system responds to a low-energy signal, if implemented. | Missing |
| SR-005 | Step-by-step reward sequence | [add screen recording path after capture] | Reward feedback appears as a sequence, if implemented. | Missing |
| SR-006 | Remind later to reminder received | [add screen recording path after capture] | A reminder is scheduled and later received, if implemented. | Needed |
| SR-007 | Return after inactivity | [add screen recording path after capture] | A soft re-entry flow exists, if implemented. | Needed |

Screen recording review rule:

> A recording can prove interaction continuity, but it does not prove that users can complete the flow without confusion unless tested with participants.

---

## 11. Code reference evidence index

Code references must be exact. Add file paths only after inspecting the repository.

Do not invent repository paths.

| Evidence ID | Code target | File/location | What it proves | Status |
| ----------- | ----------- | ------------- | -------------- | ------ |
| CR-001 | Mission retrieval or display | [add code path after repository inspection] | Mission UI or data retrieval logic exists. | Missing |
| CR-002 | Mission completion handler | [add code path after repository inspection] | Completion logic exists. | Missing |
| CR-003 | Tiny mission or smaller mission logic | [add code path after repository inspection] | Tiny/smaller mission logic exists, if implemented. | Missing |
| CR-004 | Bonus mission logic | [add code path after repository inspection] | Bonus mission logic exists, if implemented. | Needed |
| CR-005 | Rule-based adaptation logic | [add code path after repository inspection] | Decision rules exist, if implemented. | Missing |
| CR-006 | Ringo message or mood logic | [add code path after repository inspection] | Message or mood source/trigger logic exists, if implemented. | Needed |
| CR-007 | Reminder scheduling or notification logic | [add code path after repository inspection] | Reminder logic exists, if implemented. | Needed |
| CR-008 | Reward, XP, or streak logic | [add code path after repository inspection] | Reward/streak display or calculation logic exists. | Needed |
| CR-009 | Event logging logic | [add code path after repository inspection] | Behavior events are captured or persisted, if implemented. | Missing |
| CR-010 | AI-assisted personalization logic | [add code path after repository inspection] | AI-assisted personalization exists, if actually implemented. | Not applicable yet |

Code reference review rule:

> Code can support implementation claims, but it cannot support claims about usability, emotional support, motivation, retention, wellbeing, or habit formation.

---

## 12. Data-model evidence index

Data-model evidence should include schemas, field names, state models, database diagrams, API response examples, or documented data structures.

Do not add schema paths until the repository or backend/database has been inspected.

| Evidence ID | Data-model target | File/location | What it proves | Status |
| ----------- | ----------------- | ------------- | -------------- | ------ |
| DM-001 | Path model | [add schema path after inspection] | Path data can be represented, if implemented. | Needed |
| DM-002 | Challenge model | [add schema path after inspection] | Challenge data can be represented, if implemented. | Needed |
| DM-003 | Mission model | [add schema path after inspection] | Mission content, state, or variants can be represented. | Missing |
| DM-004 | Behavior event model | [add schema path after inspection] | Behavior signals can be stored. | Missing |
| DM-005 | Reward and streak model | [add schema path after inspection] | Reward, XP, or streak state can be represented. | Needed |
| DM-006 | Reminder model | [add schema path after inspection] | Reminder time, status, delivery, or response can be represented. | Needed |
| DM-007 | Ringo message model | [add schema path after inspection] | Messages, moods, or triggers can be represented, if implemented. | Needed |
| DM-008 | User-study data model | [add study data template path after creation] | Study responses and logs can be organized safely. | Needed |

Data-model review rule:

> A schema proves that the product can represent data. It does not prove that the data is collected correctly, interpreted correctly, or meaningful to users.

---

## 13. User-flow evidence index

User-flow evidence should show the sequence of screens, decisions, user actions, system responses, Ringo responses, and logged events.

| Evidence ID | User-flow target | File/location | What it proves | Status |
| ----------- | ---------------- | ------------- | -------------- | ------ |
| UF-001 | Onboarding to first mission | [add user-flow diagram path after creation] | First-use flow is documented. | Missing |
| UF-002 | Daily mission completion | [add user-flow diagram path after creation] | Daily mission flow is documented. | Needed |
| UF-003 | Low-energy adaptation | [add user-flow diagram path after creation] | “Make it smaller” or “I’m too tired” flow is documented. | Needed |
| UF-004 | Return after inactivity | [add user-flow diagram path after creation] | Soft re-entry flow is documented. | Needed |
| UF-005 | Remind later flow | [add user-flow diagram path after creation] | Postponement and reminder flow is documented. | Needed |
| UF-006 | Skip flow | [add user-flow diagram path after creation] | Non-shaming skip flow is documented. | Needed |
| UF-007 | Reward sequence flow | [add user-flow diagram path after creation] | Step-by-step reward feedback is documented. | Needed |
| UF-008 | Bonus mission flow | [add user-flow diagram path after creation] | Optional bonus flow is documented, if implemented. | Needed |

User-flow review rule:

> A flow diagram can clarify intended behavior. It does not prove implementation unless matched with screenshots, recordings, code references, or test evidence.

---

## 14. Behavior-log evidence index

Behavior-log evidence should be anonymized before being added to the repository.

Do not include real personal identifiers, private text, raw IP addresses, or sensitive data.

| Evidence ID | Behavior-log target | File/location | What it proves | Status |
| ----------- | ------------------- | ------------- | -------------- | ------ |
| LOG-001 | Mission completed | [add anonymized log sample after collection] | Completion events are captured. | Missing |
| LOG-002 | Tiny mission selected or completed | [add anonymized log sample after collection] | Tiny mission events are captured. | Missing |
| LOG-003 | Mission skipped | [add anonymized log sample after collection] | Skip events are captured. | Needed |
| LOG-004 | Remind later selected | [add anonymized log sample after collection] | Postponement events are captured. | Needed |
| LOG-005 | Reward sequence started/completed/exited | [add anonymized log sample after collection] | Reward interaction events are captured. | Needed |
| LOG-006 | Inactivity or return after inactivity | [add anonymized log sample after collection] | Return or inactivity patterns can be identified. | Needed |
| LOG-007 | Bonus mission selected/completed | [add anonymized log sample after collection] | Bonus mission events are captured, if implemented. | Needed |
| LOG-008 | Reminder sent/opened/clicked | [add anonymized log sample after collection] | Reminder response can be tracked, if implemented. | Needed |

Behavior-log review rule:

> Behavior logs can show what happened in the product. They cannot explain why it happened without user feedback.

---

## 15. Ringo message evidence index

Ringo message evidence should include exact copy, trigger condition, intended tone, risk review, and whether the message is static, rule-based, AI-generated, or manually selected.

| Evidence ID | Message target | File/location | What it proves | Status |
| ----------- | -------------- | ------------- | -------------- | ------ |
| MSG-001 | Completion / celebration message | [add message library path or screenshot after collection] | Ringo’s completion copy exists. | Needed |
| MSG-002 | Low-energy / tiny mission message | [add message library path or screenshot after collection] | Ringo’s response to tiredness or smaller mission request exists. | Needed |
| MSG-003 | Skip / non-shaming message | [add message library path or screenshot after collection] | Ringo’s skip response exists and can be reviewed. | Needed |
| MSG-004 | Return-after-inactivity message | [add message library path or screenshot after collection] | Ringo’s re-entry response exists and can be reviewed. | Needed |
| MSG-005 | Reminder message | [add message library path or screenshot after collection] | Reminder copy exists and can be reviewed. | Needed |
| MSG-006 | Streak-risk message | [add message library path or screenshot after collection] | Streak-risk wording exists and can be reviewed for guilt risk. | Needed |
| MSG-007 | Bonus mission message | [add message library path or screenshot after collection] | Optional challenge wording exists and can be reviewed. | Needed |
| MSG-008 | Explanation of adaptation | [add message library path or screenshot after collection] | The product explains why a mission changed, if implemented. | Needed |

Ringo message review rule:

> Message copy can prove tone intention. Only user feedback can show whether users experience the message as supportive, annoying, childish, caring, intrusive, or pressuring.

---

## 16. Reminder evidence index

Reminder evidence should distinguish between planned reminders, UI reminders, scheduled reminders, delivered notifications, and user response logs.

| Evidence ID | Reminder target | File/location | What it proves | Status |
| ----------- | --------------- | ------------- | -------------- | ------ |
| REM-001 | Reminder copy | [add reminder copy path after collection] | Exact reminder language exists. | Needed |
| REM-002 | Reminder scheduling logic | [add scheduling evidence after inspection] | Reminder scheduling exists, if implemented. | Needed |
| REM-003 | Delivered notification screenshot | [add notification screenshot after capture] | A reminder notification was delivered, if implemented. | Needed |
| REM-004 | Reminder settings / opt-out | [add screenshot path after capture] | Users can control reminders, if implemented. | Needed |
| REM-005 | Reminder response log | [add anonymized log sample after collection] | Open/click/ignore response is tracked, if implemented. | Needed |
| REM-006 | Reminder timing rule | [add rule documentation path after inspection] | Reminder timing logic is documented. | Needed |

Reminder review rule:

> Reminder evidence must not be used to claim that reminders are caring, effective, or better than neutral reminders without user perception data or comparison evidence.

---

## 17. Reward and streak evidence index

Reward and streak evidence should separate visual display, calculation rules, data storage, and user perception.

| Evidence ID | Reward/streak target | File/location | What it proves | Status |
| ----------- | -------------------- | ------------- | -------------- | ------ |
| RW-001 | XP and reward rule | [add reward rule path after inspection] | XP or reward assignment is documented. | Needed |
| RW-002 | Streak calculation rule | [add streak rule path after inspection] | Streak calculation, reset, or preservation rule is documented. | Needed |
| RW-003 | Step-by-step reward sequence | [add screen recording path after capture] | Reward feedback appears step by step, if implemented. | Needed |
| RW-004 | Reward UI screenshot | [add screenshot path after capture] | Reward state exists visually. | Needed |
| RW-005 | Streak UI screenshot | [add screenshot path after capture] | Streak state exists visually. | Needed |
| RW-006 | Reward interaction log | [add anonymized log sample after collection] | User interaction with reward sequence is tracked, if implemented. | Needed |
| RW-007 | Pressure/guilt review note | [add review note path after evaluation] | Reward/streak language has been reviewed for pressure risk. | Needed |

Reward and streak review rule:

> Rewards and streaks should be described as feedback mechanisms. They should not be described as evidence of habit formation.

---

## 18. User-study material evidence index

The current project has a user-study plan, but the study has not been conducted according to the available evidence.

User-study materials should be separated from user-study results.

| Evidence ID | User-study material | File/location | What it proves | Status |
| ----------- | ------------------- | ------------- | -------------- | ------ |
| UX-001 | Study plan | `user-study-plan.md` | A formative UX/product research plan exists. | Collected |
| UX-002 | Consent text | [add consent document path after creation] | Participants can be informed about purpose, data use, recordings, and limits. | Needed |
| UX-003 | Moderated usability task script | [add task script path after creation] | Version A usability tasks are ready to run. | Needed |
| UX-004 | Survey instrument | [add survey form path after creation] | Ratings and open-ended questions are ready to collect. | Needed |
| UX-005 | Interview guide | [add interview guide path after creation] | Follow-up questions are ready. | Needed |
| UX-006 | Recruitment message | [add recruitment text path after creation] | Participants can be invited without overclaiming product benefits. | Needed |
| UX-007 | Data handling plan | [add data handling path after creation] | Logs, recordings, and responses can be handled responsibly. | Needed |
| UX-008 | Study results | [add anonymized results path after study completion] | User feedback and observations exist after the study. | Missing |
| UX-009 | Analysis notes | [add analysis notes path after study completion] | Findings have been interpreted and reviewed. | Missing |
| UX-010 | Participant quote evidence | [add anonymized quote file after study completion] | User perception can be quoted safely, if consented. | Missing |

User-study review rule:

> A study plan proves readiness. It does not prove user perception, usability, engagement, motivation, emotional support, or behavior change.

---

## 19. Evidence gaps by priority

### Critical gaps

These gaps should be addressed before the paper or portfolio makes stronger product claims.

| Priority | Evidence gap | Why it matters | Status |
| -------- | ------------ | -------------- | ------ |
| Critical | Daily mission screen and completion flow | Daily missions are central to the product concept. | Missing |
| Critical | Ringo companion UI and message examples | Ringo is central to the paper identity and must be visible as product evidence. | Missing |
| Critical | Tiny mission / Make it smaller evidence | Tiny missions are central to the framework but currently need direct evidence. | Missing |
| Critical | I’m too tired evidence | This is an emotional-state signal and needs careful proof and safety review. | Missing |
| Critical | Behavior event logging evidence | The framework depends on behavior signals, but logs are not yet indexed. | Missing |
| Critical | Rule-based adaptation evidence | Adaptation must not be claimed without decision-rule or flow evidence. | Missing |
| Critical | User-study consent, task script, survey, and interview guide | The current plan must be turned into usable study materials. | Needed |

### High-priority gaps

| Priority | Evidence gap | Why it matters | Status |
| -------- | ------------ | -------------- | ------ |
| High | Onboarding / guided flow evidence | The paper discusses guided flow and decision burden. | Needed |
| High | Path and challenge screenshots or schema | The product hierarchy needs direct evidence. | Needed |
| High | Reward and XP evidence | Rewards are a key feature but need rules and screenshots. | Needed |
| High | Streak evidence | Streaks are high-risk because they can imply habit formation. | Needed |
| High | Skip and non-shaming response evidence | Skip behavior must be safe and non-guilt-based. | Needed |
| High | Reminder copy and scheduling evidence | Reminders are planned/intended but need implementation proof. | Needed |

### Medium-priority gaps

| Priority | Evidence gap | Why it matters | Status |
| -------- | ------------ | -------------- | ------ |
| Medium | Bonus mission evidence | Bonus missions are useful but less central than tiny missions. | Needed |
| Medium | Ringo mood asset and trigger evidence | Mood system is part of the companion design but may remain conceptual. | Needed |
| Medium | Step-by-step reward fatigue evidence | The sequence could become repetitive and needs user feedback. | Needed |
| Medium | Reminder settings or opt-out evidence | User control is important for ethical reminder design. | Needed |

### Later gaps

| Priority | Evidence gap | Why it matters | Status |
| -------- | ------------ | -------------- | ------ |
| Later | AI-assisted personalization evidence | This should not be claimed until actually implemented and evaluated. | Not applicable yet |
| Later | Long-term habit-strength measurement | Needed only if the paper later claims habit formation. | Not applicable yet |
| Later | Controlled comparison between static and adaptive missions | Needed for stronger adaptive-intervention claims. | Not applicable yet |
| Later | Comparison between Ringo reminders and neutral reminders | Needed for claims about Ringo reminders feeling more caring. | Not applicable yet |

---

## 20. Safe paper wording based on current evidence

Use wording that clearly separates design intent from evidence.

### Safe general wording

> RingoStrike is an evidence-informed design framework and early product case study.

> The current materials define a proposed feature system and behavior-aware micro-mission framework.

> Direct product evidence is still needed before most features can be described as implemented.

> The paper explores design rationale, not validated behavior-change effectiveness.

### Safe implementation wording

> The available research files describe RingoStrike as conceptually organized around paths, challenges, missions, behavior signals, Ringo messages, reminders, rewards, and streaks.

> Implementation status remains unclear for several features and requires screenshots, code references, user-flow evidence, data-model evidence, and behavior logs.

> Some features should be described as proposed, planned, design-concept, prototype-stage, or requiring clarification until product artifacts are added.

### Safe adaptation wording

> RingoStrike explores rule-based or behavior-aware adaptation as a design strategy.

> Behavior signals are treated as imperfect indicators, not proof of the user’s internal psychological state.

> Whether mission adaptation improves clarity, perceived support, completion, or continuation requires future evaluation.

### Safe Ringo wording

> Ringo is designed as a companion interface intended to make guidance, reminders, and feedback feel more supportive and less mechanical.

> Whether users experience Ringo as supportive, annoying, childish, caring, intrusive, or pressuring should be evaluated through usability testing, surveys, and interviews.

### Safe tiny mission wording

> Tiny missions are designed as lower-effort alternatives for moments when the full mission may feel too difficult.

> Their effect on completion, skipping, continuation, retention, or habit formation in RingoStrike requires product logs and user testing.

### Safe reminder wording

> Ringo-style reminders are planned or intended as re-engagement cues using supportive, autonomy-respecting language.

> User testing and reminder-response data are needed to evaluate whether these reminders are perceived as helpful, caring, intrusive, or pressuring.

### Safe reward and streak wording

> Streaks, XP, rewards, and progress feedback are designed as feedback mechanisms.

> They should not be treated as evidence of habit formation.

### Safe user-study wording

> A formative UX/product study is proposed to evaluate clarity, usability, perceived support, friction, reminders, rewards, and pressure or guilt risks.

> The study has not yet produced results unless future evidence is added.

---

## 21. Evidence required before updating the paper

Before updating the paper to make stronger product claims, collect and review the following evidence.

### Minimum evidence before stronger portfolio wording

| Required evidence | Evidence IDs | Status |
| ----------------- | ------------ | ------ |
| Screenshots of first screen, mission screen, Ringo companion, and reward/streak screen | SS-001, SS-004, SS-011, SS-013, SS-014 | Missing / Needed |
| Screen recording of normal mission completion | SR-002 | Missing |
| At least one user-flow diagram for onboarding to mission completion | UF-001, UF-002 | Missing / Needed |
| Exact Ringo message examples for completion, skip, tiredness, and return | MSG-001, MSG-002, MSG-003, MSG-004 | Needed |
| Code references for mission display, completion, rewards, and logs | CR-001, CR-002, CR-008, CR-009 | Missing / Needed |
| Data-model evidence for missions and behavior events | DM-003, DM-004 | Missing |
| User-study consent, task script, survey, and interview guide | UX-002, UX-003, UX-004, UX-005 | Needed |

### Minimum evidence before preprint or academic-style submission

| Required evidence | Evidence IDs | Status |
| ----------------- | ------------ | ------ |
| Verified screenshots and recordings for all major flows discussed in the paper | SS-001 to SS-015, SR-001 to SR-007 | Missing / Needed |
| Exact code references for implemented feature claims | CR-001 to CR-009 | Missing / Needed |
| Data model and anonymized sample logs for behavior signals | DM-003, DM-004, LOG-001 to LOG-008 | Missing / Needed |
| Reminder implementation and response evidence if reminders are discussed as current features | REM-001 to REM-006 | Needed |
| Reward and streak rules if XP/streaks are discussed as current features | RW-001 to RW-007 | Needed |
| Completed formative user study results if user perception claims are made | UX-008, UX-009, UX-010 | Missing |
| Verified references and consistent citation formatting | Separate reference verification file | Needed |

### Evidence needed before claiming implementation

A feature can be described as implemented only when at least three evidence types support it:

1. Visual evidence, such as a screenshot or recording.
2. Technical evidence, such as code reference or data model.
3. Flow or behavior evidence, such as a user-flow diagram, state transition, or anonymized log.

For high-risk features such as Ringo messages, reminders, streaks, and emotional support, user feedback is also needed before making perception claims.

### Evidence needed before claiming effectiveness

The paper must not claim effectiveness without empirical evidence.

Claims that require user-study data or longer-term logs include:

* Tiny missions reduce skipping.
* Tiny missions increase completion.
* Tiny missions support retention.
* Ringo makes users feel supported.
* Ringo reminders feel more caring than neutral reminders.
* Guided flow reduces confusion.
* Rewards feel satisfying.
* Streaks motivate users without pressure.
* Rule-based adaptation improves continuation.
* RingoStrike supports long-term habit formation.

---

## 22. Final recommendation

The next step for the repository is not another stronger paper claim.

The next step is evidence collection.

The paper is currently safest when framed as:

> An evidence-informed design framework and early product case study.

It should not yet be framed as:

> A validated habit-building system.

or:

> A fully implemented adaptive companion product.

or:

> A proven intervention for wellbeing, productivity, discipline, motivation, retention, or long-term habit formation.

Recommended immediate priorities:

1. Capture screenshots of the actual product or clearly labeled prototype.
2. Record the core mission completion flow.
3. Inspect the repository and add exact code references.
4. Document the data model for missions, behavior events, rewards, streaks, and reminders.
5. Build user-flow diagrams for onboarding, mission completion, low-energy adaptation, reminder behavior, skip behavior, and reward feedback.
6. Create a Ringo message library with exact copy and trigger notes.
7. Prepare consent text, task script, survey, and interview guide for the formative UX study.
8. Collect anonymized logs only after the data model and privacy boundaries are clear.
9. Keep all paper wording cautious until evidence is collected and reviewed.

Final evidence rule:

> If an artifact has not been collected, reviewed, and linked in this index, the paper should not rely on it as evidence.
