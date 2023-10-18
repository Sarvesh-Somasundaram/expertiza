# To-Do List

## Issue 1:
- [ ] **Problem:** Error message shows up when clicking on “New Late Policy” in “due date” tab.
- [ ] **Solution:** 
    - Determine the root cause of the error message.
    - Fix the error so that it doesn't occur.
- [ ] **Testing:** Add a test case that verifies the error doesn’t occur.

## Issue 2:
- [ ] **Problem:** Clicking the "Back" link on the "New late policy" page when creating a policy takes the instructor to an error page instead of the “Due Date” tab of the assignment edit page.
- [ ] **Solution:** 
    - Ensure the "Back" link on the "New late policy" page directs the user to the "Due dates" tab.
- [ ] **Testing:** Add a test case which verifies the corrected behavior.

## Issue 3:
- [ ] **Problem:** On the “New Late Policy” page, clicking “Create” displays a list of late policies. The “back” link on this page currently gives an error as it can't find an assignment number.
- [ ] **Solution:** 
    - The “back” link should redirect to the “Due Date” page of the assignment being edited.
- [ ] **Testing:** Add a test case to check the fixed behavior and verify it passes.

## Additional Issues (conditional on above fixes):
- [ ] **Problem:** If a user directly accesses the “New Late Policy” page, without the “edit assignment” workflow, the “Back” link on both “new late policy” and “all late policies” pages should direct to the Assignments tab on the home screen, given there's no "assignment" they are editing.
- [ ] **Solution:** 
    - Set conditional logic to determine the origin of the user's navigation. If they didn't come through the “edit assignment” workflow, the back link should redirect to the Assignments tab on the home screen.
- [ ] **Testing:** Add test cases to verify the above behaviors.
