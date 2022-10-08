# Test Plan

**Author**: Team004

## 1 Testing Strategy

### 1.1 Overall strategy

This document is to document the test plan of Team004 in developing an app to compare job offers as instructed. We are going to test the robustness of the app and the correctness of the results. A table of test cases is shown at the bottom of the document, and bugs will be logged. The test activities will be performed majorly by Maohua Pan, and supported by other group members if necessary.

### 1.2 Test Selection

We are going to select test cases that can show if the app could function normally using black-box techniques, and select test cases that can check if the app would rank jobs as we expected using white-box techniques.

### 1.3 Adequacy Criterion

We will compare the actual results to the expected results, whether they match or not will give us a hint if our test cases work.

### 1.4 Bug Tracking

Bugs will be documented in a log.

### 1.5 Technology

JUnit will be used here.

## 2 Test Cases


|Test Case |Purpose|Steps|Expected Result|Actual Result|Pass/Fail|
|----------|-------|-----|---------------|-------------|---------|
|Ability to enter current job details|Test if add function works|Open main menu|A new current job will be added| |Pass|
|Ability to edit current job details|Test if edit function works|Open main menu and click current job|Current job details will be edited| |Pass|
|Ability to enter job offers|Test if add new job offer works|Open main menu and enter new job details|A new job will be added| |Pass|
|Ability to adjust weight settings|Test if adjustment works|Open comparison settings |Weights will be adjusted| |Pass|
|Ability to select two jobs|Test if comparison function works|Select two jobs|A rank will be returned| |Pass|
|Ability to return the correct ranking|Test if the math to compare is correct|Select two jobs|A correct rank will be returned| |Pass|
|Salary<0|Test with corner case|Change the salary attribute |Throw out error message| |Fail|
|weight<0|Test with corner case|Change the weight setting|Throw out error message| |Fail|


