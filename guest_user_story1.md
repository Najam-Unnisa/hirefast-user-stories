Epic: Guest User Onboarding & Assessment Experience

Business Goal

Reduce onboarding friction by allowing users to experience HireFast before completing profile registration, thereby improving Guest-to-Registered conversion.

Persona

Guest User (Authenticated via Google but profile not completed)

Success Criteria

Guest can sign in with Google.
Guest account is created automatically.
Guest can complete the General Communication Assessment.
Assessment is evaluated.
JRS and AI Summary are generated but hidden.
Guest is prompted to complete profile registration.
Profile completion unlocks results.
Feature: Guest Login & Assessment Flow
User Story 1: Google Sign-In
Title

Guest User Login using Google

Description

Allow new users to authenticate using Google as the only authentication method for the MVP.

User Story

Acceptance criteria :

Feature: Google Authentication

Background:
Given the user is on the HireFast Landing Page

Scenario: Successful Google Login
When the user clicks "Continue with Google"
And successfully authenticates with Google
Then the system creates a Guest account if one does not exist
And logs the user into HireFast
And redirects the user to the General Communication Assessment

Scenario: Returning Guest Login
Given the Guest account already exists
When the user signs in with the same Google account
Then the existing Guest account is used
And the user resumes their Guest experience

Scenario: Google Authentication Cancelled
When the user cancels Google authentication
Then no account is created
And the user remains on the Login page

Scenario: Authentication Failure
When Google authentication fails
Then an error message is displayed
And the user can retry login
As a new candidate

I want to sign in using my Google account

So that I can start using HireFast without creating a separate password.
