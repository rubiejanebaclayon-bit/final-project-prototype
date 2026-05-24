# Project Code & UI Style Guide

This document establishes the design tokens and implementation code standards for the Group 6 RM Dormitel engineering project workspace.

## 1. UI & Visual Design Tokens
* **Primary Branding Color:** Maroon Accent (`#A34343` / Hover: `#8A3535`) used for main submission prompts and primary buttons.
* **Secondary Action Accent:** Soft Sky Blue (`#9AD0EC` / Hover: `#7EC2E7`) reserved for background navigation toggles and home links.
* **Typography Base:** Standard Tailwind Inter/Sans-Serif stack (`font-sans antialiased`). Base descriptions run at `text-xs` (12px) and `text-sm` (14px) with uppercase text indicators scaled to `text-[10px]` for scannable forms.

## 2. Directory & Architecture Structure
* **Root Pages:** Static files (`index.html`, `view-rooms.html`, `booking.html`, `admin_login.html`, `admin-dashboard.html`) reside flat in the repository root for immediate GitHub Pages deployment.
* **Assets:** Graphic backgrounds and visual references (`bookingbg.png`) are managed using clean local string sources.

## 3. Commit Message Conventions
All commit records must comply with semantic syntax prefixes to ensure clean automation logs:
* `Feat(...)` — Implementing brand-new layout views or features.
* `Fix(...)` — Resolution steps for bugs or UI elements (e.g., `Fix(booking): Enforce strict 11-digit numeric validation`).
* `Docs(...)` — Creating or altering markdown logs, guidelines, or files.

## 4. Development Best Practices
* Enforce native HTML5 parameters (`required`, `pattern`, `maxlength`) on interactive data entries to avoid raw data leakage.
* Never hardcode sensitive parameters or administrative access bypass links directly inside client template configurations.