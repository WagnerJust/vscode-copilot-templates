---
## 📋 Project Onboarding Questions

### **Category 1: High-Level Project Overview**
*This sets the overall context for the project.*

1.  **Project Identity:** What is the name of this project and what is its primary purpose?
2.  **Tech Stack:** What are the main technologies, frameworks, and languages used? (e.g., Next.js, SvelteKit, Go, Rust, Ruby on Rails, etc.)

***

### **Category 2: Development Environment & Workflow**
*This tells me how to run the project and execute commands.*

3.  **Setup & Execution:** What are the exact commands to install dependencies and run the project in development mode?
4.  **Containerization:** Does the project use **Docker** or any other containerization for development? If so, how are commands run?
5.  **Package Management:** What package managers are used? (e.g., `npm`, `yarn`, `pip`, `poetry`, `bundle`).
6.  **Virtual Environments:** If applicable, is there a virtual environment (like for Python or Ruby)? If so, how is it managed?

***

### **Category 3: Project Architecture & Structure**
*This helps me understand the layout and design patterns.*

7.  **Directory Structure:** How is the codebase organized? Is it a monorepo, a standard framework structure (like Next.js), or something custom?
8.  **Architectural Patterns:** Are there established architectural patterns I must follow? (e.g., specific data fetching methods, a service layer, state management patterns, or dependency injection).
9.  **Key Libraries:** Are there any core libraries I should know about for specific tasks (e.g., `TanStack Query` for data fetching, an ORM, a component library like `Shadcn/UI`)?
10. **Documentation:** Where can I find the primary source of truth for documentation, such as API specs (Swagger/OpenAPI) or component libraries (Storybook)?

***

### **Category 4: Coding Standards & Conventions**
*This ensures the code I write is consistent with your team's style.*

11. **Language & Version:** What specific language versions are used (e.g., JavaScript ES2022, Python 3.11, TypeScript 5.2)?
12. **Linting & Formatting:** Do you use tools like ESLint, Prettier, Black, or Ruff to enforce code style?
13. **Module System:** What module system is used (e.g., ES Modules (`import`/`export`) or CommonJS (`require`))?
14. **Commit Messages:** Do you follow a specific commit message format, like Conventional Commits?
15. **Data Validation:** How is data validated in the application (e.g., with libraries like Zod, Pydantic, or Yup)?

***

### **Category 5: Testing & Quality**
*This defines the project's approach to testing and debugging.*

16. **Testing Philosophy:** What is the testing strategy? Are tests mandatory for new features or bug fixes?
17. **Debugging Rule:** When a test fails, what is the most important rule to follow? Should I assume the **application code** is wrong first, or the test?
18. **Mocking:** Are there any specific rules regarding mocking in tests?

***

### **Category 6: Deployment & DevOps**
*This covers how the project gets to production.*

19. **Deployment Platform:** Where is the application hosted? (e.g., Vercel, Netlify, AWS, Heroku).
20. **CI/CD:** What system is used for Continuous Integration/Continuous Deployment (e.g., GitHub Actions, GitLab CI/CD)?
21. **Environment Variables:** What is the policy on using environment variables and managing secrets?

***

### **Category 7: Prohibitions & Strict Rules**
*This tells me the critical "what NOT to do" items.*

22. **Forbidden Practices:** Are there any libraries, patterns, or practices that are strictly forbidden?
23. **Security:** Are there any critical security rules I must always follow?
