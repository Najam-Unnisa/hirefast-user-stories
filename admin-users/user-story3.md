Epic 2: Question Bank Management
User Story 3: Create Question
User Story

As an Administrator

I want to add assessment questions

So that candidates can answer them during assessments.

Acceptance Criteria
Feature: Create Question

Scenario: Create Question
Given the administrator opens Question Management
When valid question details are entered
Then the question is saved successfully

Scenario: Missing Mandatory Fields
When mandatory fields are blank
Then validation errors are displayed
And the question is not saved
