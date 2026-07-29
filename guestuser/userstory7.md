User Story 7: Lock Guest Results
Title

Hide Assessment Results for Guest Users

User Story

As a Guest User

I want my assessment results to remain locked until profile completion

So that I am encouraged to complete my HireFast profile.

Acceptance Criteria
Feature: Locked Results

Scenario: Guest Completes Assessment
Given evaluation is complete
When the Guest attempts to view results
Then the Job Readiness Score is hidden
And the AI Summary is hidden
And a profile completion prompt is displayed

Scenario: Guest Opens Dashboard
Given the user is a Guest
When they attempt to access the dashboard
Then access is denied
And profile completion is required
