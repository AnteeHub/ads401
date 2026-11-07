# Questionnaire v2 — English (Tally Live Deployment)

> **Tally Live Deployment Source (2026-10-30)**: form `xVXO6r`.
> **Architecture**: 9-Page Streamlined Flow / 27 Questions with conditional branching & presence-linked matrices.
> *Note: This document reflects the live survey instrument deployed on Tally. For changes, update the form in Tally and re-sync this file.*

## Page 1: Information & Voluntary Consent

This is a voluntary ADS401 coursework survey exploring students' awareness, adoption, and use of XJTLU AI.

**"XJTLU AI"** refers to any student-accessible AI agent service officially provided by XJTLU, including but not limited to Junmou AI and the XJTLU Library AI Portal.

**"External AI"** refers to any AI agent service not officially provided by XJTLU, including but not limited to ChatGPT, DeepSeek, and similar services accessed independently.

**ADS401 Evaluation Methods and Statistics** is an XJTLU module for all enrolled students across core and elective programmes. It teaches you to evaluate computer systems through experiments, surveys, interviews, and data analysis, and to communicate your findings using evidence.

Unless otherwise specified, answer about **ADS401 learning in the past four weeks (28 days)**.

Participation is voluntary. This survey does not ask for identity or contact details unless you choose Yes to the optional follow-up interview invitation; if you choose Yes, the final question asks for a preferred name or pseudonym and a phone number or email address so the research team can match your answers to a potential interview invitation; your responses will therefore not be anonymous to the research team. Such information will be used only for interview recruitment and scheduling, accessed only by authorised study-team members, excluded from all reports and analysis datasets, and deleted within 30 days after all follow-up interviews are completed. You may decline an interview invitation later. Do not provide other sensitive information. Estimated completion time: 5–7 minutes.

**Participant Information Sheet:** Before deciding whether to participate, please review the complete study details, ethics clearance, and data management procedures in our official [Participant Information Sheet (PDF)](https://github.com/LionChenA/ads401/blob/main/assets/pre2/materials/survey/ADS401.Ethics.ParticipantInformationSheet.pdf).

**Ethical Approval:** This study has received formal ethical clearance from the XJTLU University Research Ethics Review Panel (Approval Ref: **ER-LRR-11000011420261012163300**). If you have any ethical concerns or questions, you may contact the University Ethics Committee at ethics@xjtlu.edu.cn.

### 1. Have you read the information above and do you voluntarily agree to participate?

- Yes, I agree
- No, I do not agree (survey ends)

- **Branching / Logic:** if 「1. Have you read the information above a」 IS ['No, I do not agree (survey ends)'] → JUMP(第1页)

## Page 2: Eligibility & Background

### 2. Which programme or pathway are you in?

- MSc Human-Computer Interaction — Human-centric Computing Pathway
- MSc Human-Computer Interaction — Human-AI Collaborative Computing Pathway
- MSc Social Computing — Full-Time
- MSc Social Computing — Part-Time
- Other _(inline text field)_

### 3. What was your primary field of study before your current programme?

- Computer Science & Information Technology
- Engineering & Technology
- Design, Arts & Media
- Social Sciences & Psychology
- Business, Management & Economics
- Humanities & Languages
- Natural Sciences & Mathematics
- Health & Life Sciences
- Education
- Other _(inline text field)_
- Prefer not to say

### 4. What is your gender?

- Woman
- Man
- Prefer not to say

### 5. What is your age?

- 20 or younger
- 21–24
- 25–29
- 30 or older
- Prefer not to say

### 6. How many years of experience do you have with AI platforms (e.g., Doubao, ChatGPT, Gemini)?

- No experience
- Less than 1 year
- 1–2 years
- 2–3 years
- More than 3 years

## Page 3: Awareness & Usage Category (Branching Hub)

### 7. So far, how familiar are you with XJTLU AI?

- Heard of them and knew some functions
- Heard of them but knew little
- Had not heard of them
- Unsure whether known services were XJTLU-provided

- **Branching / Logic:** if 「7. So far, how familiar are you with XJT」 IS ['Had not heard of them'] → HIDE: ff050a27, Both XJTLU AI and External AI, XJTLU AI only (no External AI)

### 8. Have you ever used XJTLU AI?

- Yes
- No
- Not sure

- **Branching / Logic:** if 「8. Have you ever used XJTLU AI?」 IS ['No'] → HIDE: Both XJTLU AI and External AI, XJTLU AI only (no External AI)

### 9. During the past four weeks, which statement best describes your use of AI for ADS401 learning activities? (Select one.)

- Both XJTLU AI and External AI
- XJTLU AI only (no External AI)
- External AI only (no XJTLU AI)
- Neither XJTLU AI nor External AI

- **Branching / Logic:** if 「9. During the past four weeks, which sta」 IS ['External AI only (no XJTLU AI)'] → JUMP(跳至指定页)
- **Branching / Logic:** if 「9. During the past four weeks, which sta」 IS ['Neither XJTLU AI nor External AI'] → JUMP(跳至指定页)
- **Branching / Logic:** if 「9. During the past four weeks, which sta」 IS ['Both XJTLU AI and External AI'] → JUMP(跳至指定页)
- **Branching / Logic:** if 「9. During the past four weeks, which sta」 IS ['XJTLU AI only (no External AI)'] → JUMP(跳至指定页)
- **Branching / Logic:** if 「9. During the past four weeks, which sta」 IS ['Neither XJTLU AI nor External AI'] → JUMP(跳至指定页)
- **Branching / Logic:** if 「9. During the past four weeks, which sta」 IS ['External AI only (no XJTLU AI)'] → JUMP(跳至指定页)

## Page 4: XJTLU AI Usage & Experience

### 10. How many times did you use XJTLU AI for ADS401 learning during the past four weeks?

- 1–4 times in total (at most once a week on average)
- 5–8 times in total (about 1–2 times a week on average)
- 9–12 times in total (about 2–3 times a week on average)
- More than 12 times in total (more than 3 times a week on average)
- Can't recall

### 11. For which broad categories of ADS401 learning activities did you use XJTLU AI in the past four weeks? (Select all that apply.)

- Finding and using campus resources (e.g., finding an empirical HCI paper for Pre1 via XJTLU Library / Research Portal, module materials on Learning Mall)
- Learning within-course content (understanding concepts, finding past exams)
- Support beyond-course content (e.g., survey tools, scales, research-method references)
- Understanding ADS401 policies (why learn ADS401, what's taught, grading criteria, tutor information)
- Coursework production (survey design, literature search, slides)
- Other activity (please specify) _(inline text field)_

- **Branching / Logic:** if 「11. For which broad categories of ADS401」 DOES_NOT_CONTAIN ['Finding and using campus resources (e.g., finding an empirical HCI paper for Pre1 via XJTLU Library / Research Portal, module materials on Learning Mall)'] → HIDE: Finding and using campus resources
- **Branching / Logic:** if 「11. For which broad categories of ADS401」 DOES_NOT_CONTAIN ['Learning within-course content (understanding concepts, finding past exams)'] → HIDE: Learning within-course content
- **Branching / Logic:** if 「11. For which broad categories of ADS401」 DOES_NOT_CONTAIN ['Support beyond-course content (e.g., survey tools, scales, research-method references)'] → HIDE: Support beyond-course content
- **Branching / Logic:** if 「11. For which broad categories of ADS401」 DOES_NOT_CONTAIN ["Understanding ADS401 policies (why learn ADS401, what's taught, grading criteria, tutor information)"] → HIDE: Understanding ADS401 policies
- **Branching / Logic:** if 「11. For which broad categories of ADS401」 DOES_NOT_CONTAIN ['Coursework production (survey design, literature search, slides)'] → HIDE: Coursework production
- **Branching / Logic:** if 「11. For which broad categories of ADS401」 DOES_NOT_CONTAIN ['Other activity (please specify)'] → HIDE: Other activity

### 12. For each activity category, rate how useful XJTLU AI was in your actual experience. Select N/A for categories you did not use it for.

**Rating Columns:**  | Not useful | Slightly useful | Moderately useful | Useful | Very useful
**Rows (presence-linked to previous selection):** Finding and using campus resources | Learning within-course content | Support beyond-course content | Understanding ADS401 policies | Coursework production | Other activity

### 13. In the past four weeks, when you used information from XJTLU AI for ADS401 work, how often did you check it against course materials or other reliable sources?

- Never
- Rarely (about 1–3 times in 10)
- Sometimes (about 4–6 times in 10)
- Often (about 7–9 times in 10)
- Every time
- Unable to judge

### 14. Based on your overall experience using XJTLU AI in ADS401, how much do you agree with these statements? (Select N/A if you cannot judge.)

**Rating Columns:**  | Strongly disagree | Disagree | Neutral | Agree | Strongly agree | N/A | XJTLU AI helps me complete ADS401 tasks more effectively | XJTLU AI helps me complete ADS401 tasks more efficiently | XJTLU AI is easy to learn how to use | XJTLU AI is easy to use for my ADS401 tasks | XJTLU AI usually provides information I consider reliable | I generally trust XJTLU AI's explanations

### 15. In the past four weeks, which problems did you experience when using XJTLU AI for ADS401 learning? (Select up to 3.)

- No notable problem (selecting this will hide other options) _(max 3)_
- Unclear which XJTLU AI to use _(max 3)_
- Hard to formulate prompts _(max 3)_
- Inaccurate, unclear or vague answers _(max 3)_
- Answers not relevant to ADS401 _(max 3)_
- Time-consuming to verify or revise _(max 3)_
- Inconvenient access/login/workflow _(max 3)_
- Functions insufficient _(max 3)_
- Uncertain about course permission _(max 3)_
- Privacy or data concerns _(max 3)_
- Other _(inline text field)_ _(max 3)_

- **Branching / Logic:** if 「15. In the past four weeks, which proble」 CONTAINS ['No notable problem (selecting this will hide other options)'] → HIDE: Unclear which XJTLU AI to use, Hard to formulate prompts, Inaccurate, unclear or vague answers, Answers not relevant to ADS401, Time-consuming to verify or revise, Inconvenient access/login/workflow, Functions insufficient, Uncertain about course permission, Privacy or data concerns, Other
- **Branching / Logic:** if 「15. In the past four weeks, which proble」 IS_ANY_OF ['Unclear which XJTLU AI to use', 'Hard to formulate prompts', 'Inaccurate, unclear or vague answers', 'Answers not relevant to ADS401', 'Time-consuming to verify or revise', 'Inconvenient access/login/workflow', 'Functions insufficient', 'Uncertain about course permission', 'Privacy or data concerns', 'Other'] → HIDE: No notable problem (selecting this will hide other options)

### 16. If you have a suitable ADS401 task in the next four weeks, how likely are you to continue using XJTLU AI?

- Very unlikely
- Unlikely
- Neutral
- Likely
- Very likely

## Page 5: Non-use Module (External-only & Neither)

### 17. What are your main reasons for NOT using XJTLU AI for ADS401 during the past four weeks? (Select up to 3.)

- Previously unaware _(max 3)_
- Unclear what it can do _(max 3)_
- Unsure how to access _(max 3)_
- No suitable ADS401 task _(max 3)_
- Prefer External AI _(max 3)_
- Prefer non-AI methods _(max 3)_
- Concerned about inaccurate answers _(max 3)_
- Unsure if AI use permitted _(max 3)_
- Privacy/data concerns _(max 3)_
- Past experience unsatisfactory _(max 3)_
- Access or operation seemed inconvenient _(max 3)_
- Other _(inline text field)_ _(max 3)_

### 18. If you have a suitable ADS401 task in the next four weeks, how willing are you to try or resume XJTLU AI?

- Very unwilling
- Unwilling
- Neutral
- Willing
- Very willing

## Page 6: External AI Usage & Experience

### 19. How many times did you use External AI for ADS401 learning during the past four weeks?

- 1–4 times in total (at most once a week on average)
- 5–8 times in total (about 1–2 times a week on average)
- 9–12 times in total (about 2–3 times a week on average)
- More than 12 times in total (more than 3 times a week on average)
- Can't recall

### 20. For which broad categories of ADS401 learning activities did you use External AI in the past four weeks? (Select all that apply.)

- Finding and using campus resources (e.g., finding an empirical HCI paper for Pre1 via XJTLU Library / Research Portal, module materials on Learning Mall)
- Learning within-course content (understanding concepts, finding past exams)
- Support beyond-course content (e.g., survey tools, scales, research-method references)
- Understanding ADS401 policies (why learn ADS401, what's taught, grading criteria, tutor information)
- Coursework production (survey design, literature search, slides)
- Other activity (please specify; if same as above, state 'Same as above') _(inline text field)_

- **Branching / Logic:** if 「20. For which broad categories of ADS401」 DOES_NOT_CONTAIN ['Finding and using campus resources (e.g., finding an empirical HCI paper for Pre1 via XJTLU Library / Research Portal, module materials on Learning Mall)'] → HIDE: Finding and using campus resources
- **Branching / Logic:** if 「20. For which broad categories of ADS401」 DOES_NOT_CONTAIN ['Learning within-course content (understanding concepts, finding past exams)'] → HIDE: Learning within-course content
- **Branching / Logic:** if 「20. For which broad categories of ADS401」 DOES_NOT_CONTAIN ['Support beyond-course content (e.g., survey tools, scales, research-method references)'] → HIDE: Support beyond-course content
- **Branching / Logic:** if 「20. For which broad categories of ADS401」 DOES_NOT_CONTAIN ["Understanding ADS401 policies (why learn ADS401, what's taught, grading criteria, tutor information)"] → HIDE: Understanding ADS401 policies
- **Branching / Logic:** if 「20. For which broad categories of ADS401」 DOES_NOT_CONTAIN ['Coursework production (survey design, literature search, slides)'] → HIDE: Coursework production
- **Branching / Logic:** if 「20. For which broad categories of ADS401」 DOES_NOT_CONTAIN ["Other activity (please specify; if same as above, state 'Same as above')"] → HIDE: Other activity

### 21. For each activity category, rate how useful External AI was in your actual experience. Select N/A for categories you did not use it for.

**Rating Columns:**  | Not useful | Slightly useful | Moderately useful | Useful | Very useful
**Rows (presence-linked to previous selection):** Finding and using campus resources | Learning within-course content | Support beyond-course content | Understanding ADS401 policies | Coursework production | Other activity

## Page 7: Tool Comparison (Both Users)

### 22. For each activity category where you used both XJTLU AI and External AI in the past four weeks, which worked better in your actual experience? (Choose 'Unable to compare' where appropriate.)

**Rating Columns:**  | XJTLU AI better | About the same | External AI better | Unable to compare | Finding and using campus resources | Learning within-course content | Support beyond-course content | Understanding ADS401 policies | Coursework production | Other activity (if both used) | Overall preference

## Page 8: Convergence, Evaluation & Interview Recruitment

### 23. Which factors matter most when choosing an AI tool for ADS401, or if you were to choose one? (Select up to 3.)

- Task relevance _(max 3)_
- Accuracy or reliability _(max 3)_
- Ease of use _(max 3)_
- Speed _(max 3)_
- Familiarity _(max 3)_
- Suitable features _(max 3)_
- Accessibility _(max 3)_
- Chinese-language support _(max 3)_
- Quota or cost _(max 3)_
- University recommendation _(max 3)_
- Other _(inline text field)_ _(max 3)_

### 24. In your opinion, which improvements should XJTLU AI prioritise for ADS401? (Select up to 3)

- More accurate course answers _(max 3)_
- Research-method support _(max 3)_
- Survey/interview design support _(max 3)_
- Document/knowledge-base support _(max 3)_
- Writing/summaries/planning _(max 3)_
- Clearer navigation _(max 3)_
- ADS401-specific examples _(max 3)_
- Privacy/data transparency _(max 3)_
- Clear course-use guidance _(max 3)_
- Other _(inline text field)_ _(max 3)_

### 25. Anything else you'd like to share about XJTLU AI or External AI for ADS401? (Optional; open text; no identifying information)

- [长文本 / (Optional)]

### 26. Would you be willing to be contacted for an optional follow-up interview? If Yes, the final question will ask for a preferred name or pseudonym and a phone number or email address.

- Yes
- No

- **Branching / Logic:** if 「26. Would you be willing to be contacted」 IS ['No'] → HIDE: 27. Please leave your contact information., • Preferred name or pseudonym:, 16d748d2, • Phone number or email:, e3c40c00; JUMP(第1页)

### 27. Please leave your contact information.

- **Preferred name or pseudonym:** [单行文本 / (Optional)]
- **Phone number or email:** [单行文本 / (Required)]

## Page 9: Completion

### Thank you for your participation!

Your responses have been submitted. If you chose to take part in the follow-up interview, we may contact you via the details you left.
