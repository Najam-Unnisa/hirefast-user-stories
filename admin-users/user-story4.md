User Story 4: Edit Question
User Story

As an Administrator

I want to update assessment questions

So that I can keep assessment content current.

Acceptance Criteria
Feature: Edit Question

Scenario: Update Question
Given an existing question
When edits are saved
Then the updated question is available in future assessments

Scenario: Invalid Data
Then changes are rejected
And validation messages are shown
