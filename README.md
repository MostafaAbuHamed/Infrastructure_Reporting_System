# Infrastructure Reporting System: Graduation Project Snapshot

Final submission snapshot of my graduation project (graded **Excellent**), Egyptian E-Learning University, 2026. Citizens report damaged public infrastructure, authorities review and assign workers, and an AI service classifies the damage from photos and writes the issue description.

> This repository is a frozen snapshot of everything that was submitted. The actively maintained code lives in the repositories linked below.

## Maintained repositories

| Part | Repository |
| ---- | ---------- |
| Backend API (ASP.NET Core 9, Clean Architecture) | [InfrastructureReportingSystem](https://github.com/MostafaAbuHamed/InfrastructureReportingSystem/tree/Dev) |
| AI image-analysis service (FastAPI) | [IRS.AI](https://github.com/MostafaAbuHamed/IRS.AI) |

## What's in this snapshot

| Folder / file | Contents |
| ------------- | -------- |
| `Infrastructure_Reporting_System_Back` | ASP.NET Core 9 API: EF Core, SQL Server, JWT auth, role-based access, xUnit tests, Postman collection |
| `Infrastructure_Reporting_System_Front` | Angular frontend styled with Tailwind CSS |
| `Infrastructure_Reporting_System_AI` | FastAPI microservice with a vision LLM, Dockerfile and GitHub Actions workflow |
| `Infrastructure_Reporting_System_Doc-420.docx` | Project documentation |
| `Infrastructure_Reporting_System_Presentation-420.pptx` | Graduation presentation |

## My role

I was part of the team that built the system, and my main contributions were:

- **Authentication and security:** JWT access and refresh tokens, OTP verification and account lockout
- **AI service:** the FastAPI microservice that classifies damage photos and generates issue descriptions
- **Deployment:** Docker packaging and automated deployment of the AI service with GitHub Actions

## Tech stack

ASP.NET Core 9, Entity Framework Core, SQL Server, JWT, xUnit, Moq, Angular, Tailwind CSS, Python, FastAPI, Docker, GitHub Actions.

## Author

Mostafa Abu-Hamed. [GitHub](https://github.com/MostafaAbuHamed) · [LinkedIn](https://linkedin.com/in/mostafa-abuhamed)
