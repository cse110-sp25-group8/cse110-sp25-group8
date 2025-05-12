# Sprint #2 Plan
## About
- Overarching Goal: Split teams to build the foundation for our website. Functionality is not important right now. Everyone is working on split files for now for modularity, but we do have plans to refactor as needed.
- Date range: 05/12/2025 - 05/18/2025
- Stand-up check-in planned for: 05/16 @ 5:00 - 6:00 PM via Zoom. Your teams don't need to be 100% done, but please try to be around 70% of the way there.
  - Daily stand-ups will be asynchronous as usual... expect them to be daily for this week (5/12 - 5/18) as we're expecting a stand-up related team assignment due this week. We'll probably send out a stand-up message in the evenings so people have time earlier in the day to work.

## Housekeeping
- Review UI design together
- Review file structure together
- Decide on our daily stand-up methods
  - ~~For this week, maybe we do our sprint review meeting on Friday?~~ Resolved. See above.
    - For Chanbin, before 6:00pm as I am going to Padres baseball game

⚠️ **This is TENTATIVE.** Since our sprint planning meetings are on Monday, we might need to adjust plans based on what's due for our team this week.

## Tasks
### Overview
| Task | Who |
| ---- | ---- |
| [Main page](#1-main-page-and-research) | Samson, Dorje, Arlene | 
| [View Recipe page](#2-adding-a-recipe-page) | Mina, Kiet, Kiara | 
| [Add a Recipe page](#3-view-recipe-page) | Shash, Patrick, Ryan | 
| [Shadow DOM for Cards](#4-shadow-dom-for-recipe-cards) | Chanbin, Ashley | 

### (1) Main Page and Research
- **Goal**: 
  - This is the main page where we show the recipes. Essentially, this is the user's "digital cookbook" where they can view and look through all of their recipes they've added. This team does not need to handle the creation of cards, but they should leave an area where the cards can be inserted.
- **What**:
    - [ ] `index.html` (home page)
    - [ ] `index.css`
    - [ ] `index.js` (this can be blank for now)
    - Research (Markdown or some sort of PDF would be nice):
      - Look into how we might implement a search for our recipes.
      - Look into how to do the filters... should we have separate dropdowns or an all-in-one one?
- **Assignee(s)**:
  - 1: Samson
  - 2: Dorje
  - 3: Arlene

### (2) Adding a Recipe Page
- **Goal**: 
  - This is for the user to implement their own recipe to add to their "cookbook." Later, this should be stored as JSON. 
- **What**:
  - [ ] `detail.html` (view recipe information)
  - [ ] `detail.css`
  - [ ] `detail.js` (this can be blank for now)
- **Assignee(s)**:
  - 1: Mina
  - 2: Kiet
  - 3: Kiara

### (3) View Recipe Page
- **Goal**: 
  - The cards on the main page will not display all of the recipe's details, so we'll have them on a separate page. The view recipe page should be where clicking on a recipe card redirects.
- **What**:
  - [ ] `adding.html` (page to create a recipe)
    - This has forms for user input. This does *not* need to be functioning.
  - [ ] `adding.css`
  - [ ] `adding.js` (this can be blank for now).
    - [ ] Time permitting, work on the timer... if time is short, just work on the HTML and CSS for it.
- **Assignee(s)**:
  - 1: Shash
  - 2: Patrick
  - 3: Ryan

### (4) Shadow DOM for Recipe Cards
- **Goal**: 
  - Like in Lab 6, we might want to utilize the Shadow DOM to implement our recipe cards. Because card implementation will be dependent on the other pages being done, we might want to create this feature in isolation (like a module) that we can easily add to our project once ready.
- **What**:
  - [ ] `shadow.html`?
  - [ ] `shadow.css`?
  - [ ] `shadow.js`?
- **Assignee(s)**:
  - 1: Ashley
  - 2: Chanbin
 
### Plan for the structure
```
final-project/
-- index.html
-- detail.html
-- adding.html
-- css/
   --- index.css
   --- detail.css
   --- adding.css
-- scripts/
   --- index.js
   --- detail.js
   --- adding.js
-- data/
   --- items.json
-- assets/
   --- images/
```
