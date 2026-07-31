User Story 5: Delete Question
User Story

As an Administrator

I want to remove obsolete questions

So that outdated content is no longer available.

Acceptance Criteria
Feature: Delete Question

Scenario: Delete Question
Given an unused question
When Delete is confirmed
Then the question is removed

Scenario: Question Used in Active Assessment
Given the question belongs to a published assessment
When Delete is attempted
Then deletion is prevented
And an explanatory message is displayed
