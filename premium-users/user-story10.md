Feature 9: Download Assessment Reports
User Story 10: Download Reports
User Story

As a Premium User

I want to download my assessment reports

So that I can keep or share my results.

Acceptance Criteria
Feature: Report Download

Scenario: Download Successful
Given a completed report exists
When the user selects Download
Then the report is generated
And downloaded successfully

Scenario: Download Failure
When report generation fails
Then an error message is displayed
And the user can retry
