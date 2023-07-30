## Test Case: Banner Text Change

**Test Case ID:** TST-19

**Test Case Description:** This test case verifies that the text "NOMINATIONS SELECTED" changes to "CLICK HERE TO SUBMIT" only when 5 movies have been selected.

**Preconditions:**
- A compatible browser (e.g., Chrome, Firefox, Safari) is installed and accessible.
- The internet connection is stable and reliable.

| Test Step                                         | Expected Result                                         | Actual Result                                         |
|---------------------------------------------------|---------------------------------------------------------|-------------------------------------------------------|
| Open the browser and navigate to the Shoppies website | The Shoppies website should open successfully on the browser without any errors or issues | Pass |
| Click on button "CLICKING HERE"                  | The website will transition smoothly from the homepage to the search page | Pass |
| Click on the search bar                          | Search bar becomes focused                              | Pass |
| Search "Harry Potter"                            | Titles relevant to "Harry Potter" should populate the list | Pass |
| Nominate 4 movies from the list                  | Banner text will remain the same                       | Pass |
| Nominate 1 more movie bringing the total to 5 movies | Banner text will change from "NOMINATIONS SELECTED" to "CLICK HERE TO SUBMIT" | Pass |
| Remove 1 nomination from the list                | Banner text will change back to "NOMINATIONS SELECTED" | Pass |
