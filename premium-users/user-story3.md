User Story 3: Attempt Skill-Based Assessment
User Story

As a Premium User

I want to complete premium skill assessments

So that I can evaluate my expertise in specific domains.

Acceptance Criteria
Feature: Premium Skill Assessment

Scenario: Start Assessment
Given the user selects a Skill-Based Assessment
When the assessment starts
Then the assessment loads successfully

Scenario: Resume Assessment
Given an assessment was auto-saved
When the user returns
Then the saved progress is restored

Scenario: Submit Assessment
Given all mandatory questions are answered
When the user submits the assessment
Then evaluation begins
