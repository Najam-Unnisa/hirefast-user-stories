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

User Story 10: Achievement Badges
User Story

As a Registered User

I want to earn badges

So that my achievements are recognized.

Acceptance Criteria
Feature: Badges

Scenario: Earn First Assessment Badge
Given the user completes the first assessment
Then the "First Assessment" badge is awarded

Scenario: Badge Display
When the user opens the Dashboard
Then all earned badges are displayed
