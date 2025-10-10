# Documentation of Main Application Components

Components are the building blocks of the user interface. In this project, components are organized by feature and shared usage to promote reusability and maintainability.

- **Shared Components (`shared/presentation/components/`)**:  
  These include elements like `button-logout.vue`, `language-switcher.vue`, and layout components for different user roles (`layout-owner.vue`, `layout-workshop.vue`). Shared components are designed to be used across multiple modules, ensuring consistency in look and behavior.

- **Feature-Specific Components (`<feature>/presentation/components/`)**:  
  Each module (e.g., `maintenance-tracking`, `iam`) contains its own set of components tailored to its functionality. For example, `progress-bar.vue` and `state-error.vue` in `maintenance-tracking` help visualize maintenance progress and error states.

- **Views (`<feature>/presentation/views/`)**:  
  Views represent full pages or screens, such as `login.vue`, `track-vehicle.vue`, and `home-owner.vue`. They often compose several components and handle routing logic.

**Best Practices:**  
- Each component should have a single responsibility and a clear, descriptive name.
- Complex views should be split into smaller, manageable components.
- Use props and events for communication between components.
- Document components with comments and usage examples.

---