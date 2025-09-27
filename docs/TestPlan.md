# 🧪 Test Plan Document — OpenCart Manual Testing

## 1. Project Overview
OpenCart is an open-source e-commerce platform. This manual testing project will focus on validating core functionalities such as user registration, login, product search, cart operations, and checkout flow.

## 2. Objective
To ensure that the key modules of OpenCart function as expected under normal and edge-case scenarios using manual testing techniques.

## 3. Scope of Testing

### ✅ Included:
- User Registration & Login
- Product Search & Filter
- Add to Cart & Checkout
- Admin Login & Product Management

### ❌ Excluded:
- Performance Testing
- Security Testing
- Third-party integrations

## 4. Test Deliverables
The following documents will be created during the testing process:
- `OpenCart-TestScenarios.xlsx` — High-level test scenarios
- `OpenCart-TestCases.xlsx` — Detailed test cases with steps and expected results
- `OpenCart-BugReport.xlsx` — Logged defects with severity and status

## 5. Test Environment
- **Browser:** Chrome v117+, Firefox v115+
- **OS:** Windows 10
- **Test Data:** Dummy user credentials and product entries

## 6. Test Approach
Manual testing will be performed using scenario-based and exploratory techniques. Both positive and negative test cases will be designed and executed. Any defects found will be logged in Excel with severity tagging.

## 7. Entry Criteria
- Functional modules must be deployed and accessible
- Test data must be prepared
- Environment setup must be completed

## 8. Exit Criteria
- All major test cases must be executed
- Critical bugs must be resolved or documented
- Final bug report must be submitted

## 9. Risks & Mitigation

| ⚠️ Risk | ✅ Mitigation |
|--------|---------------|
| Incomplete test coverage | Prioritize high-impact scenarios |
| UI changes during testing | Revalidate affected test cases |
| Limited test data | Use dummy data for simulation |

## 10. Conclusion
This Test Plan outlines the strategy for manual testing of OpenCart modules. Once the plan is approved, test case design and execution will begin. The goal is to identify functional issues and ensure a stable user experience.

## 📌 Note
Test cases will be designed based on functional understanding of OpenCart modules, aligned with typical FRS expectations.
