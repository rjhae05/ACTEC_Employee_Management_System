📂 Controls/

Description:
This folder contains reusable custom user controls or UI components used across different forms in the application. These are modular interface elements built to promote code reuse, consistency, and maintainability.

Purpose:

Encapsulates UI elements that appear on multiple forms (e.g., navigation bar, sidebar, header).

Allows centralized updates — modifying a control here automatically updates all forms that use it.

Helps maintain a clean separation between layout and logic for better scalability.

Typical Contents:

File	               Description
SidebarControl.vb	| A custom sidebar menu for navigation between different application sections.
HeaderControl.vb	| A header or toolbar that displays the application title, user info, or quick actions.

Best Practices:

Keep each control self-contained (handle its own events and visual updates).

Expose custom events or properties for easy integration with forms.

Follow naming conventions like ControlNameControl.vb (e.g., SidebarControl.vb).