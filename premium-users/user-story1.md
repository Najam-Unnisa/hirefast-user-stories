
Epic: Registered User (Freemium) Assessment & Dashboard Experience
Business Goal

Provide registered users with complete access to their assessment results, dashboard, and engagement features while encouraging continued platform usage and future premium upgrades.

Persona: Registered User (Freemium)

Success Criteria

User completes profile registration.
Dashboard is accessible.
User can take the General Communication Assessment.
JRS and AI Summary are visible.
Assessment history is maintained.
Gamification features are enabled.
Premium features remain restricted.
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
