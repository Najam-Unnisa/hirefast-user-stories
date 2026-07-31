Epic 7: Platform Settings
User Story 14: Manage Platform Settings
User Story

As an Administrator

I want to configure platform settings

So that system behavior can be managed centrally.

Acceptance Criteria
Feature: Settings

Scenario: Update Settings
Given valid configuration values
When Save is clicked
Then settings are updated

Scenario: Invalid Configuration
Then validation errors are displayed
