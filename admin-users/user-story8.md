User Story 8: Publish Assessment
User Story

As an Administrator

I want to publish assessments

So that candidates can access them.

Acceptance Criteria
Feature: Publish Assessment

Scenario: Publish
Given the assessment passes validation
When Publish is clicked
Then assessment status changes to Published

Scenario: Missing Questions
Then publishing is prevented
