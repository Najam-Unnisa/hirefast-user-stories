User Story 3: Access General Communication Assessment
Title

Allow Guest Users to Start Assessment

Description

Guest users should only be able to access the General Communication Assessment.

User Story

As a Guest User

I want to access the General Communication Assessment

So that I can experience HireFast before registering.

Acceptance Criteria
Feature: Guest Assessment Access

Scenario: Eligible Assessment
Given the user is a Guest
When they access assessments
Then only the General Communication Assessment is available

Scenario: Restricted Assessment
Given the user is a Guest
When they attempt to open a Skill-Based Assessment
Then access is denied
And an appropriate message is displayed

Scenario: Assessment Start
Given the assessment is available
When the Guest clicks Start
Then the assessment begins
