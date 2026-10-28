
# Test Plan – OpenCart E-commerce Application

## 1. Project Information

- **Project Name:** OpenCart Manual Testing Project
- **Application Under Test:** OpenCart Demo Store
- **Website:** https://demo.opencart.com/
- **Project Type:** Manual Software Testing
- **Testing Approach:** Black-box testing
- **Project Status:** In Progress
- **Document Version:** 1.0
- **Prepared By:** QA Portfolio Project
- **Target Environment:** Public demo website

## 2. Overview

This project focuses on manually testing the functional
features of the OpenCart e-commerce demo application.

The objective is to evaluate the application's main
user workflows, identify potential defects, validate
expected behaviour, and document test execution results.

The project follows a structured Software Testing Life
Cycle (STLC), including test planning, test design,
test execution, defect reporting, regression testing,
and test closure.

This is an independent QA portfolio project and is not
an official engagement with OpenCart.

## 3. Scope

The scope of this project includes functional testing of
the major features available in the public demo store.

Testing will focus on:
- Correct application behaviour
- Input validation
- Navigation and user workflows
- Positive and negative scenarios
- Error messages and usability
- Identification and documentation of reproducible defects

## 4. Inclusions

The following features are included, subject to their
availability in the demo environment:

1. Home Page
2. User Registration
3. User Login and Logout
4. Forgot Password
5. Product Search
6. Product Compare
7. Product Display / Details Page
8. Add to Cart
9. Wish List
10. Shopping Cart
11. Currency Selection
12. Checkout Page
13. My Account Page
14. Order History
15. Downloads Page
16. Contact Us Page
17. Menu Options
18. Footer Options
19. Category Pages

Features that are unavailable or restricted in the
current demo environment will be recorded as blocked
or not applicable, with an explanation.

## 5. Test Environments

### Primary Environment

- Operating System: Windows 11
- Browser: Google Chrome
- Application: Public OpenCart demo website
- Testing Method: Manual browser-based testing

### Additional Environments

The following environments may be tested if available:

- Microsoft Edge on Windows
- Safari on macOS
- Chrome on Android
- Safari on iPhone

The actual operating system, browser version, execution
date, and any relevant environment details will be
recorded during test execution.

Testing will not be claimed on environments that have
not actually been used.

## 6. Exclusions

The following items are outside the scope of this project:

- Performance and load testing
- Security penetration testing
- Source-code and white-box testing
- Real payment processing or real financial transactions
- Third-party payment gateway certification
- Features unavailable in the public demo environment
- Production deployment and production data validation
- Automated testing in the initial manual testing phase

Automation may be considered as a future enhancement.

## 7. Test Strategy

Testing will be conducted using a risk-based and
black-box manual testing approach.

### 7.1 Test Planning and Design

Test scenarios and test cases will be prepared using
appropriate test design techniques:

- Equivalence Partitioning
- Boundary Value Analysis
- Decision Table Testing
- State Transition Testing
- Use Case Testing
- Error Guessing
- Exploratory Testing

Test cases will be prioritized according to business
importance, user impact, and risk.

### 7.2 Test Execution Process

1. Review the available application features.
2. Prepare test scenarios and detailed test cases.
3. Perform initial smoke testing.
4. Execute functional and negative test cases.
5. Compare actual results with expected results.
6. Record the execution status of each test case.
7. Document and report reproducible defects.
8. Retest fixes where possible.
9. Perform regression testing on affected functionality.
10. Prepare a test execution summary.

If a critical issue prevents meaningful testing, the
affected tests will be marked blocked until the issue
can be investigated or resolved.

### 7.3 Types of Testing

- Functional Testing
- Smoke Testing
- Sanity Testing
- Positive Testing
- Negative Testing
- Integration-oriented workflow testing
- UI and Usability Testing
- Regression Testing
- Retesting
- End-to-End Workflow Testing

### 7.4 Testing Best Practices

- Risk-based test prioritization
- Exploratory testing
- Context-driven testing
- Shift-left testing principles during test design
- End-to-end user journey validation
- Clear documentation and reproducible test steps

## 8. Defect Reporting Procedure

Any reproducible deviation from expected behaviour
will be documented as a potential defect.

Each defect report will contain:

- Defect ID
- Defect Title
- Functional Module
- Environment
- Preconditions
- Steps to Reproduce
- Expected Result
- Actual Result
- Severity
- Priority
- Supporting Screenshot, where available
- Defect Status

### Defect Workflow

New → Under Investigation → Fixed (if applicable)
→ Retest → Closed or Reopened

Actual workflow states may vary depending on the
tracking method used.

### Severity

- Critical: Major application functionality is unusable
  or a severe business impact is observed.
- High: Important functionality is significantly affected.
- Medium: Functionality is affected but a workaround
  may exist.
- Low: Minor UI, content, or usability issue.

Severity will be assigned based on observed impact.
Priority will reflect the urgency of investigation.

Defects will only be reported after the behaviour has
been observed and reproduced where possible.
Expected behaviour will not be presented as a confirmed
defect without evidence.

## 9. Roles and Responsibilities

This is an individual portfolio project. The following
responsibilities are performed by the project author.

| Role | Responsibilities |
|---|---|
| QA Engineer / Tester | Review application features, prepare test scenarios, execute tests, record actual results, and report defects. |
| Test Analyst | Apply test design techniques, identify boundary and negative scenarios, and prioritize test cases. |
| Test Coordinator | Maintain test documents, track progress, and prepare the final test summary. |
| Developer / Application Owner | Not assigned within this independent project. Defect fixes cannot be assumed. |

No client, manager, or development team approval is
claimed as part of this portfolio project.

## 10. Test Schedule

The schedule will be updated as the project progresses.

| Task | Planned Activity | Status |
|---|---|---|
| Test Planning | Define scope, approach, risks, and environments | In Progress |
| Test Design | Prepare test scenarios and test cases | Planned |
| Test Environment Review | Check website accessibility and available features | Planned |
| Smoke Testing | Validate basic application availability | Planned |
| Functional Test Execution | Execute planned test cases | Planned |
| Defect Reporting | Document observed issues and evidence | Planned |
| Retesting | Recheck fixes when available | Planned |
| Regression Testing | Recheck affected functionality | Planned |
| Test Closure | Prepare final test summary | Planned |

Actual dates and durations will be recorded when
each activity is performed.

## 11. Test Deliverables

The following deliverables will be maintained in the
GitHub repository:

| Deliverable | Description |
|---|---|
| Test Plan | Scope, strategy, environments, risks, and schedule |
| Test Cases | Test scenarios, steps, test data, and expected results |
| Test Execution Report | Actual results and pass/fail/blocked status |
| Defect Reports | Reproducible issues with steps and evidence |
| Test Summary Report | Execution statistics, defect summary, and limitations |
| Supporting Evidence | Screenshots and other relevant observations |

## 12. Entry and Exit Criteria

### 12.1 Requirement Analysis

**Entry Criteria**
- Application URL and available functionality are identified.

**Exit Criteria**
- Main features and user workflows are understood.
- Initial testing scope and limitations are documented.

### 12.2 Test Planning

**Entry Criteria**
- Application features have been reviewed.
- Initial scope and objectives are defined.

**Exit Criteria**
- Test plan is documented and reviewed by the project author.

### 12.3 Test Design

**Entry Criteria**
- Test scope and approach are defined.

**Exit Criteria**
- Test scenarios and test cases are documented.
- Expected results and test data are specified where applicable.

### 12.4 Test Execution

**Entry Criteria**
- The demo website is accessible.
- Relevant test cases are prepared.
- Suitable test data is available.

**Exit Criteria**
- Planned test cases have been executed where possible.
- Actual results and execution statuses are recorded.
- Failed or blocked tests have explanations.
- Observed defects are documented where applicable.

### 12.5 Test Closure

**Entry Criteria**
- Test execution results are documented.
- Known defects and testing limitations are recorded.

**Exit Criteria**
- Test summary is prepared.
- Execution statistics are reviewed.
- Outstanding risks and untested areas are documented.

These criteria apply to this portfolio project and do
not represent formal client sign-off requirements.

## 13. Suspension and Resumption Criteria

### Suspension Criteria

Testing of an affected feature may be suspended when:

- The demo website is unavailable.
- A blocking error prevents further execution.
- Required functionality cannot be accessed.
- Test data or a required service is unavailable.

### Resumption Criteria

Testing may resume when:

- The website or relevant functionality is accessible.
- The blocking issue no longer prevents execution.
- Required test data or access is available.
- The affected test cases can be executed meaningfully.

Blocked tests will retain their status and reason until
they can be executed.

## 14. Tools

The following tools will be used as appropriate:

- GitHub: Version control and portfolio documentation
- Google Chrome: Browser-based manual testing
- Microsoft Excel or Google Sheets: Test case tracking
- Browser Developer Tools: Inspection of visible UI and
  relevant browser errors
- Screenshot Tool: Capture of supporting evidence
- Markdown: Documentation of test plans and reports

A defect tracking tool such as Jira may be used for
practice if available, but no Jira usage will be claimed
unless it is actually performed.

## 15. Risks and Mitigations

| Risk | Mitigation |
|---|---|
| Demo website is unavailable | Record the issue and resume testing when accessible. |
| Demo data resets | Record test data and capture evidence promptly. |
| Features differ from documentation | Verify current behaviour before executing tests. |
| External services are unavailable | Mark affected tests blocked and explain the reason. |
| Limited testing time | Prioritize high-risk and critical user workflows. |
| Defects cannot be fixed in the demo | Document findings and retest only if a fix becomes available. |
| Browser or environment differences | Record the actual test environment and limitations. |
| No access to source code | Restrict conclusions to observed black-box behaviour. |

## 16. Approvals and Sign-Off

This document is maintained for learning and portfolio
demonstration purposes.

Formal client approval is not applicable because this
is an independent project.

The project author will review the test plan and update
it when the scope, environment, or testing approach
changes.

## 17. Project Status

The test plan defines the proposed testing approach.
Test execution, defect findings, and final statistics
will be added as testing progresses.

No test results, defect counts, or approvals are
claimed before they have actually occurred.
