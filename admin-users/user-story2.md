User Story 2: View Dashboard
User Story

As an Administrator

I want to view platform metrics

So that I can monitor overall system activity.

Acceptance Criteria
Feature: Admin Dashboard

Scenario: Dashboard Load
Given the administrator is logged in
When Dashboard loads
Then display:
And Total Candidates
And Active Assessments
And Completed Assessments
And Recent Candidates
And Pending Reviews

Scenario: No Data
Given no platform activity exists
When Dashboard loads
Then empty states are displayed
