Feature 2: Skill-Based Assessment Catalog
User Story 2: Browse Premium Assessments
User Story

As a Premium User

I want to browse available skill-based assessments

So that I can improve skills relevant to my career goals.

Acceptance Criteria
Feature: Premium Assessment Catalog

Scenario: View Assessment Catalog
Given the user has Premium access
When the user opens Assessments
Then all available Skill-Based Assessments are displayed

Scenario: No Available Assessments
Given no premium assessments are currently published
When the user opens the catalog
Then an empty state message is displayed
