## Test Automation Approach

  - [A. Overview:](#a-overview)
  - [B. Scope](#b-scope)
  - [C. Test Schedule](#c-test-schedule)
  - [D. Design Automation framework strategy](#d-design-automation-framework-strategy)

### [A. Overview](#a-overview): 
- Tool selection: CodeceptJs (Refer to [Automation tool evaluation](https://github.com/hungdao-testing/TodoMVC/blob/master/Automation_tool_evaluation.md) to know why we choose this framework)
- Apply “whole team” approach: Dev and QA contribute to write test scripts
- The test script is developed based on the scenarios defined in user stories.
- The test scripts will be executed based on incremental internal build and major build   
- The test goal will be executed for smoke test and regression test
- These test cases will be automated:
  - The repetitive tasks look like smoke test and regression test
  - Involve complex business logic
- Test automation will start in each sprint

### [B. Scope](#b-scope)

- In Scope: Based on the features in test plan
- Out of scope: Need to discuss each sprint planning.


### [C. Test Schedule](#c-test-schedule)
- Develop test script right after finishing manual execution. In case we don’t have enough time, we will move to the next sprint.
  

### [D. Design Automation framework strategy](#d-design-automation-framework-strategy)
1. Coding convention:
   - Follow coding conventions as a Development team.

2. Web element locator:
   - Working with the Dev team to define attributes for web elements when starting implementing a feature. It helps QA easily to get elements and maintain script better.

3. Design framework
   - Apply [Page Object Model](https://codecept.io/pageobjects/#pageobject)
   - Apply [Page Fragment](https://codecept.io/pageobjects/#page-fragments)
   - Follow design patterns as in development team to maintain the script better.




