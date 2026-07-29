Feature 3: General Communication Assessment
User Story 3: Start General Assessment
User Story

As a Registered User

I want to take the General Communication Assessment

So that I can evaluate my employability skills.

Acceptance Criteria
Feature: General Communication Assessment

Scenario: Start Assessment
Given the user is on the Dashboard
When the user selects General Communication Assessment
Then the assessment starts successfully

Scenario: Resume Incomplete Assessment
Given an assessment was previously auto-saved
When the user opens the assessment
Then the latest saved progress is restored

User Story 4: Submit Assessment
User Story

As a Registered User

I want to submit my completed assessment

So that my Job Readiness Score can be updated.

Acceptance Criteria
Feature: Assessment Submission
Scenario: Successful Submission
Given all mandatory questions are answered
When the user submits the assessment
Then the assessment is submitted
And evaluation begins

Scenario: Mandatory Questions Missing
When mandatory questions are unanswered
Then submission is prevented
And unanswered questions are highlighted
