## Test Strategy

  - [A. Introduction:](#a-introduction)
  - [B. Test Environment](#b-test-environment)
  - [C. Testing type](#c-testing-type)
  - [D. Scope of Work](#d-scope-of-work)
  - [E. Test Approach:](#e-test-approach)
  - [F. Entrance and Exit criteria](#f-entrance-and-exit-criteria)


### [A. Introduction](#a-introduction): 
This document intends to provide all team members with an overview of the testing scope and approaches to be used in the project. 

### [B. Test Environment](#b-test-environment)

| Environment | URL                                             | Description  |
| ----------- | ----------------------------------------------- | ------------ |
| QC env      | http://todomvc.com/examples/firebase-angular/#/ | Full Testing |

### [C. Testing type](#c-testing-type)
- **Functional testing**: will focus on the Requirements Documentation as well as the User Stories. The QA team will generate test scenarios that will be used during this test. Both negative and positive testing methods will be utilized to ensure that the Platform conforms to the requirements.

- **Static testing**: review and give fast feedback to BA/PO/Client to update the requirements, and to enrich requirements before implementation

- **Automation test**: Some stable parts in regression tests will be automated to get fast feedback and reduce testing time.

- **Testing related to changes (regression testing)**: QA will ensure that although an enhancement has been tested and passed, that no other modification has been broken. This will be accomplished via both manual testing and using the automated tools described above.

  

### [D. Scope of Work](#d-scope-of-work)

1. Platform and browser

    | Platform /Browser       | Description                         |
    | ----------------------- | ----------------------------------- |
    | Win 10 /Chrome(latest)  | Run all test cases                  |
    | Win 10 /Firefox(latest) | Run only highest priroty test cases |

2. Features to be tested

    | No  | Description             | Priority |
    | --- | ----------------------- | -------- |
    | 1   | Add tasks               | 1        |
    | 2   | Marking task “complete” | 2        |
    | 3   | Delete task             | 3        |
    | 4   | Filter task by Active   | 3        |
    | 5   | Filter task by Complete | 3        |
    | 6   | Filter task by All      | 3        |
    
  Notes: The less priority is, the more important feature is 

3. Features NOT to be tested: N/A
   
### [E. Test Approach](#e-test-approach): 
The QA will perform testing within the Agile workflow to verify each individual Sprint, task, component or user story as it becomes available for testing. To perform the testing activities effectively, "Shift-left testing" and "Automation" are conducted on each testable items.

1. Shift-left Testing: is a method helpping team to prevent issues/defects sooners and give feedback about quality sooner.

    1.1. What to do:
      -    Carried out the review testing and risk analysis for testable tasks.
      -    Test as early as possible by:
           -    Performing verification for a part of a feature when it's available, don't wait for all things to be integrated.
           -    The feature could be verified at local environment.
    
    1.2. Goals:
      - Detect issues in Requirements quickly.
      - Team is aware of risks, and allows the team to take more ownership in quality.
      - Reduce the testing time, and give quality feedback quickly.

2. Automation Testing (UI based): is a method helpping team to reduce the testing time and effort.
   
    2.1. What to do:
    -   Framework: Codeceptjs (please refer to [Automation Plan](https://github.com/hungdao-testing/TodoMVC/blob/master/Automation_Approach.md))
    -   Utilize the resources in team to write test script

    2.2. Goals:
    -   Detect issues quickly before releasing build to QA/customer.
    -   Reduce the testing efforts.

### [F. Entrance and Exit criteria](#f-entrance-and-exit-criteria)
Testing process is a part of Development cycle in Agile model. QA and team will work together to identify a schedule for delivering each Sprint or task as it is completed so that we achieve the greatest quality in the shortest possible time. Before doing or releasing builds, we must follow the Definition Of Done (DOD) and Definition of Ready (DOR) in project plan, here are outstanding points related to quality:

1. DOR (the conditions to test the tasks)
   -   The tasks must described clearly what could be tested and what could not be tested.
   -   All blockers and dependencies are resolved completedly.
   -   Before releasing the tasks to QA team, they must satisfy the quality coverage at Unit test level.
   -   Before releasing the tasks to QA team, they must be passed the acceptance criterias. If NOT, please list out what items are done.

2. DOD (the conditions to mark the tasks done)
   - All test cases are executed.
   - No major defects remain.
