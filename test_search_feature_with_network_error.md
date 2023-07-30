## Test Case: Unit Testing for Search Feature with Network Error for Shoppies Website

**Test Case ID:** TST-10

**Test Case Description:** This test verifies whether turning off the internet is handled gracefully by the website.

**Preconditions:**
- A compatible browser (e.g., Chrome, Firefox, Safari) is installed and accessible.
- The internet connection is stable and reliable.

| Test Step                                         | Expected Result                                         | Actual Result                                         |
|---------------------------------------------------|---------------------------------------------------------|-------------------------------------------------------|
| Open the browser and navigate to the Shoppies website | The Shoppies website should open successfully on the browser without any errors or issues | Pass |
| Click on the search bar                          | Search bar enters focused state                         | Pass |
| Turn off the internet                            |                                                         |  |
| Search for "The Matrix" with no internet         | Website should provide a message when encountering network errors | Fail |
