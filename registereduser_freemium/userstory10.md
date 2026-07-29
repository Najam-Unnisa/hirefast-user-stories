Feature 8: Premium Access Restriction
User Story 11: Restrict Premium Features
User Story

As a Registered User

I want to know which features require a premium subscription

So that I understand the additional benefits available.

Acceptance Criteria
Feature: Premium Restrictions

Scenario: Access Premium Assessment
Given the user is a Registered (Freemium) user
When the user selects a Skill-Based Assessment
Then access is denied
And an upgrade prompt is displayed

Scenario: Premium Dashboard Widget
When premium-only content is displayed
Then it is clearly marked as Premium
And includes an upgrade call-to-action
