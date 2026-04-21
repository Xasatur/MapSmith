# PROJECT_GUIDELINES

## 1. Project Overview
- This repository is for building an AI-assisted DnD battle map generation workflow.
- It is a **prompt-engineering final project**.
- The main purpose is to improve the **consistency** and **usability** of AI-generated battle maps, not just generate random images.

## 2. Core Project Goal
- Build a prompt-driven system that solves a real problem for users.
- The system should create practical value for the user, not just show that one prompt is better than another.
- Reliability and consistency are central: outputs should be usable in repeated scenarios.

## 3. Instructor Clarification
- The project is **not only** about comparing a baseline prompt vs. an advanced prompt.
- The most important part is showing how the tool/system creates value.
- For this project, generated maps should be consistent and usable for gameplay.
- Success criteria must be specific, measurable, and easy to evaluate.

## 4. Target User
- The target user is a **Dungeon Master (DM)** preparing maps for tabletop sessions.
- The user needs maps quickly and with less trial-and-error.
- The system should reduce time spent iterating on unclear or unusable outputs.

## 5. Project Use Case
- AI map generation often takes many iterations before a usable result appears.
- Common problems include:
  - wrong perspective
  - missing required elements
  - cluttered layout
  - poor gameplay usability
  - inconsistent visual style
- This project aims to reduce these problems through structured prompting and clear evaluation.

## 6. Success Criteria
A generated map is considered successful if it passes **at least 4 out of 5** criteria.

Each criterion is evaluated as **pass/fail**:
- **Top-down perspective**: no side view or isometric angle.
- **Required elements present**: all requested scene objects are visible.
- **Layout clarity**: areas are distinguishable, paths are readable, and there is no confusing overlap.
- **Playability**: the map can realistically support movement and combat.
- **Visual consistency**: style is cohesive and no random immersion-breaking objects appear.

## 7. Overall Success Requirement
- The system will be tested on **10 unique test cases**.
- The full project is successful if **at least 8 out of 10** test cases pass.

## 8. Test Cases
1. Forest ritual site
2. Dungeon room
3. Cave system
4. Village square
5. Boss arena
6. Ship deck
7. Ruined temple
8. Feywild clearing
9. Desert ruins
10. Castle hall

## 9. Workflow
- Start from a reusable prompt template.
- Insert a test case.
- Generate the final prompt.
- Generate or attach the output image.
- Evaluate the image against the 5 criteria.
- Save the result in a logbook.
- Refine the prompt based on issues observed.

## 10. Logbook Requirements
Each logbook entry should include:
- date
- test case
- goal of attempt
- prompt version
- exact prompt used
- output description
- score
- OK / Not OK
- issue observed
- next change and why

## 11. Deliverable Support
This repository should support later creation of:
- proposal
- testing logbook
- final report
- presentation

## 12. Design Principles for the Codebase
- Keep code simple and readable.
- Prefer clear structure over overengineering.
- Make outputs easy to paste into Notion or the final report.
- Keep the project easy to extend later (for example with Streamlit).
