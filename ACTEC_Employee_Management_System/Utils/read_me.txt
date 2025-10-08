⚙️ Utils/

Description:
The Utils/ (short for Utilities) folder contains helper classes, error handlers, and constant definitions used throughout the application.
These files provide reusable, generic, and non-domain-specific functions that simplify tasks such as logging, error management, string formatting, and constant declarations.

Purpose:

Centralize all common functions and utility methods to avoid code duplication.

Improve maintainability and readability by keeping business logic clean.

Provide a consistent way to handle errors, log activities, and manage constants.

Typical Contents:

File						Description
ErrorHandler.vb			| Handles runtime errors and exceptions in a unified way (e.g., showing user-friendly error messages).
Logger.vb				|  Records application logs such as errors, warnings, and activities into a text file or database.
Constants.vb (optional)	| Stores fixed values like API URLs, default settings, or application messages.

Best Practices:

Keep utility functions static/shared (Public Shared) to allow easy global access.

Ensure error handlers do not expose sensitive information.

Use structured logging with timestamps for easier debugging.

Keep constants centralized to make configuration changes easier.