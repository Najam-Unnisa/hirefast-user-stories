Epic 3: Assessment Management
User Story 6: Create Assessment
User Story

As an Administrator

I want to create assessments

So that candidates can complete evaluations.

Acceptance Criteria
Feature: Create Assessment

Scenario: Successful Creation
Given assessment information is valid
When Save is clicked
Then the assessment is created

Scenario: Duplicate Name
Then duplicate assessment names are rejected
