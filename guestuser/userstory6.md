User Story 6: Evaluate Guest Assessment
Title

Evaluate Guest Assessment Responses

User Story

As the HireFast system

I want to evaluate submitted assessments

So that Job Readiness Score and AI reports are prepared.

Acceptance Criteria
Feature: Assessment Evaluation

Scenario: Backend Evaluation
Given the assessment is submitted
When evaluation begins
Then quantitative questions are evaluated by backend logic

Scenario: AI Evaluation
Given qualitative questions exist
When backend evaluation completes
Then AI evaluates qualitative responses

Scenario: Generate Results
When both evaluations complete
Then Job Readiness Score is generated
And AI Summary is generated
