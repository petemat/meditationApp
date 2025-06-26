# Meditation Journey - Design & Aesthetics Guide

This document outlines the core design principles and Tailwind CSS classes used in the Meditation Journey application. The goal is to maintain a calm, modern, and immersive aesthetic, primarily achieved through a glassmorphism effect.

## 1. Core Style: Glassmorphism

The signature look of the UI is a semi-transparent, blurred background effect that sits on top of the 3D scene.

**Key Tailwind Classes:**
- `bg-black/20` or `bg-black/40`: A black background with low opacity.
- `backdrop-blur-lg` or `backdrop-blur-xl`: Applies the blur effect to the content behind the element.
- `border border-white/10` or `border-white/20`: A subtle white border to define the element's edges.
- `shadow-lg` or `shadow-2xl`: Adds depth and lifts the element off the background.

**Example (Panel):**
```html
<div class="p-6 bg-black/20 backdrop-blur-lg rounded-2xl border border-white/20 shadow-lg">
  <!-- Content here -->
</div>
```

## 2. Color Palette

The palette is designed to be soothing and minimalist.

- **Primary Background**: The dynamic 3D scene (purple/orange gradient).
- **UI Panel Background**: Semi-transparent black (`bg-black/20`, `bg-black/40`).
- **Primary Text**: Off-white (`text-white/90`).
- **Secondary Text / Icons**: Muted white (`text-white/70`).
- **Accent / Success**: Green (`text-green-400`) for completed items.
- **Hover / Interactive Elements**: Slightly opaque white (`hover:bg-white/10`, `hover:bg-white/15`).

## 3. Typography

- **Font Family**: 'Inter', loaded from Google Fonts.
- **Panel Titles**: `font-bold` or `font-semibold` (e.g., "Courses" header).
- **List Item Titles**: Normal font weight, `text-white/90`.
- **Body Text**: `text-white/80`.
- **Small Text / Labels**: `text-xs`, `text-white/70`.

## 4. UI Component Styling

### Panels & Cards
- **General**: `rounded-2xl` for main containers.
- **Example (`#progress-panel`):** `p-4 bg-black/20 backdrop-blur-lg rounded-2xl border border-white/20 shadow-lg`

### List Items
- **General**: `rounded-md`, subtle background to stand out from the panel.
- **Example (`.course-item`):** `p-2 rounded-md bg-white/5 cursor-pointer hover:bg-white/15`

### Buttons
- **Icon Buttons**: No background, direct icon usage.
- **Example (`#muteButton`):** `<button id="muteButton" class="p-2 rounded-full hover:bg-white/10 transition-colors"><svg>...</svg></button>`

## 5. Layout & Spacing

- **Layout**: Primarily uses Flexbox (`flex`, `justify-between`, `items-center`) for alignment.
- **Padding**: `p-2`, `p-3`, `p-4` are common.
- **Margins**: `mt-2` for spacing between vertical elements.
- **Stacking**: `space-y-1` or `space-y-2` for vertically stacked items inside a container.

By following these guidelines, all new elements will share a consistent and professional look.
