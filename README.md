# Sippy

**Native iOS Pet Care Platform**

SwiftUI · Kotlin · Spring Boot · PostgreSQL · Google Cloud

*Engineering Showcase · Documentation Only*

---

## Overview

A native iOS pet-care application built with SwiftUI and a Kotlin/Spring Boot backend, featuring cloud infrastructure and secure APIs.

Sippy brings pet profiles, everyday care, reminders, and personal memories into a single mobile experience.

This repository documents selected engineering decisions behind the project. The application and backend source code remain private.

## Key Features

- **Pet Profiles** — Structured pet information, household management, and care-related data.
- **Personal Diary** — Timeline-based entries with calendar navigation and media support.
- **Care & Reminders** — Pet care tracking, scheduling, and reminder management.
- **Interactive Map** — Mapbox-based exploration of pet-friendly places.

## Tech Stack

| Layer | Technologies |
|---|---|
| iOS | Swift, SwiftUI |
| Backend | Kotlin, Spring Boot, REST APIs |
| Database | PostgreSQL, Flyway |
| Authentication | JWT, Spring Security, RBAC |
| Maps | Mapbox |
| Cloud | Google Cloud Run, Cloud Storage |
| Infrastructure | Docker, GitHub Actions |
| Testing | JUnit 5, Testcontainers |

## Engineering Highlights

### Native iOS Architecture

Feature-oriented SwiftUI application with separate presentation, domain, and data responsibilities.

### Backend Design

Kotlin/Spring Boot backend with modular organization, REST endpoints, relational persistence, and household-scoped access controls.

### Cloud Media Storage

Integration with Google Cloud Storage using signed URLs for media uploads and access.

### Continuous Integration & Delivery

GitHub Actions pipeline configured to run backend tests, build Docker images, and deploy to Google Cloud Run.

## System Architecture

The project combines a native iOS client with a Kotlin backend and managed cloud infrastructure.

See [Architecture Documentation](docs/architecture.md) for the high-level system diagram, media upload flow, and CI/CD overview.

## Development Status

**Under active development**

The project includes implemented functionality alongside evolving features and integrations.

This showcase does not imply that all planned functionality is complete or publicly available.

## Source Code & Repository Scope

This is a documentation-only showcase.

The production application, backend source code, private configurations, and deployment credentials are not included.

## Author

**Roman Agadjanyan** — Software Engineer

[GitHub](https://github.com/comebackunreal) · [LinkedIn](https://www.linkedin.com/in/laeslow/)
