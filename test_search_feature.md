## Test Case: Unit Testing for Search Feature for Shoppies Website

**Test Case ID:** TST-9

**Test Case Description:** This test verifies whether the movie search feature works successfully to retrieve the user's query.

**Preconditions:**
- A compatible browser (e.g., Chrome, Firefox, Safari) is installed and accessible.
- The internet connection is stable and reliable.

| Test Step                                         | Expected Result                                         | Actual Result                                         |
|---------------------------------------------------|---------------------------------------------------------|-------------------------------------------------------|
| Open the browser and navigate to the Shoppies website | The Shoppies website should open successfully on the browser without any errors or issues | Pass |
| Navigate to the search page                       | The website's homepage should display the search bar and should navigate to the search page smoothly when clicked on | Pass |
| Click on the search bar                          | Search bar enters focused state                         | Pass |
| Search for "The Matrix"                          | Searching for "The Matrix" should retrieve relevant search results | Pass |
| Search for "Ma"                                 | Searching for "Ma" should retrieve relevant search results | Fail |
| Delete "a"                                       | Verify that results update to show different relevant movies which begin with the letter "M" | Fail |
| Clear the search bar                             | Verify that no movies appear                             | Pass |
| Search for "hskdskmsk"                           | Verify that no results show up                           | Pass |
| Search "21 Jump"                                | Verify that "21 Jump Street" shows up                    | Pass |
