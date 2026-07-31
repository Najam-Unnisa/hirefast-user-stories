Feature 5: AI Assessment Report
User Story 6: View AI Summary Report
User Story

As a Registered User

I want to view AI-generated feedback

So that I understand my strengths and areas for improvement.

Acceptance Criteria
Feature: AI Summary Report

Scenario: View AI Report
Given AI evaluation is complete
When the user opens the report
Then the report displays:
And Assessment Summary
And Strengths
And Weaknesses
And Improvement Areas
And Personalized Recommendations

Scenario: AI Processing Delay
Given AI evaluation is pending
When the report page opens
Then a processing message is displayed
