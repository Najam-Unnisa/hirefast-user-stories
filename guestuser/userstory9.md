User Story 9: Unlock Results After Registration
Title

Unlock Guest Assessment Results

User Story

As a Registered User

I want my completed assessment results to become available after registration

So that I can review my Job Readiness Score and AI feedback.

Acceptance Criteria
Feature: Unlock Results

Scenario: Successful Registration
Given the Guest completes profile registration
When registration is saved successfully
Then the user role changes to Registered
And previously generated Job Readiness Score becomes visible
And AI Assessment Summary becomes visible
And Dashboard access is granted

Scenario: Incomplete Registration
When mandatory profile fields are missing
Then registration cannot be completed
And results remain locked
