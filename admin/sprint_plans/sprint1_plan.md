# Sprint #1 Plan
## About
- Overarching Goal: Build a starting point and foundation for our project.
- Date range: 5/8/2025 - 5/11/2025
- Stand-up check-in planned for: 5/10 @ ~7:00pm (asynchronous via Slack)
  - **Please try to be done with your work (or at least most of it) by 5/10 @ 7pm.** Please reach out sooner if you need help.

## Tasks
### Overview
| Task | Who |
| ---- | ---- | 
| [CI/CD](#1-cicd) | Samson, Ryan, Minahil, Ashley |
| [Program Flow Diagram](#2-program-flow-diagram) | Kiara, Arlene |
| [UI Development](#3-ui-development) | Chanbin, Patrick, Dorje |
| [Github Issues and Features](#4-github-issues-and-organization) | Kiet, Shash |
| [Floaters + Experiments](#5-floater-experimental-projects) |  Ashley |

### (1) CI/CD
- **DUE** 5/11/2025 (async. check-up on 5/10)
- **Goal**:
  - Research how to build lint rules and how to  implement them into GitHub Actions. See what would be good to include in our linters.
  - The three assignees are just laying the groundwork. Everyone else should help check.
- **What**:
	- [ ] One (1) : enforce 2 pull request reviews (the two reviewers *must* be people who did *not* work on the branch).
	- [ ] Linters
    	- [ ] One (1) : HTML
  	  - [ ] One (1) : CSS
  	  - [ ] One (1) : JS
- **Assignee(s)**:
  - 1: Samson
  - 2: Ryan
  - 3: Minahil
  - Support: Ashley

### (2) Program Flow Diagram
- **Goal**: Create a master diagram to illustrate program flow (i.e. how our users will go through our app). This process was demoed in Lab 4, so refer to that for guidance. This does not need to be perfect, but we should draw the general idea of how our app flows. This will act as a reference for everyone to understand as well that we can always modify as needed.
- **What**:
	- [ ] One (1) : `.drawio.png` flowchart
- **Assignee(s)**:
  - 1: Kiara
  - 2: Arlene

### (3) UI Development
- **Goal**: Develop a UI that we want to use for our app.
- **What**: 
	- [ ] One (1) : Design for Desktop
	- [ ] One (1) : Design for mobile (tablets)
    	- Horizontal orientation
    	- Vertical orientation (small and large scales)
- **Assignee(s)**: 
  - 1: Chanbin
  - 2: Patrick
  - 3: Dorje

### (4) GitHub Issues and Organization
- **Goal**: 
  - Jot down our features as issues in our project repository. This is so we can track what features we have yet to implement or have not  implemented.
  - We want to answer the following questions: How do we want to organize our `.html`, `.css`, and `.js` files? Do we want folders? What should the repository look like?
- **What**:
	- [ ] x number of GitHub issue tickets as necessary (see Miro board or notes from 5/7)
    	- Follow an issue template (create one if needed): Describe the feature, describe why we have it, and maybe assign a priority to them (e.g. high, medium, low) 
	- [ ] One (1) : Outline of repository structure
    	- There's no need to actually push/create folders for now. This can be in plain text. 
- **Assignee(s)**:
  - 1: Kiet
  - 2: Shash

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
  - 1: Ashley (will focus on CI/CD to help the CI/CD team get started)
	
