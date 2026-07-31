User Story 1: Admin Login
User Story

As an Administrator

I want to securely log into the Admin Portal

So that I can manage the HireFast platform.

Acceptance Criteria
Feature: Admin Login

Scenario: Successful Login
Given the administrator has valid credentials
When the administrator logs in
Then the system authenticates the administrator
And redirects to the Admin Dashboard

Scenario: Invalid Credentials
Given invalid credentials
When login is attempted
Then an authentication error is displayed

Scenario: Session Expired
Given the administrator session expires
When any secured page is accessed
Then the user is redirected to Login
