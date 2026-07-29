User Story 9: Daily Streak
User Story

As a Registered User

I want to maintain a daily streak

So that I stay consistent with my learning.

Acceptance Criteria
Feature: Daily Streak

Scenario: Continue Streak
Given the user completes an eligible activity today
Then the daily streak increases by one

Scenario: Miss a Day
Given no qualifying activity was completed yesterday
When the user logs in today
Then the streak resets to zero
