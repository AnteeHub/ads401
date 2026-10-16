---
name: hci-academic-slides
description: >
  Create clean, academic HCI coursework presentation slides
  from Markdown research scripts. Follow a consistent
  seven-region slide layout, preserve research methodology,
  and validate content and visual quality.
---

# HCI Academic Slides Skill

## 1. Purpose

Generate professional, minimal, and readable academic
presentation slides for Human–Computer Interaction (HCI)
coursework.

The slides should resemble a university lecture presentation:
- White background
- Strong typographic hierarchy
- Dark navy/teal text
- Thin grey horizontal dividers
- Generous whitespace
- Clearly structured content
- Small source references and page numbers

The reference images define the visual hierarchy,
not the exact slide content.

## 2. Input

Primary input:
- A Markdown file containing the presentation outline,
  research questions, methodology, sampling, evaluation
  materials, and expected outcomes.

Optional inputs:
- Reference slide screenshots
- Research papers
- Course assessment criteria
- Presentation duration
- Required slide count

The Markdown file is the source of truth.

Do not silently modify:
- Research questions
- Target population
- Research methodology
- Sample sizes
- Study status
- Research findings

Flag inconsistencies instead.

## 3. Output

Default deliverables:

1. Editable PowerPoint (.pptx)
2. PDF preview, when requested
3. Slide-by-slide content summary
4. Validation report

Default language:
- English for visible slide content
- Chinese translations may be included in speaker notes
  when requested.

Never overcrowd slides to preserve bilingual text.

## 4. Slide Canvas

Aspect ratio: 16:9
Recommended size: 13.333 × 7.5 inches

Background:
- White (#FFFFFF)

Color palette:
- Primary text: #172327
- Academic teal: #183F46
- Secondary text: #687780
- Divider: #CED5D7
- Accent: #1683A5

Typography:
- Aptos, Arial, or another widely available sans-serif
- Consistent font family across the presentation
- Avoid decorative fonts

## 5. Seven-Region Layout

Each slide follows the same visual structure.

### Region 1: Section Label

Position:
- Top-left
- Approximately x=0.55, y=0.28 inches

Style:
- 10–12 pt
- Bold
- Uppercase
- Academic teal

Examples:
RESEARCH BACKGROUND
RESEARCH QUESTIONS
RESEARCH METHODOLOGY
EVALUATION DESIGN
EXPECTED OUTCOMES

### Region 2: Slide Title

Position:
- Below section label
- Approximately x=0.55, y=0.72 inches

Style:
- 28–34 pt
- Bold
- Primary text color
- Left aligned

Rules:
- Prefer a meaningful, declarative title
- Maximum two lines
- Avoid generic titles such as "Introduction"
  when a more informative title is possible

Example:
"Understanding the Adoption of XJTLU AI"

### Top Divider

Place a thin grey horizontal line below the title.

Suggested position:
y=1.48 inches

### Region 3: Content Headings

Position:
- Above each main content area

Style:
- 11–14 pt
- Uppercase when appropriate
- Secondary text color

Examples:
QUESTIONNAIRE
SEMI-STRUCTURED INTERVIEWS
AWARENESS & ADOPTION
PERCEIVED BENEFITS & BARRIERS

### Region 4: Main Content

Preferred layout:
- Two-column comparison
- Three-stage research process
- Research-question cards
- Data visualization
- Diagram or structured text

Guidelines:
- Use editable text and shapes whenever possible
- Prefer diagrams over paragraphs
- Use concise phrases
- Preserve necessary methodological details
- Do not add decorative illustrations without purpose

Content area:
Approximately y=2.2 to 5.6 inches

For two-column slides:
- Equal column widths
- Consistent alignment
- Clear visual separation
- Balanced content density

Do not reproduce black placeholder rectangles
from the reference images.

### Region 5: Key Takeaway

Position:
- Near the bottom
- Approximately y=6.05 inches

Style:
- 18–22 pt
- Bold
- Academic teal
- One sentence, preferably under 18 words

Purpose:
Communicate the main conclusion or question of the slide.

Examples:
"Why do some ADS401 students adopt XJTLU AI while others do not?"

"Survey patterns guide the follow-up interviews."

Do not invent findings.

### Bottom Divider

Place a thin grey line below the key takeaway.

Suggested position:
y=6.88 inches

### Region 6: References

Position:
- Bottom-left
- Approximately x=0.55, y=7.05 inches

Style:
- 8–9 pt
- Secondary text color

Rules:
- Cite external sources used on the slide
- Preserve DOI or stable source identifiers
- Do not invent citations
- Use "Source: Research proposal" for original
  study-design diagrams when useful
- Do not add irrelevant citations

### Region 7: Page Number

Position:
- Bottom-right
- Approximately x=12.3, y=7.05 inches

Style:
- 9 pt
- Secondary text color

Format:
01 / 05
02 / 05
03 / 05

Page numbering must be consistent.

## 6. Content Transformation Rules

Transform Markdown into presentation content.

Do not copy entire Markdown paragraphs onto slides.

For each slide:

1. Identify its primary communication objective.
2. Extract the essential research information.
3. Select the most suitable visual structure.
4. Write a concise slide title.
5. Create short content blocks.
6. Write one key takeaway.
7. Preserve relevant references.
8. Move supporting explanations to speaker notes.

Each slide should communicate one main idea.

Do not force every slide into two columns.

## 7. HCI Research Integrity

When generating slides for an HCI research proposal:

### Research Questions
- Preserve the original meaning of each RQ.
- Show clear relationships between RQs and methods.
- Do not introduce new RQs without approval.

### Methodology
- Distinguish questionnaires from interviews.
- Preserve the stated mixed-methods sequence.
- Do not describe planned data as collected data.
- Do not claim causal relationships from
  exploratory cross-sectional research.

### Sampling
- Distinguish the target population from
  the number of actual respondents.
- Distinguish recruitment targets from achieved samples.
- Preserve voluntary participation.
- Do not assume full participation.

### Evaluation Materials
- Show representative survey and interview questions.
- Mention participant information and consent.
- Do not claim materials are completed unless confirmed.

### Findings
- Never fabricate sample data.
- Distinguish expected outcomes from actual findings.
- Avoid unsupported claims of statistical significance.

### Limitations
- Preserve relevant methodological limitations.
- Do not generalize a single-module study to
  all university students.

## 8. Project-Specific Research Context

For the current ADS401 coursework:

Primary research subject:
XJTLU-provided AI services, including Junmou AI
where applicable.

Target population:
Students currently enrolled in ADS401 at XJTLU.

Research focus:
- Awareness
- Adoption
- Academic usage patterns
- Perceived benefits
- Perceived barriers
- Perceived differences from external AI tools

External AI tools:
ChatGPT, DeepSeek, and similar services are
secondary comparison contexts.

Do not transform this project into:
- An objective AI model benchmark
- A general survey of all university students
- A study primarily about ChatGPT
- A controlled usability experiment

Research methodology:
Explanatory Sequential Mixed-Methods Design

Sequence:
Cross-sectional Questionnaire
→ Preliminary Analysis
→ Semi-structured Interviews
→ Integrated Analysis

Preserve the source document's sample numbers,
but flag any ambiguity about recruitment targets.

## 9. Slide Selection Strategy

Choose layouts based on content.

Background:
- Two-column problem and motivation layout

Research Questions:
- Three aligned RQ blocks or cards

Methodology:
- Three-stage horizontal or vertical flow diagram

Sampling:
- Compact participant breakdown diagram

Evaluation Materials:
- Two-column questionnaire/interview comparison

Expected Outcomes:
- Three-part outcomes diagram

Limitations:
- Minimal text blocks

Use a consistent overall design system
while allowing different content arrangements.

## 10. Speaker Notes

When requested, provide speaker notes for every slide.

Rules:
- Natural spoken English
- Consistent with visible content
- No unsupported claims
- Avoid reading every bullet verbatim
- Fit the requested presentation duration

For bilingual notes:
- English paragraph first
- Chinese translation in a separate paragraph

Do not place long translations directly on slides
unless explicitly requested.

## 11. Visual Quality Requirements

All slide elements must:
- Stay within canvas bounds
- Avoid overlap
- Avoid clipped text
- Maintain readable font sizes
- Use consistent margins
- Maintain sufficient color contrast
- Align to a coherent grid

Minimum recommended body text:
16 pt

Small labels:
11–14 pt

References:
8–9 pt

Do not reduce essential body text below 14 pt
to force excessive content onto a slide.

If content does not fit:
1. Shorten wording without changing meaning.
2. Simplify the visual structure.
3. Move supporting details to speaker notes.
4. Split the slide if the slide limit permits.
5. Otherwise flag the conflict.

## 12. Validation

After generating the slides, perform two reviews.

### A. Content Validation

Check:
- Every RQ is represented.
- Target participants are correctly stated.
- Methods match the research design.
- Sampling figures are not misrepresented.
- Evaluation materials are included.
- Planned and completed work are distinguished.
- Citations are accurate.
- No findings are fabricated.

### B. Visual Validation

Check:
- 16:9 aspect ratio
- All seven layout regions
- Consistent title positioning
- Consistent dividers
- Readable text
- No overlap or clipping
- Balanced whitespace
- Correct page numbers
- Correct source references

Render every slide for visual inspection.

Do not claim visual validation was completed
unless the rendered slides were actually inspected.

## 13. Final Quality Report

Provide a concise report containing:

- Slide count
- Estimated presentation duration
- Content validation status
- Visual validation status
- Outstanding issues
- Any source ambiguities

Classify issues as:
- Critical
- Major
- Minor

Never silently resolve research ambiguities
by inventing information.