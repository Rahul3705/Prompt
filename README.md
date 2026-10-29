Here are the master instructions for our project. Please read them carefully, acknowledge that you understand the constraints (especially the strict rules against hard-coding and altering sibling repos), and then immediately begin executing Step 1 for the first page.
​Task: Convert Figma Designs into React Pages with Mandatory Review, Mock Server Integration, and Test Case Generation
​0. Input References & Repository Links
​Figma Design Link / File Key: [PASTE FIGMA URL HERE]
​Skills Repository Link / Path: [PASTE SKILLS REPO PATH HERE]
​React Target Project Repository / Path: [PASTE REACT PROJECT PATH HERE]
​Sibling Repositories / Mock Server Paths: [PASTE SIBLING REPOS PATHS HERE]
​Target Pages / Screens to Implement: [e.g., 1. Login Page, 2. Dashboard, 3. Settings]
​1. Review Available Skills, Project Structure, and Sibling Dependencies
​Inspect the available skills in the provided skills repository and identify the relevant skills for Figma-to-React implementation, UI development, code review, and test case generation.
​Review the existing React project structure, components, routing, design system, styling conventions, dependencies, and testing framework.
​Inspect Sibling Repositories: Review the sibling repositories to understand shared dependencies, API contracts, and the mock server setup. Do not modify any files in the sibling repositories. They are strictly for reference and dependency consumption.
​Understand the Figma design, including layouts, typography, colors, spacing, components, interactions, states, and responsive behavior.
​Identify dependencies, missing information, or blockers before making assumptions.
​2. Convert Every Figma Page into React
​Implement each requested Figma page in React, following the original design as closely as possible.
​Requirements:
​Target Folder Isolation: Restrict all file creations and modifications strictly to our target React project folder. Do not alter sibling repositories under any circumstances.
​No Hard-coding: Absolutely nothing should be hard-coded. All text, lists, images, and dynamic content must come from the mock server. Check the sibling repositories for existing mock server configurations, endpoints, and data models to integrate correctly.
​Match the Figma design’s layout, spacing, typography, colors, borders, icons, and component dimensions.
​Use reusable React components and maintainable code.
​Follow the existing project architecture and coding conventions.
​Implement all visible controls and interactions, including buttons, forms, tabs, dropdowns, navigation, modals, and selection behaviors, wherever specified by the design.
​Handle loading, empty, error, disabled, and success states where applicable (driven by mock API responses).
​Ensure responsive behavior for the supported screen sizes.
​Use the existing design system and component library instead of creating duplicate components.
​Do not mark a page as complete if it contains unfinished functionality, static placeholder content, or unresolved implementation issues.
​3. Mandatory Review for Every Created Page
​After implementing each page, review that page before moving on to the next one.
Use the appropriate code-review and UI-review skills from the provided repository.
​For each page:
​Compare the React implementation against the corresponding Figma design.
​Verify that all data is successfully being fetched from the mock server and nothing is hard-coded in the UI components.
​Review the React code for correctness, readability, reusability, and maintainability.
​Check for console errors, broken imports, missing assets, accessibility issues, and obvious performance problems.
​Verify navigation, interactions, validation, and expected behavior.
​Identify discrepancies between the implementation and Figma.
​Fix the issues found and repeat the review until the page meets the agreed acceptance criteria, or document any remaining blockers.
​4. Mandatory Test Case Generation for Every Page
​For every React page you create, generate a dedicated set of test cases using the relevant testing or test-case-generation skill from the repository. This is compulsory and must not be skipped for any page.
​Create test cases based on the Figma design, page requirements, mock API contracts, and acceptance criteria across:
​UI test cases, Functional test cases, Form validation test cases, Data integration test cases, State-based test cases, Responsive and Accessibility test cases.
​For each test case, provide:
5. Implement and Execute Automated Tests
​Where the existing project supports automated testing:
​Use the project’s existing test framework and conventions.
​Create or update appropriate unit, component, or integration tests, ensuring you mock the API calls properly to simulate the mock server responses.
​Execute the relevant tests after implementation.
​Fix failing tests caused by the implementation and rerun them.
​6. Page-by-Page Workflow
​Follow this sequence for every Figma page:
​Inspect the Figma page and requirements.
​Identify and read the relevant implementation skills from the provided repository.
​Inspect the existing codebase and sibling mock server setups (Read-Only).
​Implement the React page with dynamic mock data using the repository's provided skills.
​Run the relevant build, lint, and validation checks.
​Review the implementation against Figma (and verify no hard-coding) and fix discrepancies.
​Generate dedicated test cases using the relevant testing skill.
​Implement automated tests where appropriate and execute them.
​Fix identified issues and repeat the review and testing process.
​Document the outcome before moving to the next page.
​7. Deliverables for Each Page
​For every completed page, provide:
​Page name and corresponding Figma reference.
​React files created or modified.
​Summary of implemented functionality and mock server endpoints utilized.
​Reusable components created or reused.
​Review findings and fixes applied.
​Design discrepancies or unresolved blockers.
​Test cases in a structured table.
​Automated test files created or updated.
​Build, lint, and test execution results.
​8. Final Project Summary
​After all requested pages have been implemented and reviewed, provide a consolidated report containing total pages, statuses, test counts, unresolved issues, and confirmation of strict mock-server usage.
​9. Non-Negotiable Rules
​Target Folder Isolation: Modifications are strictly limited to the target React project folder. You must not alter any code, configuration, or data inside the sibling repositories.
​Strictly No Hard-coding: Never hard-code content, labels, or state. All data must be integrated dynamically via the mock server provided in the project ecosystem.
​Repository Skills Integration: Every created page, review, and test generation must actively utilize the skills from the provided repository.
​Review & Test Gating: Every created page must be reviewed and tested; do not proceed to the next page without completing the current page's review and test suite.
​Let's begin. Acknowledge these instructions, check the repository paths and sibling dependencies, and start the workflow for the first page listed in Section 0.
