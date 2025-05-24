## Full-Stack Todo Ui

A simple task management app to help your organize to your daily to-do lists. Users can Authentication and authorization Add, delete, and mark tasks as complete and imcomplete with ease

## Features

- ➡️ "bootstrap": "directus bootstrap", (The directus bootstrap command is used to initialize the Directus system database and create the initial admin user)

- ➡️ "dbupdate": "directus database migrate:latest", ( Runs directus command database migrate:latest to apply the latest database schema migrations.)

- ➡️ "dbsnapshot": "directus schema snapshot --yes ./db/snapshot.yaml", ( Runs a Directus command that exports the current database schema configuration schema snapshot )

- ➡️ "dbapply": "directus schema apply --yes ./db/snapshot.yaml" (Runs a Directus command that apply to the current database schema)

## Technologies Used

** Backand **

- Node.js
- Directus for The last Headless CMS
- Sqlite for Database

## 1. Clone the repo

- ➡️ Backand repo git clone (https://github.com/gopalsarkar-dev/fullstack_todo_server.git)

- ➡️ Frontend repo git clone (https://github.com/gopalsarkar-dev/fullstack_todo_ui.git
  )

## Getting Started

npm install

#or

bun install

Run the development server:

npm start

#or

yarn start

#or

pnpm start

#or

bun start
