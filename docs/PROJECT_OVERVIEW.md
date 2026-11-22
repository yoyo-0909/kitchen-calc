# Kitchen Calc — Project Overview

## Purpose

Kitchen Calc is a standalone browser application intended to support common kitchen planning tasks in one place.

## Included workspaces

- **Recipe Scaler:** scales ingredient quantities based on original and desired servings.
- **Recipe Library:** provides recipe browsing and filtering controls.
- **Pantry:** tracks stored ingredients and expiry-related information.
- **Shopping List:** helps collect items needed for shopping.
- **Cooking:** provides cooking-step progress and timer workflows.
- **Converter:** supports kitchen measurement conversion.

## Implementation notes

- The supplied application is contained in `kitchen_calc.html`.
- The app uses HTML, JavaScript, and Tailwind CSS loaded from a CDN.
- Browser capabilities such as local storage and Web Audio are used where implemented in the source.
- The project currently has no required build or package-install step.

## UI preservation requirement

The supplied UI must remain unchanged. Repository improvements, documentation, and code maintenance must not become an excuse to restyle the application. Preserve the existing visual design exactly unless the project owner explicitly changes this requirement.

## Scope note

This document describes the supplied source at a high level. It does not imply the presence of a backend, account system, cloud synchronization, or external recipe API.
