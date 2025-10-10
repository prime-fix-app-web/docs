# Navigation and Routing Guide

Routing defines how users navigate through the application and how views are rendered based on the URL.

- **Route Definitions:**  
  Each module has its own route file (e.g., `tracking.routes.js`, `iam-routes.js`) specifying available paths and associated views. These are combined in the global router (`router.js`).

- **Route Guards:**  
  Guards (`auth.guard.js`) enforce authentication and role-based access, ensuring users only see pages they are authorized for.

- **View Organization:**  
  Views are grouped by user role and feature, making navigation intuitive. For example, owner and workshop layouts and sidebars provide tailored navigation experiences.

- **Error Handling:**  
  The application gracefully handles 404 and error pages using components like `page-not-found.vue`.

- **Performance:**  
  Use lazy loading for route components to improve initial load times. Nested routes help manage complex layouts and workflows.

**Best Practices:**  
- Keep navigation consistent across user roles.
- Document route structure and access rules.
- Use named routes for easier navigation and maintenance.
- Test navigation flows for all user roles and edge cases.

---