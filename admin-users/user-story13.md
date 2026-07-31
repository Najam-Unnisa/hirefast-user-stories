Epic 6: Reports & Analytics
User Story 13: Generate Reports
User Story

As an Administrator

I want to generate platform reports

So that I can monitor operational performance.

Acceptance Criteria
Feature: Reports

Scenario: Generate Report
Given report filters are selected
When Generate is clicked
Then the report is produced successfully

Scenario: No Matching Data
Then an empty report message is displayed
