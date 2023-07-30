## Test Case: API Testing for Search Feature

**Test Case ID:** TST-10

**Test Case Description:** This test verifies the response from requests made to the OMDB API.

**Preconditions:**
- A compatible browser (e.g., Chrome, Firefox, Safari) is installed and accessible.
- The internet connection is stable and reliable.
- Have Postman installed and open on your computer.

| Test Step                                         | Expected Result                                         | Actual Result                                         |
|---------------------------------------------------|---------------------------------------------------------|-------------------------------------------------------|
| Make a GET request with the URL http://www.omdbapi.com/?apikey=[yourkey]&s=matrix | Response code 200                                    | Pass |                                                      
