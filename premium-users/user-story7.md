Feature 6: Assessment History
User Story 7: View Assessment History
User Story

As a Registered User

I want to view my previous assessments

So that I can monitor my improvement over time.

Acceptance Criteria
Feature: Assessment History

Scenario: History Available
Given previous assessments exist
When the user opens Assessment History
Then all completed assessments are listed chronologically

Scenario: Empty History
Given no completed assessments exist
When Assessment History opens
Then an empty state message is displayed
