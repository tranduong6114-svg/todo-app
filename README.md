# Todo App - Fullstack Training Project

A fullstack Todo application built with Vue 3 + Vuex (Frontend) and Laravel + MySQL (Backend).

## Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | Vue 3 (Composition API), Vuex, Vue Router, Axios |
| Backend | Laravel 10, Laravel Sanctum |
| Database | MySQL |
| Local Server | Laragon |

## Project Structure

```
todo-app/
├── backend/          # Laravel API
│   ├── app/
│   │   ├── Http/
│   │   │   ├── Controllers/
│   │   │   ├── Middleware/
│   │   │   └── Requests/
│   │   ├── Models/
│   │   └── Resources/
│   ├── database/
│   │   ├── migrations/
│   │   └── seeders/
│   └── routes/
│       └── api.php
├── frontend/         # Vue 3 SPA
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── router/
│   │   ├── store/
│   │   ├── views/
│   │   └── App.vue
│   └── public/
└── README.md
```

## Features

- User authentication (Login/Register)
- CRUD Categories
- CRUD Tasks with priority and due date
- Filter tasks by category
- Mark tasks as completed

## Getting Started

See individual README files in `backend/` and `frontend/` directories.
