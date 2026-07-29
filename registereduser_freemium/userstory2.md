Feature 2: Dashboard
User Story 2: View Dashboard
User Story

As a Registered User

I want to access my dashboard

So that I can view my assessment progress and performance.

Acceptance Criteria
Feature: Dashboard

Scenario: Dashboard Load
Given the user is logged in
When the Dashboard opens
Then the system displays:
And Job Readiness Score
And AI Assessment Summary
And Assessment History
And Skill Scores
And Profile Completion Status
And Gamification Progress
And Recommended Next Steps

Scenario: No Assessments
Given the user has never completed an assessment
When the Dashboard loads
Then an empty state is displayed
And a prompt to start the General Communication Assessment is shown
