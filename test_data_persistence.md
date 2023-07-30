## Test Case: Data Persistence

**Test Case ID:** TST-21

**Test Case Description:** This test case verifies that the data persists if the user navigates away from the website.

**Preconditions:**
- A compatible browser (e.g., Chrome, Firefox, Safari) is installed and accessible.
- The internet connection is stable and reliable.

| Test Step                                         | Expected Result                                         | Actual Result                                         |
|---------------------------------------------------|---------------------------------------------------------|-------------------------------------------------------|
| Open the browser and navigate to the Shoppies website | The Shoppies website should open successfully on the browser without any errors or issues | Pass |
| Click on button "CLICKING HERE"                  | The website will transition smoothly from the homepage to the search page | Pass |
| Click on the search bar                          | Search bar becomes focused                              | Pass |
| Search "Harry Potter"                            | Titles relevant to "Harry Potter" should populate the list | Pass |
| Nominate 1 movie                                 | Movie will be added to nominations                     | Pass |
| Navigate to another website and then come back to the Shoppies app | List of nominations should remain unchanged     | Pass |
| Nominate 1 more movie                            | Nominations will have 2 total                          | Pass |
| Close the Shoppies App and reopen it             | List of nominations should remain unchanged            | Pass |
