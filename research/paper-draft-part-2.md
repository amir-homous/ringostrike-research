## 4. Behavior-Aware Micro-Mission Framework

The central contribution of this paper is the Behavior-Aware Micro-Mission Framework. The framework describes how RingoStrike is designed to move from user behavior signals to adaptive mission support, companion response, feedback, and the next action. It is not presented as a validated behavior-change model. Instead, it is a design framework that translates habit-formation, behavior-change, adaptive intervention, motivational, gamification, and companion-agent concepts into a concrete product logic.

The framework follows this flow:

```text
User behavior signal
→ cautious user-state interpretation
→ mission adaptation
→ Ringo companion response
→ feedback/reward loop
→ next action
```

The purpose of this flow is to avoid treating habit-building as a fixed checklist. In many habit apps, a user either completes a task or fails to complete it. RingoStrike instead treats user actions such as skipping, postponing, reporting tiredness, completing a tiny mission, or returning after inactivity as behavior signals that may indicate different support needs. These signals are useful, but they are imperfect. A skipped mission may mean low energy, confusion, lack of time, poor mission fit, technical difficulty, or lack of interest. For this reason, the system should not assume that it understands the user’s internal psychological state. It should interpret behavior cautiously and offer support in a way that preserves user autonomy.

### 4.1 User Behavior Signal

The first stage is the user behavior signal. Signals may be directly selected by the user, such as tapping “I’m too tired,” “Make it smaller,” “Remind later,” or “Skip.” Signals may also be inferred from interaction patterns, such as mission completion, repeated completion, inactivity, tiny mission selection, or bonus mission selection.

These signals are not evidence of habit formation. They are short-term interaction data that can help the system decide what kind of support to offer next. For example, mission completion shows that the user completed the action in that moment, but it does not prove automaticity. Similarly, inactivity may suggest drop-off risk, but it does not explain why the user stopped using the app.

### 4.2 Cautious User-State Interpretation

The second stage is cautious interpretation. RingoStrike may interpret a behavior signal as a possible indicator of a user state, such as low energy, overwhelm, high momentum, returning after inactivity, or need for clarity. These states should be treated as design interpretations rather than psychological labels.

For example, if a user taps “I’m too tired,” the system may interpret this as a low-energy signal. If a user repeatedly completes missions, the system may interpret this as consistency or momentum. If a user skips a mission, the system should treat the signal as ambiguous rather than assuming laziness or lack of discipline.

The key principle is that RingoStrike should adapt without pretending to fully understand the user. A safer system response would be:

> “Looks like today might need a smaller step. Want to make this easier?”

A risky response would be:

> “I know exactly how you feel.”

The first response offers support while preserving uncertainty. The second overstates the system’s emotional understanding.

### 4.3 Mission Adaptation

The third stage is mission adaptation. Based on the signal and cautious interpretation, RingoStrike may adjust the mission experience. Possible adaptations include keeping the normal mission, offering a tiny mission, offering a recovery mission, reducing mission difficulty, delaying a reminder, sending a supportive check-in, offering an optional bonus mission, or asking the user what they need.

Mission adaptation should be transparent and simple. If the system changes the mission, the user should understand why. For example:

> “I made this one smaller because you asked for a lighter mission today.”

This kind of explanation helps prevent adaptation from feeling random, patronizing, or manipulative. It also makes clear that the system is responding to a specific behavior signal rather than claiming deep personalization.

### 4.4 Ringo Companion Response

The fourth stage is Ringo’s companion response. Ringo is designed to provide emotionally supportive feedback around user actions. The companion response may include a short message, a visual mood, or a prompt for the next action.

Ringo’s response should match the interaction context. Completion may trigger celebration. Tiredness may trigger low-energy support. Skipping may trigger a non-judgmental check-in. Returning after inactivity may trigger a warm re-entry message. Repeated completion may trigger proud but non-pressuring encouragement.

The tone should avoid shame, guilt, or emotional manipulation. Ringo should not imply that the user has disappointed the companion, failed morally, or lost personal worth because they skipped a mission. Ringo should also avoid therapeutic or clinical language unless the product is properly evaluated and governed as a health or therapy tool.

### 4.5 Feedback and Reward Loop

The fifth stage is the feedback and reward loop. When a mission is completed, RingoStrike may show a sequence of feedback elements: completion confirmation, Ringo’s reaction, XP or reward earned, path or challenge progress, streak update, achievement, and suggested next action.

This reward loop is designed to make progress visible and emotionally noticeable. However, rewards should be framed as informational feedback, not as the primary reason to act. Streaks should represent continuity, not moral judgment. XP should recognize effort, not define the value of the user. Tiny mission completion should also count as valid progress, because the point of a tiny mission is to preserve low-pressure action on difficult days.

The reward loop requires future evaluation. It may make progress clearer and more satisfying, but it could also feel slow, repetitive, childish, or overly focused on points.

### 4.6 Next Action

The final stage is the next action. After the system responds, the user should know what to do next. This may mean stopping for the day, choosing a bonus mission, scheduling a reminder, switching to a tiny mission, selecting a recovery mission, or returning tomorrow.

The next action should be clear and low-pressure. RingoStrike should not push users into endless task completion. A high-momentum user may be offered an optional bonus mission, but the option to stop should remain acceptable. A tired user may be offered a tiny mission or a rest-friendly next step. A returning user should be guided toward a small re-entry action rather than being asked to recover everything at once.

### 4.7 Example Behavior Scenarios

#### User taps “I’m too tired”

When the user taps “I’m too tired,” RingoStrike receives an explicit low-energy signal. The system may cautiously interpret this as a need for lower effort or recovery support. The mission can be adapted into a tiny or recovery mission. Ringo’s response should validate the user’s state without dramatizing it:

> “That’s okay. Let’s make this lighter today. A tiny step still counts.”

If the user completes the tiny mission, the reward loop should treat it as real progress. The next action may be to stop for the day or schedule a gentle reminder. This interaction is intended to reduce friction, but it does not prove that tiny missions improve retention or habit formation.

#### User taps “Make it smaller”

When the user taps “Make it smaller,” the system receives a signal that the current mission may feel too large, unclear, or effortful. The system can reduce the mission difficulty and replace the original mission with a smaller version.

For example, a normal mission such as “Write for 20 minutes” could become “Write one sentence.” Ringo’s response should frame this as adaptive support rather than failure:

> “Good call. Let’s shrink it. One small version is better than forcing the full one.”

The next action should be the smaller mission only. The user should not be shown many additional choices at this moment, because the signal may indicate overwhelm.

#### User selects “Remind later”

When the user selects “Remind later,” RingoStrike should treat the signal as a timing adjustment, not failure. The system may delay the reminder and keep the mission available. Ringo’s response should respect autonomy:

> “No problem. I’ll remind you later so you can decide then.”

No reward should be given because the mission has not been completed. The main design risk is that reminders may become intrusive or guilt-inducing if the timing, frequency, or language is poorly designed. Future user testing should examine whether users feel helped, annoyed, pressured, or supported by Ringo-style reminders.

#### User skips a mission

When the user skips a mission, the signal is ambiguous. It may mean the mission was too difficult, irrelevant, unclear, badly timed, or simply not wanted that day. RingoStrike should not interpret skipping as laziness or lack of discipline.

A cautious response would be:

> “Okay. Want to leave it for today, make it smaller, or try a recovery mission instead?”

This response gives the user options without shame. The system may log the skip as a behavior signal, but it should not draw strong conclusions from the skip alone. Future evaluation should combine skip logs with survey and interview data to understand why users skip.

#### User returns after inactivity

When a user returns after inactivity, RingoStrike should treat this as a re-engagement opportunity rather than a failure moment. The system may cautiously interpret the signal as returning after a break or possible drop-off recovery. The mission adaptation should be simple: one recovery mission or one tiny mission.

Ringo’s response should avoid guilt:

> “Welcome back. No need to fix everything today. Let’s restart with one small mission.”

The next action should be clear and easy to complete. This scenario is especially important because many habit-building experiences become emotionally difficult after missed days. If the app makes the user feel behind, judged, or punished, the user may disengage further.

#### User repeatedly completes missions

Repeated completion may suggest consistency, momentum, or good mission fit. However, it should not be described as proof of habit formation. The system may keep the normal mission difficulty, celebrate continuity, or offer an optional bonus mission.

Ringo’s response should support momentum without pressure:

> “You’ve got good momentum today. Want an optional bonus mission, or are we done for now?”

This preserves autonomy. Bonus missions should not become an expectation or hidden requirement. Future evaluation should examine whether repeated completion predicts continued engagement, whether bonus missions feel motivating, and whether users feel safe declining extra work.

#### User selects a bonus mission

When the user selects a bonus mission, the system may cautiously interpret this as high momentum or interest in extra challenge. The mission adaptation is to provide an optional higher-intensity action. Ringo’s response may be more enthusiastic, but it should still avoid pressure:

> “Nice. This one is extra. Do it only if it feels good today.”

The reward loop can recognize bonus effort separately, but the app should avoid making bonus completion feel necessary for success. Bonus missions are intended to support motivated users without forcing the same intensity on tired users.

---

## 5. Feature-to-Theory Mapping

The following feature-to-theory map summarizes how RingoStrike’s main features connect to relevant behavior, motivation, adaptive intervention, gamification, UX, reminder, and ethical design concepts. This table is a design rationale, not evidence that the features are effective in RingoStrike.

### 5.1 Structure Features

| RingoStrike feature | Related theory or concept                                                     | Intended design purpose                                                   | Related claim    | Main risk or limitation                                          | Evidence still needed                                                           |
| ------------------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------------------- | ---------------- | ---------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| Paths               | Goal setting; habit context; guided flow; UX simplification                   | Organize broad self-improvement directions into understandable categories | Claim 6; Claim 7 | Too many paths may increase decision burden                      | Usability evidence showing whether users understand paths and find them helpful |
| Challenges          | Action planning; graded tasks; competence support; Behavior Change Techniques | Translate a broad path into a structured sequence of actions              | Claim 6; Claim 8 | Challenges may feel rigid or pressure-based                      | User feedback on whether challenges feel clear, flexible, and meaningful        |
| Daily missions      | Repetition; prompts/cues; self-monitoring; feedback on behavior               | Give the user one concrete action to complete today                       | Claim 6; Claim 7 | Missions may become repetitive, too difficult, or poorly matched | Completion logs, clarity ratings, and interviews about mission relevance        |

### 5.2 Adaptation Features

| RingoStrike feature | Related theory or concept                                                  | Intended design purpose                                                  | Related claim                      | Main risk or limitation                                                    | Evidence still needed                                                                |
| ------------------- | -------------------------------------------------------------------------- | ------------------------------------------------------------------------ | ---------------------------------- | -------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| Tiny missions       | Micro-behaviors; friction reduction; graded tasks; effort-optimized design | Offer a lower-effort action during low-energy or high-friction moments   | Claim 1                            | Tiny missions may feel too small, childish, or meaningless                 | Tiny mission selection/completion logs and user perception data                      |
| Bonus missions      | Autonomy support; competence support; adaptive difficulty; gamification    | Offer optional extra challenge for users with more energy or momentum    | Claim 8                            | Bonus missions may create pressure if users feel they should complete them | Data on voluntary use, perceived pressure, and satisfaction                          |
| Mission intensity   | Adaptive intervention; tailoring variables; intervention options           | Adjust task difficulty through tiny, normal, bonus, or recovery variants | Claim 2; Claim 7; Claim 8          | Users may not understand why a mission changed                             | Evidence that users understand and accept intensity changes                          |
| Make it smaller     | Friction reduction; adaptive difficulty; autonomy support                  | Let users reduce task size instead of abandoning the mission             | Claim 1; Claim 2                   | Users may overuse smaller tasks or interpret them as lower standards       | Logs showing whether this reduces skipping and interviews about perceived usefulness |
| I’m too tired       | Explicit user-state signal; recovery-oriented design; supportive feedback  | Let users communicate low energy and receive lower-pressure support      | Claim 1; Claim 2; Claim 3; Claim 7 | The system may normalize avoidance or respond too strongly                 | User feedback on whether the response feels supportive, useful, or avoidant          |
| Recovery missions   | Re-entry support; drop-off recovery; low-pressure design                   | Help users restart after missed days or inactivity                       | Claim 1; Claim 2; Claim 7          | Recovery may feel like punishment if framed poorly                         | Return-after-inactivity logs and interviews about re-entry experience                |

### 5.3 Companion Features

| RingoStrike feature | Related theory or concept                                                         | Intended design purpose                                                           | Related claim                       | Main risk or limitation                                         | Evidence still needed                                                               |
| ------------------- | --------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- | ----------------------------------- | --------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| Ringo companion     | Digital companions; conversational agents; relatedness; Self-Determination Theory | Make guidance, feedback, and reminders feel warmer and less mechanical            | Claim 3; Claim 10                   | Ringo may feel childish, annoying, manipulative, or unnecessary | Interviews and surveys on perceived support, trust, annoyance, and emotional safety |
| Ringo moods         | Emotional feedback; companion-agent design; gamified feedback                     | Make Ringo’s response visually and emotionally legible                            | Claim 3; Claim 9; Claim 10          | Sad or warning moods may create guilt                           | Testing whether users interpret moods correctly and safely                          |
| Adaptive messages   | Adaptive intervention; autonomy-supportive feedback; ethical persuasive design    | Change feedback based on completion, skipping, tiredness, inactivity, or momentum | Claim 2; Claim 3; Claim 7; Claim 10 | Messages may feel fake, repetitive, wrong, or over-personalized | Message testing, user interviews, and logs of response patterns                     |

### 5.4 Feedback and Reward Features

| RingoStrike feature        | Related theory or concept                                     | Intended design purpose                                                 | Related claim    | Main risk or limitation                                            | Evidence still needed                                                                |
| -------------------------- | ------------------------------------------------------------- | ----------------------------------------------------------------------- | ---------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| XP                         | Gamification; progress feedback; competence support           | Make completed effort visible and recognizable                          | Claim 4; Claim 9 | XP may become a shallow or controlling motivator                   | User feedback on whether XP feels meaningful or distracting                          |
| Rewards                    | Feedback on behavior; gamification; informational feedback    | Recognize completion and make progress emotionally noticeable           | Claim 4; Claim 9 | Rewards may shift focus away from the behavior itself              | Evidence on reward satisfaction, repetition fatigue, and pressure risk               |
| Streaks                    | Continuity feedback; progress monitoring; gamification        | Show repeated engagement across days or sessions                        | Claim 4          | Streak loss may create guilt, pressure, or all-or-nothing thinking | Data on streak perception, streak-loss reactions, and continuation after missed days |
| Step-by-step reward moment | Progressive disclosure; progress feedback; emotional feedback | Present completion, XP, progress, streaks, and Ringo reaction gradually | Claim 9; Claim 4 | The sequence may feel slow, excessive, or childish over time       | Usability testing comparing clarity and satisfaction with fatigue risk               |

### 5.5 Reminder and Re-Engagement Features

| RingoStrike feature                  | Related theory or concept                               | Intended design purpose                                     | Related claim                       | Main risk or limitation                                 | Evidence still needed                                                   |
| ------------------------------------ | ------------------------------------------------------- | ----------------------------------------------------------- | ----------------------------------- | ------------------------------------------------------- | ----------------------------------------------------------------------- |
| Reminders and notifications          | Prompts/cues; notification receptivity; reminder timing | Bring users back to the app and support daily action        | Claim 5; Claim 7                    | Reminders may become intrusive or annoying              | Reminder response data and user feedback on timing, frequency, and tone |
| Remind later                         | Autonomy support; timing adjustment; user control       | Let users postpone without treating postponement as failure | Claim 2; Claim 5; Claim 7           | Users may postpone repeatedly without returning         | Logs on remind-later use and follow-up completion                       |
| Streak risk reminders                | Continuity support; re-engagement; gamification risk    | Alert users before losing continuity, if appropriate        | Claim 4; Claim 5; Claim 10          | Streak warnings may create guilt or anxiety             | User feedback on whether warnings feel helpful or pressuring            |
| Returning-after-inactivity check-ins | Recovery support; re-engagement; non-shaming design     | Help users restart after a break with one small action      | Claim 2; Claim 3; Claim 7; Claim 10 | Re-entry messages may feel judgmental if written poorly | Interviews with returning users and drop-off/re-entry logs              |

### 5.6 Logging and Ethics Features

| RingoStrike feature   | Related theory or concept                                      | Intended design purpose                                                                | Related claim     | Main risk or limitation                                      | Evidence still needed                                             |
| --------------------- | -------------------------------------------------------------- | -------------------------------------------------------------------------------------- | ----------------- | ------------------------------------------------------------ | ----------------------------------------------------------------- |
| Mission logs          | Self-monitoring; behavior signals; evaluation data             | Record completion, skipping, remind-later, tiny mission use, bonus use, and inactivity | Claim 7           | Logs cannot explain user motivation without qualitative data | Combined behavioral logs, surveys, and interviews                 |
| User behavior signals | Adaptive intervention tailoring variables                      | Provide inputs for rule-based or behavior-aware adaptation                             | Claim 7           | Signals may be misread or overinterpreted                    | Evidence that signals correspond to useful support needs          |
| Ethical boundaries    | Persuasive design ethics; autonomy; privacy; anti-shame design | Reduce risks of guilt, manipulation, dependency, and over-personalization              | Claim 10          | Boundaries may be stated but not experienced by users        | User feedback on pressure, guilt, autonomy, and data transparency |
| User control          | Autonomy support; responsible personalization                  | Allow users to skip, postpone, stop, control reminders, and choose smaller missions    | Claim 5; Claim 10 | Control options may add complexity if poorly presented       | Usability testing on whether control feels clear and manageable   |

---

## 6. Early Prototype / Case Study Description

RingoStrike is presented in this paper as an early prototype and product case study. The prototype is used to demonstrate how the Behavior-Aware Micro-Mission Framework can be translated into product interactions. It should not be presented as evidence that the framework changes behavior, improves wellbeing, increases productivity, or produces long-term habit formation.

The current repository materials describe RingoStrike as a habit-building app built around paths, challenges, missions, tiny missions, bonus missions, reminders, rewards, behavior logs, and an emotionally supportive companion named Ringo. The materials also describe a design direction in which Ringo guides the user toward a clear next action, responds to behavior signals, and supports adaptive mission intensity.

However, the implementation status of some features is not fully established in the current research files. Therefore, this section distinguishes between features that are described as part of the product concept, features that appear to be prototype-level design elements, and features whose implementation status should be clarified before final publication.

### 6.1 Prototype Scope

The prototype is intended to demonstrate the following product logic:

```text
Path
→ Challenge
→ Daily mission
→ Tiny / normal / bonus / recovery mission variant
→ User action
→ Ringo response
→ Reward or reminder loop
→ Next action
```

This hierarchy is designed to help users move from broad self-improvement goals toward small daily actions. Paths provide broad direction. Challenges structure that direction into a more specific program. Daily missions give the user a concrete action. Tiny, bonus, and recovery missions adapt the level of effort. Ringo provides guidance, feedback, reminders, and emotional continuity.

### 6.2 Current Feature Status

| Feature or component        | Description in the case study                                                                    | Current status for the paper                                                                 |
| --------------------------- | ------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------- |
| Paths                       | Broad self-improvement directions such as focus, health, creativity, or personal growth          | Conceptual/prototype-level; implementation status to be clarified                            |
| Challenges                  | Structured programs within paths                                                                 | Conceptual/prototype-level; implementation status to be clarified                            |
| Daily missions              | Main daily action users are asked to complete                                                    | Core product concept; implementation status to be clarified with screenshots or app evidence |
| Tiny missions               | Smaller lower-effort alternatives for tired or overwhelmed users                                 | Core design feature; implementation status to be clarified                                   |
| Bonus missions              | Optional higher-intensity actions for high-momentum users                                        | Core design feature; implementation status to be clarified                                   |
| Mission intensity           | Tiny, normal, bonus, recovery, or low-pressure mission variants                                  | Framework-level design mechanism; implementation status to be clarified                      |
| “Make it smaller”           | Interaction for reducing mission difficulty                                                      | Framework-level/prototype feature; implementation status to be clarified                     |
| “I’m too tired”             | Explicit low-energy signal                                                                       | Framework-level/prototype feature; implementation status to be clarified                     |
| “Remind later”              | Timing-adjustment action for postponing a mission                                                | Framework-level/prototype feature; implementation status to be clarified                     |
| Skip                        | User action for declining a mission                                                              | Framework-level/prototype feature; implementation status to be clarified                     |
| Ringo companion             | Cat companion that guides, responds, and gives feedback                                          | Core product identity; exact implementation status to be clarified                           |
| Ringo moods                 | Visual/emotional states such as encouraging, proud, sad, sleeping, victory, or achievement       | Design feature; implementation status to be clarified                                        |
| Adaptive messages           | Ringo messages based on completion, skipping, tiredness, inactivity, or momentum                 | Behavior-aware/rule-based design direction; implementation status to be clarified            |
| XP and rewards              | Feedback after completion                                                                        | Product design feature; implementation status to be clarified                                |
| Step-by-step reward moment  | Gradual display of completion, XP, progress, streak, achievement, and Ringo reaction             | Design feature; implementation status to be clarified                                        |
| Streaks                     | Continuity feedback across repeated days or sessions                                             | Product design feature; implementation status to be clarified                                |
| Reminders and notifications | Prompts to return, complete, or re-engage                                                        | Planned/prototype-level; implementation status to be clarified                               |
| Mission logs                | Behavior records for completion, skip, remind-later, tiny mission use, bonus use, and inactivity | Required for future evaluation; implementation status to be clarified                        |
| Onboarding and guided flow  | Ringo-guided introduction and next-action guidance                                               | Design requirement; implementation status to be clarified                                    |

Before a final paper version is published, this table should be updated using direct product evidence: screenshots, user flows, code references, screen recordings, data model notes, and actual examples of missions, reminders, Ringo messages, and reward moments.

### 6.3 Example Prototype Flow

A representative prototype flow may work as follows:

1. The user enters RingoStrike and is guided by Ringo.
2. The user selects or receives a path and challenge.
3. Ringo presents one focused daily mission.
4. The user can complete the mission, make it smaller, say “I’m too tired,” select “Remind later,” or skip.
5. If the user completes the mission, RingoStrike presents feedback through a reward sequence.
6. If the user cannot complete the mission, the system may offer a tiny mission, recovery mission, delayed reminder, or preference check.
7. The system logs the interaction as a behavior signal for future adaptation and evaluation.

This flow demonstrates how the framework can be translated into a user experience. It does not demonstrate that the framework improves engagement or habit formation.

### 6.4 Adaptive Mission Examples

A normal mission might ask the user to complete a small daily action, such as a short exercise, writing task, learning task, reflection, or creative action. If the user taps “Make it smaller,” the system may reduce the mission to a minimal version. If the user taps “I’m too tired,” the system may offer a tiny or recovery mission. If the user completes missions repeatedly, the system may offer an optional bonus mission.

The important design principle is that the system should respond to the user’s behavior without making the user feel judged. The adaptation should feel like support, not surveillance. For example, a skipped mission should not trigger a shame-based message. A return after inactivity should not begin with blame. A streak-risk reminder should not imply that the user has failed.

### 6.5 Ringo’s Role in the Prototype

Ringo functions as a companion interface rather than a clinical or therapeutic agent. In the prototype case study, Ringo has four main roles:

1. **Guidance:** helping the user understand what to do next.
2. **Emotional tone:** making feedback feel warmer and less mechanical.
3. **Adaptive response:** responding differently to completion, skipping, tiredness, inactivity, and momentum.
4. **Re-engagement:** delivering reminders or recovery messages in a supportive tone.

This role should be described carefully. The paper may say that Ringo is designed to feel supportive. It should not say that Ringo has been proven to increase motivation, retention, emotional wellbeing, or habit formation.

### 6.6 Evidence Boundary for the Case Study

The prototype/case study section should remain descriptive and transparent. It can show how RingoStrike applies the framework, but it cannot make claims about outcomes. At this stage, the case study can support statements such as:

> “The prototype demonstrates how behavior-aware mission adaptation can be represented in product interactions.”

It should not support statements such as:

> “The prototype demonstrates that adaptive missions improve user behavior.”

The next step is formative user research. Without user data, the prototype remains an evidence-informed design case, not an evaluated intervention.

---

## 7. Proposed Formative User Study

The proposed first study is a formative UX/product research study. Its purpose is to evaluate early user experience, not to prove behavior change. The study should examine whether RingoStrike is clear, usable, emotionally safe, and understandable enough to justify further development and later evaluation.

The study should not be framed as a clinical study, randomized controlled trial, or effectiveness study. It should not claim that RingoStrike improves wellbeing, productivity, discipline, mental health, or long-term habit formation.

### 7.1 Study Purpose

The purpose of the study is to understand how early users experience RingoStrike’s companion-led micro-mission system. The study should focus on:

* clarity
* usability
* perceived emotional support
* perceived friction
* tiny mission usefulness
* guided flow
* Ringo companion experience
* reminders
* rewards
* pressure and guilt risks
* user understanding of what to do next

The most important goal is to identify what should be simplified, clarified, removed, rewritten, or redesigned before the product is evaluated more seriously.

### 7.2 What the Study Can and Cannot Prove

The study can evaluate whether users understand the app, complete core tasks, interpret Ringo’s role, understand tiny missions, react positively or negatively to reminders, and experience rewards as clear or excessive. It can also identify whether users feel judged, pressured, guilty, or manipulated.

The study cannot prove that RingoStrike forms habits. It cannot prove that tiny missions improve retention, that Ringo increases motivation, that reminders are more effective than neutral reminders, or that adaptive missions outperform static missions. Behavioral metrics from a short study should be interpreted as early engagement and usability indicators, not long-term behavior-change evidence.

### 7.3 Version A: 5–8 Participant Usability Test

Version A is the recommended first study if the product is still changing quickly. It should involve 5–8 participants in a moderated usability test, either remote or in person. Each session may last approximately 45–60 minutes and include consent, first impression, task-based usability testing, a short survey, and a short interview.

Version A should focus on first-session clarity and interaction quality. The moderator should avoid explaining the app too early. Participants should be allowed to explore the interface, think aloud, and reveal where they hesitate, misunderstand, or feel uncertain.

Key tasks should include:

1. Open RingoStrike and explain what the app seems to be for.
2. Explain what Ringo does.
3. Understand the relationship between paths, challenges, and missions.
4. Find today’s mission.
5. Complete a normal mission.
6. Use “Make it smaller.”
7. Use “I’m too tired.”
8. Use “Remind later.”
9. Skip a mission.
10. React to rewards, XP, streaks, and the reward sequence.
11. React to example reminder messages.

The main data from Version A should include task success, confusion points, time to find the main mission, misclicks, help needed, user comments, survey ratings, and interview feedback.

Version A is successful if it reveals the biggest usability and emotional-risk problems. Failure signals are also useful. If users cannot explain the app, cannot find today’s mission, misunderstand tiny missions, feel judged by Ringo, or find the reward sequence confusing, those findings should guide product improvements before a longer pilot.

### 7.4 Version B: 10–20 User, 7–14 Day Formative Pilot

Version B should be conducted only after the core flow is stable enough for daily use. It should involve 10–20 users using RingoStrike naturally for 7–14 days. This version is stronger than a one-session usability test because it can show repeated-use patterns, reminder reactions, tiny mission use, skip behavior, and short-term return behavior.

However, Version B still cannot prove long-term habit formation. A 7–14 day pilot is too short for strong habit claims, and without a control group or validated habit-strength measures, it should remain a formative pilot.

Participants should be instructed to use the app honestly:

> “You do not need to complete every mission. If you feel tired, confused, annoyed, or unmotivated, use the app naturally. Skipping, postponing, or choosing a tiny mission is useful feedback for this study.”

This instruction matters because forced compliance would produce misleading data.

Version B should collect:

* onboarding completion
* first mission completion
* daily mission completion
* tiny mission selection
* tiny mission completion
* bonus mission selection
* bonus mission completion
* “Make it smaller” usage
* “I’m too tired” usage
* skip rate
* remind-later use
* reminder sent/opened/clicked
* reward sequence started/completed/exited
* return rate
* inactive days
* drop-off points
* short daily feedback
* exit survey responses
* follow-up interview data

These metrics should be interpreted as early engagement and usability indicators. For example, a high skip rate may indicate mission difficulty, unclear wording, poor timing, low relevance, reminder fatigue, technical problems, or user disinterest. It should not be interpreted as laziness or lack of discipline.

### 7.5 Behavioral Metrics

The study should use behavioral metrics carefully. Useful metrics include:

| Metric                        | What it can suggest                                          | What it cannot prove                     |
| ----------------------------- | ------------------------------------------------------------ | ---------------------------------------- |
| Onboarding completion rate    | Whether onboarding is too hard or too long                   | Long-term engagement                     |
| Time to first mission         | Initial clarity and friction                                 | Motivation or habit strength             |
| First mission completion rate | First-session usability                                      | Habit formation                          |
| Daily mission completion rate | Short-term engagement                                        | Long-term behavior change                |
| Tiny mission selection rate   | Whether users use low-friction alternatives                  | That tiny missions improve habits        |
| Tiny mission completion rate  | Whether tiny missions feel doable                            | That tiny missions improve retention     |
| “Make it smaller” usage       | Whether users need lower difficulty                          | That adaptation works                    |
| “I’m too tired” usage         | Whether users use explicit low-energy input                  | Actual emotional state accuracy          |
| Skip rate                     | Possible friction, lack of interest, poor fit, or bad timing | Failure or lack of discipline            |
| Remind-later rate             | Whether postponement is useful                               | Future completion                        |
| Reminder response rate        | Basic reminder interaction                                   | That reminders feel caring               |
| Reward sequence completion    | Whether reward flow is tolerable                             | Reward effectiveness                     |
| Return rate                   | Short-term engagement                                        | Habit formation                          |
| Drop-off point                | Where friction may occur                                     | Cause of drop-off without interview data |

Behavioral logs should be combined with surveys and interviews. Logs can show what happened, but they cannot fully explain why it happened.

### 7.6 Survey and Interview Areas

The survey should use short rating scales and open-ended questions. Key survey areas should include:

* clarity of the app’s purpose
* clarity of Ringo’s role
* understanding of paths, challenges, and missions
* ease of finding today’s mission
* ease of completing a mission
* perceived usefulness of tiny missions
* clarity of “Make it smaller”
* safety of “I’m too tired”
* perceived support from Ringo
* annoyance or childishness of Ringo
* reminder helpfulness
* reminder intrusiveness
* reward clarity
* reward satisfaction
* streak motivation
* streak pressure or guilt
* perceived autonomy
* willingness to use again
* perceived complexity

Interview questions should explore what users understood, what confused them, how they interpreted Ringo, whether tiny missions felt meaningful, whether reminders felt helpful or intrusive, whether rewards became too much, and whether any part of the app created guilt or pressure.

Important interview questions include:

* In your own words, what is RingoStrike?
* What did Ringo add to the experience?
* Did you know what to do next?
* What did you think tiny missions were for?
* Did “Make it smaller” feel useful?
* Did “I’m too tired” feel safe, awkward, or unnecessary?
* Did any message make you feel judged?
* Would reminders from Ringo feel helpful or annoying?
* Did streaks motivate you or create pressure?
* What should happen when a user misses a day?
* What should Ringo never say to a user?
* What should be simplified first?

### 7.7 Ethical Considerations

The study should include clear ethical boundaries. Participants should understand that RingoStrike is an early habit-building prototype, not a therapy app, medical tool, or mental health intervention. The study should not recruit users who expect clinical support or are in acute emotional crisis.

Participants should be told what data is collected, why it is collected, who can access it, how it will be stored, and whether it will be anonymized. The study should collect only necessary data. It should avoid collecting medical, mental health, or unnecessary personal identity data. Participants should be able to leave the study and request deletion of their data where possible.

The study should specifically evaluate pressure and guilt because RingoStrike uses persuasive features such as reminders, rewards, streaks, and an emotionally expressive companion. These features may support engagement, but they may also create emotional pressure. The study should ask whether users feel judged, guilty, manipulated, or responsible for Ringo’s emotional state.

If RingoStrike uses rule-based adaptation, the study materials should say so clearly. The product should not imply that Ringo deeply understands the user’s emotional state. A safe description would be:

> “RingoStrike uses selected behavior signals to adjust mission suggestions and messages.”

An unsafe description would be:

> “Ringo understands how you feel.”

### 7.8 How Findings Would Be Used in the Paper

Findings from the proposed study would be used to refine the case study and evaluate the framework at an early product level. Version A findings could support claims about usability problems, clarity issues, emotional reactions, and design improvements. Version B findings could provide early evidence about short-term engagement patterns, tiny mission use, remind-later behavior, reminder response, reward experience, and drop-off points.

The paper should use findings cautiously. For example, after Version B, it may be appropriate to say:

> “Early users used tiny missions during low-energy or high-friction moments.”

or:

> “Some participants perceived Ringo as supportive, while others found the companion unnecessary or potentially childish.”

It would not be appropriate to say:

> “Tiny missions improved habit formation.”

or:

> “Ringo increased long-term motivation.”

The strongest realistic use of the study is to evaluate whether the Behavior-Aware Micro-Mission Framework is understandable, usable, emotionally safe, and promising enough for further testing. The study can help identify which parts of RingoStrike should be simplified, which messages should be rewritten, which reminders should be softened, which reward elements should be shortened, and which behavior signals are too ambiguous to drive adaptation alone.

In this way, the proposed study supports the paper’s current scope: an evidence-informed design framework and early product case study. It does not turn RingoStrike into a validated behavior-change intervention.
