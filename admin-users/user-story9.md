Epic 4: Candidate Management
User Story 9: View Candidates
User Story

As an Administrator

I want to search and manage candidates

So that I can monitor candidate activity.

Acceptance Criteria
Feature: Candidate Management

Scenario: View Candidate List
Given candidates exist
When Candidate Management opens
Then all candidates are listed

Scenario: Search Candidate
When a search keyword is entered
Then matching candidates are displayed
