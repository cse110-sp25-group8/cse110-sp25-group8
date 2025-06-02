# Meeting Minutes
## Meeting Information
- **Meeting Date/Time:** June 2, 2025 @ 2:00 PM
- **Meeting Purpose:** Plan our final sprint and discuss any loose ends.
- **Meeting Location:** Sixth College RWAC + Zoom
- **Meeting Lead:** Ashley
- **Note Taker:** Ashley

## Attendance
- [X] Arlene Garcia
- [X] Ashley Vo
- [X] Chanbin Na
- [X] Dorje Pradhan
- [X] Kiara Singh
- [X] Kiet Dang
- [X] Minahil Yasar
- [X] Patrick Thant
- [X] Ryan Awal
- [ ] Samson Gebrekidan
- [X] Shashwat Dudeja

## Agenda
⚠️ These are merely for reference if you prefer a "notes" format since the conversation jumped from topic to topic. Member task assignments are **not** posted here. If you're looking for what you're assigned to, please [refer to the project board](https://github.com/orgs/cse110-sp25-group8/projects/4/views/1).

| Discussion Item |
| ---- |
| [Wrap Up Old Sprint](#wrap-up-old-sprint-content) |
| [Repository Clean-up](#repo-clean-up) |
| [CI/CD](#cicd) |
| [Refactoring + Loose Ends](#refactoring--loose-ends) |

### Sprint Planning Overview
The information here is to be copy-and-pasted into our project board. This is just a notes format of our sprint planning discussion.

Each task will be broken into two parts:
1. **High priority** - these are things that DEFINITELY need to be done by our June 8th deadline.
2. **Time permitting** - nice additions to finalize our project but won't be a killer if we don't get them done.

#### Wrap Up Old Sprint Content
- Recipe details needs to finished. Data has yet to be inserted into the page.
- Filtering works and the styling of it looks okay.
  - [ ] Does NOT tell you what you're filtering by
  - [ ] Does NOT support multiple selections. Maybe we want to limit it to maximum of three tags.
  - [ ] Clicking the "Favorites" button on the top right should filtering 
- Edit or delete recipes functionality haven't been added.
- Get rid of the search bar- we don't have time to do it :(
- Scrap the different card views. We don't have time to get to it :(

#### Repo Clean-up
##### Why
> For viewers outside of our team, they should have little-to-no trouble navigating our repository to find necessary information. Our repository should more-or-less "explain itself."

##### High Priority
- [ ] Pull requests template
  - A simple start is the **"what"** the pull request adds and **"why"** the pull request's additions are important)
  - [ ] Retroactively apply them to our old pull requests so outside viewers are aware of what each PR adds to our app.
- [ ] Hide any unnecessary files e.g. `.DS_Store` and add them to `.gitignore`

##### Time Permitting
- [ ] Have a `config` folder to hide our ESLint and `package.json` files. 
  - Ensure any CI/CD processes that rely on these files are still able to run via GitHub Actions (e.g. if we move these files, the JavaScript linter and validator should still be triggered by GitHub Actions on all of our JS files in the repository.) 

#### CI/CD
##### Why
> Building upon our CI/CD is an important process of Agile, which is what we're supposed to be practicing as apart of the project. While it's been stated that we're behind on testing, we should still want to verify the correctness and coding standards of our code.

##### High Priority
- [ ] Unit Testing
  - [ ] Input validation
    - Double check that the user can't enter in wacky information in the input fields. While the "Creating a Recipe -> Database" team from the last sprint checked this, it doesn't hurt to do some extra verification. For example, characters don't belong in `cookTime` or `calories` fields.
    - For **both** ingredients and instruction steps, skip any fields that are blank. For example, if I create 10 blank instruction inputs but only fill in 5 of them, *only* five instructions should be sent to the database-- do *not* send 5 filled instructions and 5 blank instructions.  
  - [ ] Database validation: ensure that data is correct in the database
    - Example 1: if I create two recipes, I expect two recipes in both localStorage and IndexedDB.
    - Example 2: if I have ten recipes but delete three, I expect to see seven recipes in both localStorage and IndexedDB.
    - Example 3: if I edit a recipe, I expect (1) the number of recipes to remain the same before and after I edit the recipe (2) the metadata in localStorage to be updated and the full recipe in IndexedDB to be updated to the new values.
  - [ ] Filtering validation
    - If we filter by recipes that have tomatoes in them (ingredient filter), then we expect to only see recipes that have tomatoes (and the app should show ALL of the recipes that have tomatoes-- not just some of them).
    - Repeat the same process above for recipe categories and cuisine. 
- [ ] JSDocs generation
    - The storage interfaces (`IDBService.js`, `RecipeStore.js`, `localStorageService.js`) have JSDocs 
- [ ] Code coverage
  
##### Time Permitting
- [ ] End-to-end testing

#### Refactoring + Loose Ends
##### IMPORTANT NOTE
> These are moreso tasks and notes that all teams should keep in mind for this last sprint.

##### Why
> Our final project should be in a presentable and tested state. If we have any loose ends that need tying and any neatness to be sorted out, this is the time to do it. 

##### High Priority
- [ ] Ensure functions and variables are `camelCase`.
- [ ] Get rid of commented out, unused code.
- [ ] "Bulletproof" our website. Make sure of the `<noscript>` tag.
- [ ] Create one `app.js` and have all of our dependencies there rather than having multiple `<script>` tags linking to our JS files (Rashi's suggestion).
- [ ] Responsive and clean UX/UI (double check new work done since our sprint review meeting)
  -  For all pages on our website, make sure that all elements on the page have been styled accordingly (see Figma, consult UI design team, or reference the other pages on the site for consistency).
     -  For example, in the last sprint, three input fields are created for each ingredient on the "Create a Recipe" page. However, these components have no styling on them.
  -  Ensure that there are no more duplication errors happening with the search bar or any other features/components.
  -  Ensure all buttons, cards, components, etc. appear on at least 1920x1080 and one mobile view (iPhone SE ok-- the more tested, the better).
  
##### Time Permitting
- [ ] Adding accessibility to our current HTML with [ARIA](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA)?

## Action Items
### Team Wide Assignments
| Done? | Item | Responsible | Due Date |
| ----  | ---- | ----        | ----     |
| NO | Public: Final Video | Everyone | 6/10/2025 |
| NO | Private: Final Video | Everyone | 6/10/2025 |

## Other Notes & Information
N/A
