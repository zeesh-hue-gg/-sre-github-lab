# Student Task Tracker

## Overview
This application helps software engineering students track their coursework assignments, manage deadlines, and record completed tasks efficiently during the semester.

## Scope
In scope: Add a coursework task.
In scope: List recorded tasks.
In scope: Mark a task complete.
Out of scope: Fee payments.
Out of scope: Automatic grading.

## Stakeholders
Student: Records tasks and checks progress.
Instructor: Reviews project documentation and verifies requirements alignment.
Project maintainer: Maintains codebase quality and reviews proposed documentation changes.

## Functional requirements
FR-01: The system shall let a student create a task with a title.
FR-02: The system shall display the student's recorded tasks.
FR-03: The system shall let a student mark a task as complete.

## Nonfunctional requirements
- NFR-01: For 100 stored tasks, the task list shall appear within 2 seconds in at least 95 of 100 trials on the agreed test device.
- NFR-02: All task actions shall be operable using a keyboard alone, verified against each documented task workflow.

## Acceptance criteria
FR-01: Given the title "Read Chapter 1", saving a new task causes that title to appear in the task list.
FR-02: With two saved tasks, opening the list shows both titles.
FR-03: Marking an incomplete task complete changes its displayed status to Complete.

## Assumptions and open questions
Assumption A-01: Students access the application on standard laptop operating systems (Windows/macOS).
Question Q-01: Should task notifications be supported in future releases?
Question Q-02: Which device and environment will test NFR-01?

## Project status and viewing
Documentation only. Application implementation has not started.
Clone this repository and open README.md in a Markdown viewer, or read the rendered file on GitHub.

## Author
Mohammad Zeeshan Niaz Ahmad - BS Software Engineering

## Contributing
Create a documentation branch, edit and review the README, commit the change, push the branch, and open a pull request.