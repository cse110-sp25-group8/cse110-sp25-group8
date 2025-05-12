# Sprint #2 Plan
## About
- Overarching Goal: Split teams to build the foundation for our website.
- Date range: 05/12/2025 - 05/18/2025
- Stand-up check-in planned for: 05/16 @ 05:00 - 06:00 PM (please try to be around 70% done)

## Housekeeping
- Review UI design together
- Review file structure together
- Decide on our daily stand-up methods
  - For this week, maybe we do our sprint review meeting on Friday?
    - For Chanbin, before 6:00pm as I am going to Padres baseball game

⚠️ **This is TENTATIVE.** Since our sprint planning meetings are on Monday, we might need to adjust plans based on what's due for our team this week.

## Tasks
### Overview
| Task | Who |
| ---- | ---- |
| [Main page](#1-main-page) | ... | 
| [View Recipe page](#2-view-recipe-page) | ... | 
| [Add a Recipe page](#3-adding-a-recipe-page) | ... | 
| [Shadow DOM for Cards](#4-shadow-dom-for-recipe-cards) | ... | 

### (1) Main Page and Research
- **Goal**: 
  - This is the main page where we show the recipes. Just focus 
- **What**:
    - [ ] `index.html` (home page)
    - [ ] `index.css`
    - [ ] `index.js` (this can be blank for now)
    - Research:
      - Look into how we might implement a search for our recipes.
      - Look into how to do the filters... should we have separate dropdowns or an all-in-one one?
    
- **Assignee(s)**:
  - 1: Samson
  - 2: Dorje
  - 3: Arlene

### (2) Adding a Recipe Page
- **Goal**: 
  - The view recipe page should where clicking on a recipe card redirects.
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
  - T
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
  - Like in Lab 6, we might want to utilize the Shadow DOM to implement our recipe cards.
- **What**:
  - [ ] ...
- **Assignee(s)**:
  - 1: Ashley?
  - 2: Chanbin?
 
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
