Feature 1: Registered User Authentication & Dashboard Access
User Story 1: Login as Registered User
Description

Allow registered users to log in using Google and access their personalized dashboard.

User Story

As a Registered User

I want to sign in using my Google account

So that I can access my HireFast dashboard and continue my learning journey.

Acceptance Criteria (Gherkin)
Feature: Registered User Login

Background:
Given the user has completed profile registration

Scenario: Successful Login
When the user signs in using Google
Then the system authenticates the user
And redirects the user to the Dashboard

Scenario: Returning User
Given the user has previous assessments
When the user logs in
Then the dashboard displays the latest assessment information

Scenario: Authentication Failure
When Google authentication fails
Then an appropriate error message is displayed
