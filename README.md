# MedicaCare — Medical Booking App

A small React medical appointment booking application built for practicing React, React Router, Zustand, Axios, React Hook Form, and REST API CRUD operations.

## Features

- Doctors list from REST API using Axios
- Search by doctor name with a controlled input
- Specialty filtering
- Loading, error, and no-results states
- Dynamic doctor details route: `/doctors/:id`
- Appointment Create / Read / Update / Delete
- React Hook Form validation
- Zustand global store for favorites, profile, and theme
- `useRef` uncontrolled-input example
- Responsive Bootstrap UI
- Toast-style success messages using page feedback alerts
- 404 page
- Dark/light theme bonus
- Favorite doctors bonus

## Technologies

- React + Vite
- React Router
- Axios
- Zustand
- React Hook Form
- Bootstrap 5
- json-server

## Run the project

### 1. Install dependencies

```bash
npm install
```

### 2. Start the API

Open terminal 1:

```bash
npm run api
```

The API runs at:

```text
http://localhost:3001
```

### 3. Start React

Open terminal 2:

```bash
npm run dev
```

Open the Vite URL shown in the terminal.

## API endpoints

- `GET /doctors`
- `GET /doctors/:id`
- `GET /appointments`
- `POST /appointments`
- `PUT /appointments/:id`
- `DELETE /appointments/:id`

## Suggested Git commits

```text
chore: create React medical booking app
feat: add routing and shared layout
feat: add doctors API and doctor cards
feat: add doctor search and specialty filter
feat: add doctor details page
feat: add booking form validation
feat: add appointment CRUD
feat: add Zustand store
feat: add profile and useRef example
style: polish responsive medical UI
fix: handle loading and API errors
docs: add project README
```

## Important deployment note

The included `json-server` is local. A frontend deployed to Vercel/Netlify cannot normally call your local `localhost:3001`.

For a fully working public deployment, replace the local API with a reachable hosted API such as Retool, Supabase, or another approved REST API.