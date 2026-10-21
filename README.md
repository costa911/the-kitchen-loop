<p align="center">
  <img src="thekitchenloop.png" alt="The Kitchen Loop logo" width="180" />
</p>

# The Kitchen Loop

**A recipe management and meal-planning application built to solve a real household problem.**

The Kitchen Loop started as a simple way to organise family recipes and has grown into a practical web application for meal planning, shopping-list generation, cooking history and household analytics.

---

## Project Links

- **Live app:** [The Kitchen Loop](https://costa911.github.io/the-kitchen-loop/)
- **Frontend repo:** [costa911/the-kitchen-loop](https://github.com/costa911/the-kitchen-loop)
- **Status:** Active development
- **Type:** Personal/family application with a future Community Edition planned

---

## Overview

The goal of The Kitchen Loop is to reduce the repetitive work involved in deciding:

- what to cook
- what ingredients to buy
- how to turn recipes into a practical two-week plan

It combines recipe storage, planning, shopping and usage history into one application.

---

## Features

- **Recipe management**  
  Store, search, categorise and maintain recipes.

- **Fortnightly meal planning**  
  Generate two-week plans with dinners, lunch rotations and desserts.

- **Shopping-list generation**  
  Automatically build ingredient lists from selected meals.

- **Cooking history**  
  Track what has been cooked and when.

- **Household analytics**  
  Review recipe usage, trends, cooking streaks and preferences.

- **Custom shopping lists**  
  Create one-off lists from selected recipes.

- **Export and sharing**  
  Print meal plans and share shopping lists.

---

## Screenshots

> Screenshots to be added as the project documentation is updated.

Suggested future screenshots:
- Recipe library
- Fortnightly planner
- Shopping list
- Stats dashboard
- Admin / management view

---

## Technology Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, vanilla JavaScript |
| Hosting | GitHub Pages |
| API | Cloudflare Workers |
| Data exchange | JSON over HTTP |
| Persistence | GitHub-based JSON storage (current implementation) |
| Activity/session handling | Cloudflare Workers KV |
| Version control | Git & GitHub |

---

## Architecture

The current version consists of:

1. **A static frontend** hosted on GitHub Pages
2. **A Cloudflare Worker API** handling authentication and data operations
3. **JSON-based persistence** for recipe, plan and activity data

> The architecture is currently under active review as part of ongoing security and storage improvements.

---

## Project Status

**Active development — documentation, architecture and security improvements in progress.**

This application is currently used as a controlled personal/family project.

A future **Community Edition** is planned, with the aim of offering a downloadable or local-first version that users can run for themselves without requiring centrally managed household data.

---

## Roadmap

### Completed
- Recipe management
- Fortnightly planning
- Shopping lists
- Cooking history
- Analytics dashboard
- API-backed persistence
- Household separation

### In progress
- Security review and remediation
- Documentation improvements
- Architecture review
- Portfolio presentation improvements

### Planned
- Community Edition
- Improved data portability
- Better testing
- Cleaner frontend structure
- Storage improvements

---

## What I Learned

The Kitchen Loop has been one of my most useful personal development projects because it goes beyond building isolated features.

It has given me hands-on experience in:

- designing a browser-based application
- building API-backed functionality
- handling state and persistence
- turning a real-life problem into a working product
- reviewing trade-offs in architecture and security
- improving software iteratively based on real use

---

## Notes

This README will continue to evolve as the project improves.

The aim is for The Kitchen Loop to become both:
- a genuinely useful application, and
- a strong portfolio example of practical product thinking, frontend development and iterative technical improvement.
