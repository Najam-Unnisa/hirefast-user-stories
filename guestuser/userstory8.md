User Story 8: Prompt Profile Completion
Title

Prompt Guest to Complete Profile

User Story

As a Guest User

I want to complete my HireFast profile

So that I can unlock my assessment results.

Acceptance Criteria
Feature: Profile Completion Prompt

Scenario: Display Registration Prompt
Given assessment evaluation is complete
When the Guest reaches the results screen
Then a "Complete Your Profile" prompt is displayed

Scenario: Continue Registration
When the Guest clicks Complete Profile
Then the Profile Registration page opens

Scenario: Skip Registration
When the Guest closes the prompt
Then results remain locked
