Feature 4: View Job Readiness Score
User Story 5: View Job Readiness Score
User Story

As a Registered User

I want to view my Job Readiness Score

So that I understand my current employability level.

Acceptance Criteria
Feature: Job Readiness Score

Scenario: Evaluation Complete
Given assessment evaluation is completed
When the user opens Results
Then the Job Readiness Score is displayed

Scenario: Evaluation Pending
Given evaluation is still processing
When the user opens Results
Then a processing status is displayed
