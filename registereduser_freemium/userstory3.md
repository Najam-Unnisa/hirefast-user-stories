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

