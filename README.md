# RaceDayRepo
## Project Overview
This is the RESTful API backend for the RaceDay system, built with ASP.NET Core Web API, Entity Framework Core (Code-First), and SQL Server. It handles user authentication, role-based access control (Organiser vs. Participant), event management, categories, enrolments, and results.
## Roles
- **Organiser**: Create/edit/delete own events, manage categories/routes, view event enrolments, capture/update/delete results.
- **Participant**: Update profile, view events, enrol in events, cancel own enrolment, view own results.
## CI/CD
A GitHub Actions workflow is configured in `.github/workflows/dotnet-ci.yml`. It automatically builds the project and runs unit tests on every push to the `main` branch.
Successful Test and Build

Successful Workflow

Unlisted YouTube Link: https://youtu.be/mHGXW6nCkp8?si=41TUMSo6qMJ_H-5m
