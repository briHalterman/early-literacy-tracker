# Tech Stack Research and Planning Notes

[Full Stack Roadmap](https://roadmap.sh/full-stack)
[Web Dev Tech Stack](https://ranzlappen.com/references/web-dev-tech-stack/)
[MDN Curriculum](https://developer.mozilla.org/en-US/curriculum/)

## Languages

**Markup language:** HTML
The structural foundation of any web page or app.
[HTML: The Living Standard](https://html.spec.whatwg.org/dev/)

Pairs well with:

- CSS
- JavaScript

**Styling language:** CSS
The visual styling and layout of any web page or app.
[Learn CSS](https://web.dev/learn/css/)
[CSS Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS)

Pairs well with:

- HTML
- Tailwind CSS

Alternative:

- Tailwind CSS

**Programming language:** JavaScript
The programming language of the web, run natively in browsers.
[JavaScript Web Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

Pairs well with:

- TypeScript
- Node.js
- React
- Vite

Alternative:

- TypeScript

**Static type checking:** TypeScript
A typed superset of JavaScript.
[The TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html)

Pairs well with:

- JavaScript
- Vite
- ESLint

## Libraries & Frameworks

**UI library:** React
A declarative JavaScript library for building user interfaces from composable components.
[React](https://react.dev/)
[The Road to React](https://www.roadtoreact.com/)

Pairs well with:

- Vite
- TypeScript
- Next.js

**Client-side routing:** React Router
Routing library for React.
[React Router](https://reactrouter.com/)

Pairs well with:

- React
- Vite
- TypeScript

**Backend framework:** Express
A minimal web API framework for Node.js.
[express](https://expressjs.com/)

Pairs well with:

- TypeScript
- PostgreSQL

**Database access / Object data modeling:** Mongoose
ODM library for MongoDB and Node.js.
[mongoose](https://mongoosejs.com/docs/)

Pairs well with:

- MongoDB
- Express

**MVP Styling:** CSS Modules
Bundler convention for component-scoped styling.
[css-modules](https://github.com/css-modules/css-modules)

Pairs well with:

- Vite
- React
- Next.js

Alternative:

- Tailwind CSS

**Stretch goal styling:** Tailwind CSS
A utility-first CSS framework for styling component-based UIs.
[tailwindcss](https://tailwindcss.com/)

Pairs well with:

- React
- Vite

Alternative:

- CSS Modules

**Testing library:** React Testing Library
Lightweight component tests for React.
[Testing Library](https://testing-library.com/)
[react-testing-library](https://github.com/testing-library/react-testing-library)

Pairs well with:

- Vitest
- Jest
- React

**Testing framework:** Vitest
Unit-test framework for Vite-based projects.
[Vitest](https://vitest.dev/)

Pairs well with:

- Vite
- React Testing Library
- TypeScript

Alternative:

- Jest

**SVG icons library:** TBD

**Password hashing:** bcrypt
[Password Hashing using bcrypt](https://medium.com/@bhupendra_Maurya/password-hashing-using-bcrypt-e36f5c655e09)

**Authentication / session strategy:** JWT
Self-contained secure transmission of JSON objects between web parties.
[JWT Handbook](https://auth0.com/resources/ebooks/jwt-handbook?utm_source=jwt&utm_medium=microsites&utm_campaign=jwt&_gl=1*nczf5z*_gcl_au*MzQ5ODEwNDUwLjE3ODk0MDY3OTI.*_ga*MjA5MTUzMDA4LjE3ODk0MDY3OTE.*_ga_QKMSDV5369*czE3OTAwODQ2NzYkbzIkZzAkdDE3OTAwODQ2ODAkajU2JGwwJGgw)

**Data validation:** TBD

## Tools

### Development Tools

**Code editor/IDE:** VS Code
[Visual Studio Code](https://code.visualstudio.com/Docs)

**Terminal application:** iTerm2
[iTerm2](https://iterm2.com/documentation.html)

**Backend runtime:** Node.js
Server-side JavaScript runtime for back-end APIs and full-stack frameworks.
[node.js](https://nodejs.org/en)
[Node.js v26.10.0 documentation](https://nodejs.org/docs/latest/api/)

Pairs well with:

- Express
- TypeScript
- npm
- Vite

**Package/dependency management:** npm
Default dependency management for Node.
[npm Docs](https://docs.npmjs.com/)

Pairs well with:

- Node.js

Alternative:

- Yarn

**Frontend build tool:** Vite
A frontend build tool and development server for use with React.
[Vite](https://vite.dev/)

Pairs well with:

- React
- Vitest
- TypeScript

### Quality / Testing Tools

**Linter:** ESLint
Standard linter for catching bugs and enforcing conventions across JavaScript/TypeScript.
[ESLint](https://eslint.org/)

Pairs well with:

- Prettier
- TypeScript
- GitHub Actions

**Opinionated Code Formatter:** Prettier
Auto-formatting JavaScript, TypeScript, CSS and HTML.
[Prettier](https://prettier.io/)

Pairs well with:

- ESLint
- TypeScript

**API development tooling / manual testing:** Postman
[Postman Docs](https://learning.postman.com/)

**E2E testing:** TBD

**Accessibility testing / tooling:** TBD

**AI-assisted review:** GitHub Copilot
[GitHub Copilot documentation
](https://docs.github.com/en/copilot)

**Continuous integration / automation:** GitHub Actions
Platform for automating GitHub workflows.
[GitHub Actions documentation
](https://docs.github.com/actions)

Pairs well with:

- GitHub
- ESLint
- Prettier

### Version Control / Project Management

**Version control:** Git
Ubiquitous version control system.
[git](https://git-scm.com/docs)

Pairs well with:

- GitHub
- GitHub CLI
- GitHub Actions

**Repository hosting:** GitHub
Code repo hosting and collaboration platform.
[GitHub Docs](https://docs.github.com/en)

Pairs well with:

- Git
- GitHub Actions
- GitHub CLI
- GitHub Pages

**Issue / project management:** GitHub Projects
Work planning and tracking tool for GitHub.
[About Projects](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects)

Pairs well with:

- GitHub

### Design / Documentation

**Wireframing:** Figma
[Figma](https://www.figma.com/)

**Architecture documentation diagramming:** Mermaid

**Data modeling:** dbdiagram.io
Entity-relationship diagramming.
[dbdiagram Docs](https://docs.dbdiagram.io/)

**API documentation:** Swagger UI
[SwaggerUI](https://swagger.io/open-source/swagger-ui/)

## Services / Infrastructure

**Database:** MongoDB
Document-oriented NoSQL database.
[MongoDB Docs](https://www.mongodb.com/docs/)

Pairs well with:

- Mongoose
- Express
- Node.js

Alternative:

- PostgreSQL

**Database hosting:** MongoDB Atlas

**Hosting platform:** TBD

**External API (Book search):** TBD
[OpenLibrary](https://openlibrary.org/developers/api)

**Secrets management:**
Local: `.env` + `.gitignore`
Production: TBD

## Standards & Guidelines

[Airbnb JavaScript Style Guide](https://github.com/style-guide/airbnb-javascript-style-guide)
**API specification:** [OpenAPI Specification](https://swagger.io/specification/)
**API Communication:** REST API / HTTP
**Accessibility standards:** [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) / [WAI-ARIA](https://www.w3.org/WAI/standards-guidelines/aria/)
**Security guidelines:** [OWASP](https://owasp.org/)

## Development Practices

**Code design principles:** Sandi Metz / POODR
**Project management methodology:** Agile
**Testing methodology:** Test Driven Development
**Time management technique:** The Pomodoro Technique

## Resources

[Coolors](https://coolors.co/)
[The A11y Project](https://www.a11yproject.com/)
