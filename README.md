
## 🚀 Project Structure

- **api/**
  Contains code for interacting with backend services or external APIs. This can include models, services, and request/response logic.

- **assets/**
  Holds static assets like images, fonts, and other media files used in the project.

- **components/**
  Contains reusable UI components for the application. These components are typically used across multiple pages or features. This folder is further organised into folders that logically groups all the relevant components.

- **config/**
  Contains configuration files and settings for the project. This might include environment variables, API endpoints, and global constants.

- **content/**
  Houses static content, like markdown files or other resources that represent content for the site.

- **layouts/**
  Includes layout components used to define the structure of pages or templates for reusable page structures.

- **libraries/**
  Contains third-party libraries or custom-built libraries that can be reused throughout the project.

- **middlewares/**
  Holds middleware functions for server-side processing or client-side logic that intercepts certain actions.

- **pages/**
  Contains individual page components for the site. These typically represent routes or top-level components in the application.

- **styles/**
  Contains global stylesheets, component-specific styles, or other style-related assets like CSS or SASS files.

- **types/**
  Stores TypeScript type definitions and interfaces. These are used to enforce type safety and define data structures throughout the project.

- **utilities/**
  Contains utility functions and helper methods used throughout the project. These can include common operations, data processing, or shared logic.

## TO:DO: 
- Configure Linter, as per project needs.
- Configure prettier so the code format works everywhere the same, as per the deal between developers.
- Potentially add more folders if we use react, such as hooks and context.
- Potentially add the "scripts" folder, if we have some custom scripts and integrations.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |
