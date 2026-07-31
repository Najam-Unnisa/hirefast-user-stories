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
