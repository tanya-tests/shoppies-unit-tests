## Test Case: Unit Testing for Remove Nomination Feature for Shoppies Website

**Test Case ID:** TST-12

**Test Case Description:** This test case verifies that removing a movie from favorites works.

**Preconditions:**
- Preconditions from fixture `open_website_focused_search` have been met.
- User has at least 2 movies added to nominations.

| Test Step                                         | Expected Result                                         | Actual Result                                         |
|---------------------------------------------------|---------------------------------------------------------|-------------------------------------------------------|
| Execute test steps from fixture `open_website_focused_search` | All test steps pass                                  | Pass |
| Click on the "X" displayed with the nomination on the left side of the page | Movie should be immediately removed from favorites list | Pass |
| Click on "REMOVE" beside another movie            | Movie should be immediately removed from favorites list | Pass |
