SpendWise Dashboard Shell
Project Description

SpendWise is a modern financial dashboard designed to help users understand and manage their spending.

This week's project focuses on rebuilding the Budget Tracker layout using modern CSS Grid and Flexbox techniques. The dashboard contains a navigation sidebar, a header, summary information, and six financial category cards.

No JavaScript functionality has been added because the focus of this assignment is the visual structure and responsive CSS layout.

Project Files

index.html – Contains the structure and static content of the SpendWise dashboard.

style.css – Contains the complete visual design, CSS Grid layout, Flexbox layouts, responsive styles, CSS variables, animations, and dark theme.

README.md – Explains the project and the design choices.

Dashboard Structure

The dashboard contains:

Sidebar

The sidebar contains the SpendWise logo and navigation links for:

Dashboard

Expenses

Reports

Budgets

Accounts

Settings

Header

The header contains:

A welcome message

Dashboard overview information

Current month

User profile information

Summary Cards

Three summary cards show:

Total Budget

Total Spent

Remaining Budget

Category Cards

Six category cards display realistic financial information:

Food

Transport

Rent

Entertainment

Savings

Utilities

Each card includes an icon, spending percentage, amount spent, budget amount, and a progress bar.

CSS Grid

CSS Grid is used for the main dashboard structure.

The desktop layout uses:

One column for the sidebar

One flexible column for the main content

CSS Grid is also used for:

Summary cards

The six-category card layout

The category cards are arranged in three columns on larger screens.

Flexbox

Flexbox is used inside the dashboard components.

It is used for:

Sidebar navigation items

Header content

Header actions

Summary cards

Category cards

Card content

Navigation on smaller screens

This allows the individual components to align and distribute their content effectively.

CSS Custom Properties

The application's theme is controlled using CSS variables inside the :root selector.

Important variables include:

--brand-color – Main green brand color

--accent-color – Accent color

--background-color – Main page background

--surface-color – Card and sidebar background

--primary-text – Main text color

--secondary-text – Supporting text color

--border-color – Border color

Using CSS variables makes the color theme consistent and easier to maintain.

Responsive Design

The dashboard is responsive and adapts to smaller screens.

At screen widths below 768px:

The two-column dashboard becomes a single-column layout.

The sidebar moves above the main content.

Navigation items become horizontally scrollable.

Summary cards become a single column.

Category cards become a single column.

Header content adjusts to fit smaller screens.

The layout can be tested using the browser's DevTools Device Toolbar.

Card Micro-interactions

The category cards include subtle micro-interactions.

When a user hovers over a card:

The card moves slightly upward.

A soft shadow appears.

The same effect is available when a user navigates to a card using the keyboard.

The transition lasts 200ms, which is below the required 250ms limit.

Keyboard focus is also made visible using :focus-visible.

Dark Theme

A dark theme has been included as a stretch goal.

The dark theme uses:

@media (prefers-color-scheme: dark)


Only the CSS custom property values are overridden inside this media query.

This allows the dashboard to automatically adapt to the user's operating system's preferred color scheme.

No Absolute Positioning

The dashboard does not use absolute positioning for its page layout.

CSS Grid is responsible for the overall page structure, while Flexbox is used to arrange content inside individual components.

Conclusion

The SpendWise Dashboard Shell provides a clean and responsive foundation for a future financial management application.

The project demonstrates the use of CSS Grid, Flexbox, CSS custom properties, responsive design, micro-interactions, and a dark theme while keeping the interface simple and user-friendly.