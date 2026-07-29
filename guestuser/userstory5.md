User Story 5: Submit Assessment
Title

Submit General Communication Assessment

User Story

As a Guest User

I want to submit my completed assessment

So that my performance can be evaluated.

Acceptance Criteria
Feature: Assessment Submission

Scenario: Successful Submission
Given all mandatory questions are completed
When the Guest clicks Submit
Then the assessment is submitted successfully
And no further edits are allowed
And evaluation begins

Scenario: Incomplete Assessment
Given mandatory questions remain unanswered
When the Guest attempts submission
Then the system highlights unanswered questions
And prevents submission
