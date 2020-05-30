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

3. Features NOT to be tested: N/A
   
### [E. Test Approach](#e-test-approach): 

1. Shift-left Testing

    1.1. What to do:
      -    Carried out the review testing and risk analysis for testable tasks.
      -    Test as early as possible by:
           -    Performing verification for a part of a feature when it's available, don't wait for all things to be integrated.
           -    The feature could be verified at local environment.
    
    1.2. Goals:
      - Detect issues in Requirements quickly.
      - Team is aware of risks, and allows the team to take more ownership in quality.
      - Reduce the testing time, and give quality feedback quickly.

2. Automation UI
   
    2.1. What to do:
    -   Framework: Codeceptjs (please refer to)
    -   Utilize the resources in team to write test script

    2.2. Goals:
    -   Detect issues quickly before releasing build to QA/customer.
    -   Reduce the testing efforts.

### [F. Entrance and Exit criteria](#f-entrance-and-exit-criteria)
QA and team will work together to identify a schedule for delivering each Sprint or task as it is completed so that we achieve the greatest quality in the shortest possible time. Each task MUST follow the criterias below

1. Entrance Criteria (the conditions to test the tasks)
   -   The tasks must have unit-test.
   -   Passed for Acceptance Checklists described in tasks.

2. Exit Criteria (the conditions to mark the tasks done)
   - All test cases are executed.
   - No major defects remain.
