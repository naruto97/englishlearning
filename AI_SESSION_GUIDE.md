# AI Session Guide: English Learning Comprehensive Teaching System
## Multi-Session Vision Document

---

## PURPOSE OF THIS DOCUMENT

This document serves as the master guide for AI assistants working on this English learning project. It ensures continuity across multiple AI sessions and maintains consistent teaching quality.

---

## THE MISSION

Teach the user to write a **Distinguished-level (100/100) Argumentative Essay** by providing:

1. **Exhaustive explanations** of every rubric requirement
2. **Extensive examples** of CORRECT approaches (what to do)
3. **Extensive examples** of INCORRECT approaches (what NOT to do)
4. **Clear reasoning** explaining WHY something works or fails
5. **Progressive skill building** from basic to advanced

---

## CORE PRINCIPLES FOR ALL AI SESSIONS

### Principle 1: Rubric Alignment
Every piece of advice MUST trace back to a specific rubric requirement. Never give generic writing advice that isn't directly tied to earning points.

### Principle 2: Show, Don't Just Tell
For every rule, provide:
- At least 2-3 GOOD examples (marked with checkmark)
- At least 2-3 BAD examples (marked with X)
- Explanation of WHY each is good/bad

### Principle 3: Graduated Difficulty
Show examples at multiple skill levels:
- **Failing Level** (0-6 points): What to absolutely avoid
- **Basic Level** (6-9 points): Common student work
- **Proficient Level** (12 points): Good but not perfect
- **Distinguished Level** (15 points): Target quality

### Principle 4: Error Prevention
Anticipate common mistakes and explicitly warn against them BEFORE the user makes them.

### Principle 5: Actionable Checklists
Every section should end with a concrete checklist the user can apply.

---

## PROJECT FILE STRUCTURE

```
/englishlearning/
|
|-- rubric                          # Original grading rubric (DO NOT MODIFY)
|-- learning_guide                  # Core teaching guide (ENHANCE, DON'T REPLACE)
|-- AI_SESSION_GUIDE.md             # This file - session continuity guide
|
|-- /examples/                      # Extensive example library
|   |-- 01_introduction_examples.md
|   |-- 02_body_paragraphs_examples.md
|   |-- 03_organization_examples.md
|   |-- 04_citations_examples.md
|   |-- 05_conclusion_examples.md
|   |-- 06_works_cited_examples.md
|   |-- 07_mechanics_examples.md
|   |
|   |-- model_essay_annotated.md    # Complete essay with line-by-line annotations
|   |-- common_mistakes.md          # Compendium of errors to avoid
|
|-- /practice/                      # Practice exercises (future expansion)
|-- /templates/                     # Reusable templates (future expansion)
```

---

## RUBRIC POINT VALUES (REFERENCE)

| Category          | Points | Key Distinguished Requirements |
|-------------------|--------|--------------------------------|
| Introduction      | 15     | 4+ sentences, engaging hook, clear thesis, smooth transition |
| Body Paragraphs   | 15     | 3+ paragraphs, 4+ sentences each, one claim per paragraph, detailed examples, transitions |
| Organization      | 15     | Highly organized, logical flow, strong explicit transitions |
| In-Text Citations | 15     | Every claim cited, proper MLA format |
| Conclusion        | 15     | 4+ sentences, reinforces thesis, summarizes ALL points, no new details |
| Works Cited       | 15     | Correct formatting AND MLA citation (zero errors) |
| Mechanics         | 10     | Zero errors, varied sentence structures |
| **TOTAL**         | **100**|                                |

---

## SESSION TASK PROTOCOL

When an AI session begins work on this project:

### Step 1: Read Context Files
- Read `rubric` to understand grading criteria
- Read `learning_guide` for current teaching content
- Read this file (`AI_SESSION_GUIDE.md`) for project vision
- Read any existing `/examples/` files to avoid duplication

### Step 2: Identify Current State
- Check which example files exist
- Identify gaps in coverage
- Note any user-specific needs mentioned in conversation

### Step 3: Work Systematically
- Complete ONE section fully before moving to next
- Push after each completed section
- Update this guide if project structure changes

### Step 4: Maintain Quality Standards
- Every example must be realistic and usable
- Every explanation must cite the rubric
- Every "bad example" must explain what's wrong

---

## EXAMPLE FILE TEMPLATE

Each example file should follow this structure:

```markdown
# [Section Name] - Comprehensive Examples

## Rubric Requirements
[Copy exact rubric language]

## Point Breakdown
[Show what earns each point level]

## WHAT TO DO (Correct Examples)

### Distinguished Level Examples (15/15)
[Multiple full examples with annotations]

### Proficient Level Examples (12/15)
[Show what "almost there" looks like]

## WHAT NOT TO DO (Incorrect Examples)

### Common Mistake #1: [Name]
**Bad Example:**
[Show the mistake]

**Why It's Wrong:**
[Explain rubric violation]

**How to Fix It:**
[Show corrected version]

[Repeat for all common mistakes]

## Self-Check Questions
[Questions user can ask themselves to verify quality]

## Checklist
[Concrete checklist items]
```

---

## TOPIC CONTEXT

The user's essay topic is: **College vs. Trade School/Direct Workforce Entry**

**Position to argue:** College education is the best path for most high school graduates.

**Key arguments available:**
1. Higher lifetime earnings
2. Greater career flexibility
3. Lower unemployment rates
4. Adaptable skills for changing economy
5. Counterargument: Trade school benefits are real but limited long-term

**User's unique advantage:** Has trade experience, can write with authenticity about both paths.

---

## QUALITY GATES

Before any session considers work complete, verify:

- [ ] All examples are essay-topic-relevant (college vs. trades)
- [ ] Each rubric point level is illustrated with examples
- [ ] "What NOT to do" examples are clearly marked and explained
- [ ] Explanations connect back to specific rubric language
- [ ] File is properly formatted and readable
- [ ] Changes are committed with descriptive messages
- [ ] Changes are pushed to the correct branch

---

## BRANCH INFORMATION

**Working Branch:** `claude/comprehensive-audit-examples-MOz6z`

All work should be committed and pushed to this branch.

---

## COMPLETION CRITERIA

The project is complete when:

1. All 7 example files exist with comprehensive content
2. Model essay is fully annotated
3. Common mistakes compendium is thorough
4. Every rubric requirement has multiple DO/DON'T examples
5. User can use these materials to self-assess and improve
6. All files are internally consistent and cross-referenced

---

## SESSION HANDOFF NOTES

*This section should be updated by each AI session to communicate with future sessions:*

### Session 1 (Current)
- Created this vision document
- Beginning systematic creation of example files
- Starting with Section 1: Introduction Examples

---

*Last Updated: 2025-12-29*
