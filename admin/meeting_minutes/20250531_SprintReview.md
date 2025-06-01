# Sprint Review
## Meeting Information
- **Meeting Date/Time:** May 31, 2025 @ 5:00 PM
- **Meeting Purpose:**
  - Final sprint overview notes (feedback from Rashi, etc).
  - Sprint review meeting (5/26 - 6/1 sprint)
- **Meeting Location:** Online via Zoom
- **Meeting Lead:** Ashley
- **Note Taker:** Ashley

## Attendance
UCSD is having wifi issues- people might not make it.
- [ ] Arlene Garcia (absence told ahead of time)
- [X] Ashley Vo
- [X] Chanbin Na
- [X] Dorje Pradhan
- [X] Kiara Singh
- [ ] Kiet Dang
- [X] Minahil Yasar
- [X] Patrick Thant
- [X] Ryan Awal
- [X] Samson Gebrekidan
- [X] Shashwat Dudeja

## Outline
| Topics Overview |
| ---- |
| [TA Feedback](#ta-feedback) |
| [Sprint Review](#sprint-review-1) |

## TA Feedback
Rashi left us comments on our last sprint and information for the coming and last sprint.

### Project + Sprint Feedback
#### The Good
- Our stand ups, meeting notes, and reviews are well documented, and she can tell that we're being active as a team by looking at Slack and our repository.
- Our repo is well organized (+1 for the issue numbers <==> branches- "at par with industry standards").
- We have 3-4 solid ADRs (although stand-up frequency isn't really an ADR).
#### The "To Improve/Work On"
- **PULL REQUESTS** Our PRs do *not* currently follow a template and many of them lack descriptions. When looking at them, it's hard to tell what's going on and being added by a PR. Add these.
- **CI/CD MISSING**. JSDocs, unit testing, and code coverage are missing. We definitely are going to need to get to these this last sprint.
- `.DS_Store` shouldn't be in the repo-- add it to `.gitignore`.
- Link documents to our project README.

## Sprint Review
| Team | Who | 
| ---- | ---- |
| [Recipe Creation + DB Integration](#recipe-creation--db-integration) | Ashley, Kiet, Samson | 
| [Home Page Filtering](#home-page-filtering) | Kiara, Mina, Patrick | 
| [Card Action Interactions](#card-action-interactions) | Arlene, Chanbin, Patrick, Ryan | 
| [CSS Helpers + UX/UI Clean-up](#css-helpers--uxui-clean-up) | Chanbin, Dorje, Shash | 

### Recipe Creation + DB Integration
| Member | Thoughts on Sprint |
| ----   | ---- |
| Ashley | Things took a lot longer than expected (sending data in proper formats to localStorage and IDB), but we managed to make things work. We probably should have had four people. | 
| Kiet   | Absent. | 
| Samson | No comments. Learned a lot from Kiet and Ashley. | 

#### Comments/Suggestions/Questions:
- Three inputs are easy for parsing and was a good decision.

### Home Page Filtering
| Member  | Thoughts on Sprint |
| ----    | ---- |
| Kiara   | Wifi cut out during the meet but can work on it later today. | 
| Mina    | So far the filtering isn't working. Tomorrow it should be working. | 
| Patrick | Refactored the code for ingredients filter button on the home page. Right now, they need to handle some CSS for the dropdown box, but Patrick has already added the placeholder code for it in the JS. Handled metadata scraping for ingredient tags from localStorage. | 

#### Comments/Suggestions/Questions:
- CSS team can help with the boxes and styling.
- Task was a lot harder and took a lot more time than expected.

### Card Action Interactions
| Member  | Thoughts on Sprint |
| ----    | ---- |
| Arlene  | Absent. | 
| Chanbin | Need to update recipe page, but got basic interactions working. Plans exist to work on it tonight and tomorrow. | 
| Patrick | Haven't done gotten the data from the database for the recipe page. | 
| Ryan    | Scheduling was an issue, but will work with Chanbin to finish it tonight or even tomorrow. | 

#### Comments/Suggestions/Questions:
- N/A

### CSS Helpers + UX/UI Clean-up
| Member  | Thoughts on Sprint |
| ----    | ---- |
| Chanbin | Not really. Dorje really covered most of it. | 
| Dorje   | Fixed duplicating search bars on the branch. Worked on styling for mobile. Still need to work on grid for displaying cards. CSS team hasn't gotten together. | 
| Shash   | Catching up with the team's progress. | 

#### Comments/Suggestions/Questions:
- Search bar doesn't really make sense on the "recipe details" and "add recipe" pages.

## The "To-Do" for Next Sprint
- [ ] Clean up our repo (hide files)
  - [ ] PR template (retroactively add descriptions to our old PRs)
  - [ ] Hide files that shouldn't be in our repo (e.g. `.DS_Store`)
  - [ ] Delete old branches
- [ ] Testing for CI/CD
  - [ ] Input validation?
    - [ ] Make sure if only 3 input fields are filled but n are created, only add those 3 filled ones to the database (for ingredients and instructions)
  - [ ] Database validation (e.g. if I add two recipes, expect two recipes)
  - [ ] Filtering tests (e.g. if we filter recipes that have tomatoes, we should see only the number of recipes that have tomatoes).
  - [ ] JSDocs
  - [ ] Code coverage 
- [ ] Clean up UX/UI (aka CSS)? Depending on how this sprint ends.
- [ ] Search bar via recipe name
  - See https://www.w3schools.com/howto/howto_js_autocomplete.asp as an example.
- [ ] Refactor
  - `<noscript>`
  - ONE JS file then put all the dependencies there (Rashi's suggestion).

## Other Notes & Information
- Question: Are they looking for a completed project or moreso a snapshot of our progress?
  - Given more time, there are things we wish we could have gotten to but didn't have the time for (Backlog).
