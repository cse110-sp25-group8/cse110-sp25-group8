# Sprint #1 Plan
## About
- Overarching Goal: Build a starting point and foundation for our project.
- Date range: 5/8/2025 - 5/10/2025
- Stand-up check-in planned for: 5/10 @ ~7:00pm (asynchronous via Slack)
  - **Please try to be done with your work (or at least most of it) by 5/10 @ 7pm.** Reach out sooner if you need help.

## Tasks
### Overview
| Task | Who |
| ---- | ---- | 
| [HTML Skeletons](#1-html-skeletons) |  |
| [Program Flow Diagram](#2-program-flow-diagram) |  |
| [Github Issues and Features](#3-github-issues-and-features) |  |
| [Linter](#4-linter) |  | 
| [Floaters + Experiments](#5-floaters-experimental-projects) |  |

### (1) CI/CD
- **DUE** 5/11/2025 (async. check-up on 5/10)
- **Goal**:
  - We've established some general rules on how our JavaScript code should be structured at least. Research how to build lint rules and how to  implement them into GitHub Actions. See (notes) for what we agreed on to include in our JS linter.
  - The three assignees are just laying the groundwork. Everyone else should help check.
- **What**:
	- [ ] One (1) : linter `.json` file added to the project repo's Actions
	- [ ] One (1) : enforce 2 pull request reviews (the two reviewers *must* be people who did *not* work on the branch).
- **Assignee(s)**:
  - 1:
  - 2:
  - 3:

### (2) Program Flow Diagram
- **Goal**: Create a master diagram to illustrate program flow (i.e. how our users will go through our app). This process was demoed in Lab 4, so refer to that for guidance. This does not need to be perfect, but we should draw the general idea of how our app flows. This will act as a reference for everyone to understand as well that we can always modify as needed.
- **What**:
	- [ ] One (1) : `.drawio.png` flowchart
- **Assignee(s)**:
  - 1:
  - 2:

### (3) UI Development
- **Goal**: Finalize a UI that we want to use for
- **What**: 
	- [ ] One (1) : Design for Desktop
	- [ ] One (1) : Design for mobile (tablets)
    	- Horizontal orientation
    	- Vertical orientation (small and large scales)
- **Assignee(s)**: 
  - 1:
  - 2:
  - 3:

### (4) GitHub Issues and Organization
- **Goal**: 
  - Jot down our features as issues in our project repository. This is so we can track what features we have yet to implement or have not  implemented.
  - We want to answer the following questions: How do we want to organize our `.html`, `.css`, and `.js` files? Do we want folders? What should the repository look like?
- **What**:
	- [ ] x number of GitHub issue tickets as necessary (see Miro board or notes from 5/7)
    	- Follow an issue template: Describe the feature, describe why we have it, and maybe assign a priority to them (e.g. high, medium, low) 
	- [ ] One (1) : Outline of repository structure
    	- There's no need to actually push/create folders for now. This can be in plain text. 
- **Assignee(s)**:
  - 1:
  - 2:

### (5) Floater: Experimental Projects
- **Goal**: 
  - We ideally want to use JSON files (schema.org Recipe scheme) so that we're not reinventing the wheel.
  - We want to have some way of storing recipes locally. We have two possible options for storage: localStorage vs IndexedDB, so let's answer the question, "Which one is easier to implement and best fits our needs?" 
  - **This is not a high priority task:** if other teams need help, that should take priority (hence the term "floaters"). Otherwise, these experiments will be beneficial for us later on in the project.
- **What**:
	- [ ] One (1) : experiment with JSON-LD formatting (see [schema here](https://schema.org/Recipe)).
    	- What fields do we want or not want to use? (Create a priority of the ones listed on schema's website e.g. "High/Required" or "Medium/Would be nice" or "Low/Not necessary for our project").
    	- Ashley has an exmaple in `#recipe-research` you can play around with that lets you download a JSON file based on your input and load JSON files.
	- [ ] One (1) : experiment with IndexedDB
	- [ ] One (1) : experiment with localStorage
- **Assignee(s)**:
  - 1:
