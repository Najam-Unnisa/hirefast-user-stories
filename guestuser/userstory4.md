User Story 4: Save Assessment Progress
Title

Auto-save Guest Assessment Responses

User Story

As a Guest User

I want my responses to be auto-saved

So that I do not lose my progress.

Acceptance Criteria
Feature: Assessment Auto Save

Scenario: Auto Save
Given the Guest is answering questions
When a response is entered
Then the response is automatically saved

Scenario: Resume Assessment
Given the Guest exits before submission
When they log in again
Then the previously saved responses are restored
