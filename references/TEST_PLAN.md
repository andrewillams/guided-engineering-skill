# Test Plan Template

Use this template for `docs/engineering/TEST_PLAN.md`.

## 1. Test objective
What delivery are we validating?

## 2. Environment
- Environment:
- Version/commit/build:
- Test data:
- External dependencies:

## 3. Acceptance coverage
| Acceptance criterion | Test ID(s) | Status | Evidence |
|---|---|---|---|

Allowed status: `PASS`, `FAIL`, `BLOCKED`, `NOT TESTED`.

## 4. Automated tests
| ID | Type | Scenario | Command/tool | Expected result | Status |
|---|---|---|---|---|---|

## 5. Assisted/manual tests
For each test, make the instructions reproducible.

### MT-001 — <scenario>
**Preconditions:**

**Steps:**
1. 
2. 

**Expected result:**

**Evidence to capture:**

**If it fails, report:**
- exact step;
- observed result/error;
- screenshot/log if available;
- input/test data used.

## 6. Negative and failure-path tests
| ID | Failure scenario | Expected safe behavior | Status |
|---|---|---|---|

## 7. Regression checks
- 

## 8. Known test gaps
| Gap | Reason | Risk | Follow-up |
|---|---|---|---|

## 9. Final test conclusion
- Release recommendation: GO / NO-GO / CONDITIONAL
- Blocking issues:
- Residual risks:
