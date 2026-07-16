---
name: undergrad-thesis-workflow
description: Guide a student through a practical undergraduate thesis workflow from topic narrowing to questionnaire design, data cleaning, chart preparation, drafting, revision, plagiarism response, and AIGC-risk reduction. Use whenever the user is writing a Chinese undergraduate thesis, especially a survey-based paper, asks to initialize a thesis workspace, refine a topic with advisor constraints, build a questionnaire, clean questionnaire data, write results/discussion sections, prepare charts, or revise a draft after plagiarism or AIGC feedback.
---

# Undergraduate Thesis Workflow

Use this skill as a full workflow controller for a practical undergraduate thesis project.

This skill is especially suitable when:

1. the user is an undergraduate student
2. the advisor wants a concrete population and a feasible method
3. the thesis uses a questionnaire or small-scale survey
4. the user needs step-by-step help from topic selection through final revision

## Core Principles

Always keep these rules in place:

1. Narrow the topic to a concrete population.
2. Do not oversell causality from cross-sectional questionnaire data.
3. Treat advisor feedback as a hard constraint, not a suggestion.
4. Prefer feasible execution over broad but empty writing.
5. Keep all claims tied to either:
   - user-provided data
   - user-provided documents
   - clearly marked background literature

## Best-Fit Thesis Pattern

The default pattern this skill should prefer is:

- concrete population
- one or two measurable behavioral variables
- questionnaire data
- descriptive statistics plus simple group comparison / relatedness discussion

Typical example:

- population: students from one university
- variable: ultra-processed food intake
- outcome: overweight / obesity grouped by BMI
- method: questionnaire + data cleaning + charts + results + discussion

## Workflow Stages

Route the user through these stages.

### Stage 1: Workspace Setup

Use when the user is just starting.

Tasks:

1. create a clear project structure
2. create advisor-notes files
3. create thesis draft folders
4. create questionnaire and data-analysis placeholders

If the user already has files, preserve them and only add missing structure.

### Stage 2: Topic Narrowing

Use when the topic is still too broad.

Tasks:

1. identify the advisor's real constraints
2. narrow from broad mechanism/review topics to a concrete survey topic
3. lock:
   - population
   - core variable
   - feasible method

Good narrowing checklist:

- Does the topic specify a population?
- Does it avoid trying to explain all causes?
- Can the student collect data within the project timeline?

### Stage 3: Proposal Drafting

Use when the topic is approved but the student needs an opening report / proposal.

Deliver:

1. topic background
2. research purpose
3. literature status
4. research content
5. research method
6. feasibility
7. schedule

Keep proposal language conservative and practical.

### Stage 4: Questionnaire Design

Use when the user is ready to collect survey data.

Tasks:

1. define variables
2. define coding rules
3. define BMI and grouping rules
4. prepare a clean questionnaire version for online tools
5. prepare a coding table for later analysis

Questionnaire design rules:

1. keep the questionnaire short
2. make units explicit
3. avoid ambiguous options
4. prefer variables that can be directly analyzed later

### Stage 5: Data Cleaning

Use when the user has exported survey data.

Tasks:

1. inspect row count and columns
2. identify test rows, invalid rows, and obvious unit errors
3. document every cleaning decision
4. generate an analysis-ready table
5. compute derived fields such as:
   - BMI
   - BMI group
   - total score for the main behavior variable

Always create a written cleaning note that explains:

- raw count
- removed rows
- final valid sample size
- grouping rules

### Stage 6: Results Writing

Use when the cleaned data is ready.

Tasks:

1. extract the core sample statistics
2. prepare result tables
3. prepare chart-ready data
4. write result paragraphs conservatively

Result writing rules:

1. numbers must match the cleaned data
2. do not say "proved" when the design only supports correlation or association
3. present the descriptive pattern before interpretation

### Stage 7: Discussion and Conclusion

Use when the results are available.

Tasks:

1. explain the main observed patterns
2. compare cautiously with prior literature
3. discuss practical meaning for the specific population
4. state limitations clearly
5. keep the conclusion proportional to the evidence

Discussion rules:

1. avoid generic textbook wording
2. connect claims back to the user's population and actual results
3. acknowledge other factors such as exercise, sleep, schedule, stress when relevant

### Stage 8: Chart Preparation

Use whenever the advisor asks for more visual presentation.

Deliver:

1. chart-ready CSV or spreadsheet data
2. recommended chart type for each figure
3. figure titles and placement suggestions

Prefer charts that directly support the result section:

1. sample composition
2. BMI distribution
3. frequency distribution of the core behavior variable
4. group comparison charts

### Stage 9: Plagiarism and AIGC Revision

Use when the user has plagiarism or AIGC report feedback.

For plagiarism:

1. first inspect the total duplication level
2. only revise genuinely high-risk passages
3. avoid unnecessary global rewriting if the plagiarism rate is already low

For AIGC-risk reduction:

1. focus on high-risk sections such as:
   - abstract
   - background
   - literature review definitions
   - discussion
   - conclusion
   - outlook
2. reduce:
   - overly balanced sentence rhythm
   - repetitive template transitions
   - textbook-like definitions
   - generic recommendation blocks
3. keep:
   - data
   - logic
   - actual findings

## Advisor Constraint Handling

If the user says the advisor gave feedback, treat it as top priority.

Always save and refer back to a short advisor summary.

At minimum, preserve:

1. what the advisor rejected
2. what the advisor wants narrowed
3. what method the advisor accepts
4. what wording the advisor is sensitive to

If later writing drifts away from those constraints, route backward and fix the structure before continuing.

## Suggested Deliverables

Depending on stage, produce the smallest useful artifact first.

Examples:

1. folder structure
2. proposal draft
3. questionnaire text
4. coding table
5. cleaned CSV
6. result template
7. chart files
8. full thesis draft
9. final checklist

## Output Style

When writing for the student:

1. keep explanations concrete
2. prefer usable text over theory
3. highlight risk points kindly
4. suggest the next best step, not ten possible paths

## Common Failure Modes To Avoid

1. letting the topic stay too broad
2. confusing correlation with causation
3. writing a literature review that is detached from the actual questionnaire topic
4. ignoring advisor constraints after the topic changes
5. letting results, tables, and charts disagree
6. rewriting the whole paper for low plagiarism scores that are already acceptable
7. reducing AIGC risk by flattening the meaning or damaging accuracy

## Recommended Companion Files

If packaging a thesis project for reuse, the skill works best with:

1. an advisor summary file
2. a questionnaire template
3. a coding table template
4. a data-cleaning note template
5. a results table template
6. a final submission checklist

Read the bundled reference files when they exist.
