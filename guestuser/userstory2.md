User Story 2: Automatic Guest Account Creation
Title

Create Guest Profile Automatically

Description

Automatically create a Guest account after successful Google authentication.

User Story

As a Guest User

I want my account to be created automatically

So that I can immediately access the assessment.

Acceptance Criteria
Feature: Guest Account Creation

Scenario: Create Guest User
Given the user successfully authenticates with Google
When HireFast receives authentication details
Then a Guest account is created
And the account status is "Guest"
And profile completion status is "Incomplete"

Scenario: Existing Guest
Given the Google account already exists
When the user logs in
Then no duplicate Guest account is created
