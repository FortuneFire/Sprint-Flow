# SprintFlow 🚀

**Tagline:** *Plan, balance, and track your team’s sprints effortlessly.*

![SprintFlow Logo](./assets/logo.png)  

SprintFlow is a modern Angular application designed to help teams plan agile sprints by assigning members to balanced teams based on capacity and role. With a polished Angular Material UI, SCSS styling, and reusable component architecture, SprintFlow demonstrates professional front-end development skills and scalable design patterns.

---

## Features

- **Team Management**
  - Add, edit, and remove team members
  - Assign roles (Frontend, Backend, QA, Design)
  - Set individual capacity (hours per sprint)

- **Task Management**
  - Add and estimate sprint tasks
  - Assign tasks to teams

- **Sprint Planning**
  - Configure sprint name, duration, and number of teams
  - Auto-generate balanced teams based on capacity and roles
  - Track total capacity per team

- **Drag & Drop**
  - Reorder members within teams
  - Move members between teams

- **Persistence**
  - Save sprint data to localStorage for future reference

- **Responsive Angular Material UI**
  - Modern cards, forms, buttons, tables, and snackbars
  - Themeable SCSS variables for easy customization

---

## Tech Stack

- Angular 17  
- Angular Material  
- SCSS (Sass)  
- TypeScript  
- RxJS  
- LocalStorage for data persistence  

---

## Project Structure

src/
├── app/
│ ├── core/
│ │ ├── models/ # Member, Team, Task, Sprint interfaces
│ │ ├── services/ # SprintPlannerService, StorageService
│ │ └── core.module.ts
│ ├── features/
│ │ └── sprint-planner/
│ │ ├── sprint-planner.component.ts
│ │ ├── components/
│ │ │ ├── member-form/
│ │ │ ├── task-form/
│ │ │ ├── sprint-settings/
│ │ │ ├── team-list/
│ │ │ └── team-card/
│ │ └── sprint-planner.module.ts
│ └── shared/
│ ├── components/ # Buttons, inputs
│ ├── pipes/
│ └── directives/
└── assets/
└── logo.png


---

## Screenshots

![Team Card Example](./assets/screenshot-team-card.png)
![Sprint Settings Form](./assets/screenshot-sprint-settings.png)
![Member Form Example](./assets/screenshot-member-form.png)

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/sprint-flow.git
cd sprint-flow
Install dependencies:

npm install


Run the development server:

ng serve


Open the app in your browser:

http://localhost:4200

Usage

Add members using the Member Form (name, role, capacity).

Configure sprint settings (name, duration, number of teams).

Add tasks using the Task Form.

Generate teams with Generate Teams button.

Reorder members or move between teams using drag & drop.

Save sprint to localStorage for later reference.

