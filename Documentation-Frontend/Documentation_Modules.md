
# Guide to Module Structure and Implemented Services

The project follows a modular architecture inspired by Domain Driven Design (DDD), which separates concerns and improves scalability.

- **Module Structure:**  
  Each feature (e.g., `auto-repair-catalog`, `iam`, `maintenance-tracking`) is organized into:
  - `application/`: Contains business logic, such as stores for state management.
  - `domain/model/`: Defines domain entities and models, representing core business objects.
  - `infrastructure/`: Handles API integrations, data persistence, and service logic. Assemblers transform data between layers.
  - `presentation/`: UI components, views, and route definitions.

- **Shared Services (`shared/infrastructure/`)**:  
  Common services like HTTP configuration (`base-api-config.js`), API base classes (`base-api.js`), endpoints, guards (`auth.guard.js`), and interceptors (`auth.interceptor.js`) are centralized for reuse.

- **Internationalization (`locales/`)**:  
  Language files (`en.json`, `es.json`) and configuration (`i18n.js`) enable multi-language support.

**Best Practices:**  
- Keep files focused and avoid deep nesting.
- Use index files for easier imports.
- Document services and APIs for maintainability.
- Centralize shared logic to avoid duplication.

---