# Manual-Testing-Portfolio

As a certified manual tester with a strong understanding of Behavior-Driven Development (BDD), I am passionate about creating detailed, understandable test cases that aligned with both the business and technical needs. Below are key examples of my work in manual testing, specifically using Gherkin syntax to write clear, readable test cases for functionality testing.

# Test Case Writing with Gherkin Syntax

One of my strengths is writing test cases using Gherkin syntax. Gherkin provides a simple, structured way to write tests cases that everyone on the team can understand, from developers to non-technical stakeholders. 

Explanation:

GIVEN step sets up the preconditions for the test.

WHEN step defines the action that triggers the behavior being tested.

THEN step specifies the expected result.

** Below is an example of a Gherkin-based login functionality test case.

## Login Functionality Test Case 

### Feature: User Login

  #### Scenario 1: User logs in with valid credentials
    Given the user navigates to the login page
    And the user enters a valid username "testuser"
    And the user enters a valid password "testpassword9876"
    When the user clicks the "Login" button
    Then the user should be redirected to the dashboard
    And the user's username "testuser" should be displayed on the dashboard

  Scenario 2: User logs in with invalid credentials
    Given the user navigates to the login page
    And the user enters an invalid username "wronguser"
    And the user enters an invalid password "wrongpassword"
    When the user clicks the "Login" button
    Then the user should see an error message "Invalid credentials"

## Defect Reporting

When reporting defects, I always ensure the issue is well-documented and actionable. Below is an example of a defect report that follows a structured approach for tracking issues.

## Defect ID: 

DEF-001

## Summary: 

"Sign Up" button not functional on the registration page.

## Description: 

When entering valid data in all fields on the registration page and clicking the "Sign Up" button, the page does not respond.

## Steps to Reproduce:

1. Navigate to the registration page.
2. Fill in the required fields (e.g., Name, Email, Password).
3. Click the "Sign Up" button.
4. Expected Result: User should be successfully registered, and a confirmation message should appear.

5. Actual Result: The button does not trigger any action, and the user is not registered.

## Severity: 

High

## Priority: 

Critical

## Status: 

Open

## Assigned to: 

Developer team for resolution

## Attachments: 

Screenshot of the registration page with the non-functioning "Sign Up" button.

# Conclusion

I am passionate about ensuring software quality by writing clear, maintainable test cases using Gherkin syntax. This portfolio showcases how I use Behavior-Driven Development (BDD) principles to ensure that both technical and non-technical stakeholders have a shared understanding of functionality. I look forward to contributing my skills to your team and continuing to grow as a Manual Tester.

## Connect with Me

If you have any questions, feedback, or just want to connect, you can reach me at abidoyeolayinka@yahoo.com
