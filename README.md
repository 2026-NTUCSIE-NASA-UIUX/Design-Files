# UI Design System Documentation

## 1. Overview

This design system aims to provide a consistent UI/UX across multiple internal services, including:

- CSpace (Room Reservation System)
- New Printing System
- Mail Subscription System

### Goals

- Ensure visual consistency
- Improve development efficiency
- Provide reusable UI components
- Standardize user experience

---

## 2. Design Tokens

### 2.1 Color

#### Brand Colors (Can be freely decided by app teams. We use teal for demo.)

| Token | Usage |
|------|------|
| Brand-500 | Primary actions |
| Brand-100 | background |

#### Neutral Colors

| Token | Usage |
|------|------|
| Neutral-900 | Main text |
| Neutral-800 | Secondary text |
| Neutral-600 | Tertiary text |

#### Semantic Colors

| Type | Color |
|------|------|
| Success | Green |
| Warning | Orange |
| Error | Red |

---

### 2.2 Typography

| Type | Size | Usage |
|------|------|------|
| Heading | 16–64px | Page titles |
| Body | 10–20px | Content |

---

### 2.3 Spacing

#### Spacing Scale

The spacing system is based on a consistent scale derived from the base unit.

| Token | Value | Usage |
|------|------|------|
| xs | 4px | Tight spacing, small gaps |
| sm | 8px | Default small spacing |
| md | 16px | Standard layout spacing |
| lg | 32px | Section spacing |
| xl | 64px | Large layout separation |

### 2.4 Opacity
| Token | Value |
|------|------|
| low | 10% |
| md | 10% |
| high | 90% |

---

## 3. Components

### 3.1 Button

#### Variants

- `primary` → main actions (submit, create)
- `secondary` → secondary actions
- `danger` → destructive actions (delete)
- `ghost` → low emphasis actions (filter, toolbar)

#### Sizes

- `S`
- `M`
- `L`

#### States

- default
- pressed
- hover
- disabled

#### Usage Guidelines

- Use **primary** for main actions
- Use **danger** for destructive actions
- Avoid overusing primary buttons

---

### 3.2 Card

Used as a container to group related content.

#### Usage

- List items
- Detail sections
- Dashboard widgets

---

### 3.3 Badge

Used to display status or metadata.

#### Examples

- Notification
- Status: `Pending`, `Approved`, `Rejected`
- Category labels

#### Rules

- Should not be clickable
- Should not replace main content

---

### 3.4 Input

Used for user input.

#### UX Rules

- Always include labels
- Show error messages clearly

---

## 4. Patterns

### 4.1 Navbar

#### Desktop

- Horizontal layout
- All menu items visible

### 4.2 Page Header

#### Structure

- Title (left)
- Actions (right)

#### Example
[ Page Title ] [ Search ][ Filter ][ + Add ]

### 4.3 List Pattern

#### Types

- Table list
- Card list (used in CSpace)

#### Example Structure

---
| Group Header |
|------|
| List Item |
| List Item |
...
## 5. Templates

### 5.1 List Page

Includes:

- PageHeader
- Filter
- List (grouped or table)

---

### 5.2 Form Page

Includes:

- Input fields
- Validation
- Confirm / Cancel buttons

---

### 5.3 Detail Page

Includes:

- Card sections
- Metadata (Badge)
- Action buttons

---

## 6. Figma Usage Guide

### Component Usage

- Use variants instead of duplicating components
- Follow predefined spacing and layout

### Page Construction

- Use Templates as reference
- Combine components according to Patterns

---

## 7. Future Work
- Add responsive behavior (Mobile)
- Implement React component library
- Integrate with private npm registry
- Add CI/CD pipeline

---

