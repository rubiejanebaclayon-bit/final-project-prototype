# Project Code & UI Style Guide

This document establishes the design tokens and implementation code standards for the Group 6 RM Dormitel engineering project workspace.

## 1. Naming Conventions
* **Variables:** `camelCase` (e.g., `bookingStatus`)
* **Functions / Methods:** `camelCase` (e.g., `verifyPayment()`)
* **Classes:** `PascalCase` (e.g., `bookingController`)
* **Files:** `kebab-case` (e.g., `booking-form.php`)
* **Constants:** `UPPER-SNAKE-CASE` (e.g., `MAX_ROOMS`)
* **Database Tables / Fields:** `snake_case` (e.g., `booking_id`)

## 2. Formatting Rules
* **Indentation:** 4 spaces (use spaces only)
* **Line Length Limit:** Maximum 100 characters
* **Brace Style:** Opening brace on the same line
* **Blank Lines:** One blank line between functions
* **Max Function Length:** Maximum 50 lines

## 3. Commenting Standards
* **File/Module Header:** Include project name and purpose
* **Function/Method Doc:** Add a short description for important functions
* **Inline Comments:** Use only for complex logic
* **TODO Format:** `// TODO: description`
* **Language:** English

## 4. Branch Naming Strategy
* **Feature Branch:** `feature/<short-desc>` (e.g., `feature/booking-module`)
* **Bug Fix Branch:** `fix/<short-desc>` (e.g., `fix/login-error`)
* **Hotfix Branch:** `hotfix/<short-desc>` (e.g., `hotfix/payment-upload`)
* **Release Branch:** `release/<version>` (e.g., `release/v1.0`)

## 5. Commit Message Format
All commit records must strictly comply with semantic syntax prefixes using lowercase styling:
* `<type>(<scope>): <short description>`
* *Example:* `feat(auth): add password reset flow`

### Allowed Types:
* `feat` — Adding a new feature
* `fix` — Fixing bugs/errors
* `docs` — Documentation changes
* `style` — UI/design formatting changes
* `refactor` — Improving code structure
* `test` — Adding/testing functions
* `chore` — Minor maintenance tasks

## 6. Sample Repo Commits
1. `feat(auth): add admin login system` — Baclayon
2. `feat(booking): create booking form` — Mernilo
3. `fix(payment): resolve image upload issue` — Orajay
4. `style(ui): improve landing page layout` — Pandita
5. `docs(readme): update installation guide` — Ramos