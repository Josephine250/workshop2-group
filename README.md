# Tailwind Component Library Challenge

A responsive component library built with HTML and Tailwind CSS.

## Components
- Primary, secondary, and outline buttons
- Hover, keyboard-focus, and disabled button states
- Profile card and product card
- Success, warning, error, and information alerts
- Reusable component classes using `@apply`

## Requirements
- Node.js and npm
- Internet connection for installing packages

## Run locally
1. Open this project folder in your terminal.
2. Install dependencies:

   ```bash
   npm install
   ```

3. Build the Tailwind stylesheet:

   ```bash
   npm run build
   ```

4. Open `index.html` using VS Code Live Server.

To rebuild the stylesheet automatically while editing, run `npm run dev` in a terminal and leave it running.

## Design trade-off
Utility classes provide flexibility for one-off designs. Reusable classes created with `@apply` reduce repetition for components used repeatedly. This project uses reusable classes for buttons, cards, and alerts to improve consistency and maintainability.

## Group members
- Add each group member's full name here before submission.
