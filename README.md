<div align="center">

# MYREM FLOW

### Business Management System

Una plataforma web para gestionar pequeños negocios desde un solo lugar.

[Live Demo](https://myrem-droid.github.io/myrem-flow/)

**Built by MYREM.DEV**

---

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

</div>

---

## Overview

MYREM FLOW is a web-based business management system designed to help small businesses organize their daily operations.

The platform provides a centralized workspace for managing appointments, clients, services, and business information.

It combines a clean interface with cloud-based data persistence through Supabase.

## Features

### Dashboard
- Business overview.
- Key operational statistics.
- Monthly appointment visualization.
- Upcoming appointments.
- Recent activity.

### Appointment Management
- Create and manage appointments.
- Assign clients and services.
- Update appointment statuses.
- Organize scheduled activities.

### Client Management
- Register new clients.
- Edit client information.
- Search and manage client records.
- Keep business contacts organized.

### Service Management
- Create and edit services.
- Set prices and durations.
- Organize available business services.

### Authentication
- User registration.
- Secure login through Supabase Auth.
- Individual user sessions.
- Account logout.

### Cloud Database
- Supabase integration.
- Persistent data storage.
- Business-specific data organization.
- Real-time application connectivity.

### Additional Features
- Business configuration.
- Currency selection.
- JSON data export.
- Responsive interface.
- Notification system.

---

## Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Interface and responsive design |
| JavaScript | Application logic |
| Supabase | Authentication and database |
| PostgreSQL | Data storage |

---

## Architecture

MYREM FLOW uses a client-side architecture connected to Supabase.

The application communicates with the backend through the Supabase JavaScript SDK.

Main database entities:

- `profiles`
- `businesses`
- `clients`
- `services`
- `appointments`

Each business maintains its own operational records.

Database access should be protected through properly configured Row Level Security (RLS) policies.

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/myrem-droid/myrem-flow.git
