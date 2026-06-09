# Task 02: Bug Fix

**Category:** Debugging  
**Difficulty:** Easy  
**Estimated Time:** 20 minutes

## Objective

The Node.js project in `artifacts/node_project.tar.gz` contains an off-by-one bug in the `calculateDiscount` function. Find and fix it.

## Bug Description

The `calculateDiscount` function in `src/discount.js` is supposed to apply a discount for orders of a certain size but uses an incorrect comparison operator.

## Requirements

1. Extract the project from the tarball.
2. Install dependencies (`npm install`).
3. Run the existing test suite and observe the failing test.
4. Fix the bug in `src/discount.js`.
5. Verify all tests pass after the fix.
6. Commit the fix with a descriptive message.

## Deliverables

- The fixed `src/discount.js` file
- Confirmation that all tests pass

## Evaluation Criteria

- Correct identification of the bug
- Minimal, targeted fix (no over-engineering)
- Tests pass after the fix
- Clear commit message
