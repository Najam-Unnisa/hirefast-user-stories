Feature 5: Personalized Learning Recommendations
User Story 6: Receive Learning Recommendations
User Story

As a Premium User

I want personalized recommendations

So that I know which skills to improve next.

Acceptance Criteria
Feature: Personalized Learning

Scenario: Recommendations Available
Given assessment reports exist
When the user opens Recommendations
Then personalized learning suggestions are displayed
And recommendations are based on assessment performance

Scenario: No Recommendations
Given recommendation data is unavailable
When the page loads
Then an informative message is displayed
