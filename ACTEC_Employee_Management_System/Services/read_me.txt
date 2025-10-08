⚙️ Services/

Description:
This folder contains classes responsible for handling backend logic, database access, and external service integration (such as APIs, authentication, or file storage).
These services act as the bridge between the user interface (Forms) and the data layer (Database or API).

Purpose:

Centralize data operations like database queries, CRUD functions, and API calls.

Separate business logic from UI logic, improving maintainability.

Provide reusable service functions that can be used across multiple forms.

Typical Contents:

File	              Description
ApiService.vb	    | Handles API requests (GET, POST, PUT, DELETE) to remote servers or REST endpoints.
DatabaseService.vb	| Manages database connections, SQL queries, and CRUD operations for local or remote databases.

Best Practices:

Use parameterized queries to prevent SQL injection.

Handle errors gracefully and log them using the Logger from the Utils/ folder.

Keep connection strings and API keys in App.config for security and flexibility.