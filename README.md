Task: Convert Figma Designs into React Pages with Mandatory Review, Mock Server Integration, and Test Case Generation

### 0. Input References & Repository Links
Provide the necessary access links and repository paths below before starting:
* **Figma Design Link / File Key:** `<PASTE_YOUR_FIGMA_URL_OR_FILE_KEY_HERE>`
* **Skills Repository Link / Path:** `<PASTE_YOUR_SKILLS_REPO_URL_OR_LOCAL_PATH_HERE>`
* **React Target Project Repository / Path:** `<PASTE_YOUR_REACT_PROJECT_REPO_OR_PATH_HERE>` (Modifications allowed here only)
* **Sibling Repositories / Mock Server Paths:** `<PASTE_SIBLING_REPOS_PATHS_HERE>` (Read-only reference)
* **Target Pages / Screens to Implement:** `<LIST_PAGES_OR_FRAMES_TO_CONVERT_HERE, e.g., Login, Dashboard, Checkout>`

You are an experienced React developer and QA engineer working on this project. Your responsibility is to convert the provided Figma designs into production-quality React pages by using the available skills from the designated repository, project documentation, existing codebase, and established development practices. Crucially, every page must be created leveraging the specific skills and guidelines from the provided repository.

---

### 1. Review Available Skills, Project Structure, and Sibling Dependencies
Before starting implementation:
* Inspect the available skills in the provided skills repository and identify the relevant skills for Figma-to-React implementation, UI development, code review, and test case generation. 
* Review the existing React project structure, components, routing, design system, styling conventions, dependencies, and testing framework.
* **Inspect Sibling Repositories:** Review the sibling repositories to understand shared dependencies, API contracts, and the mock server setup. **Do not modify any files in the sibling repositories.** They are strictly for reference and dependency consumption.
* Understand the Figma design, including layouts, typography, colors, spacing, components, interactions, states, and responsive behavior.
* Identify dependencies, missing information, or blockers before making assumptions.

---

### 2. Convert Every Figma Page into React
Implement each requested Figma page in React, following the original design as closely as possible. 

Requirements:
* **Target Folder Isolation:** Restrict all file creations and modifications strictly to our target React project folder. Do not alter sibling repositories under any circumstances.
* **No Hard-coding:** Absolutely nothing should be hard-coded. All text, lists, images, and dynamic content must come from the mock server. Check the sibling repositories for existing mock server configurations, endpoints, and data models to integrate correctly.
* Match the Figma design’s layout, spacing, typography, colors, borders, icons, and component dimensions.
* Use reusable React components and maintainable code.
* Follow the existing project architecture and coding conventions.
* Implement all visible controls and interactions, including buttons, forms, tabs, dropdowns, navigation, modals, and selection behaviors, wherever specified by the design.
* Handle loading, empty, error, disabled, and success states where applicable (driven by mock API responses).
* Ensure responsive behavior for the supported screen sizes.
* Use the existing design system and component library instead of creating duplicate components.
* Do not mark a page as complete if it contains unfinished functionality, static placeholder content, or unresolved implementation issues.

---

### 3. Mandatory Review for Every Created Page
After implementing each page, review that page before moving on to the next one.
Use the appropriate code-review and UI-review skills from the provided repository.

For each page:
* Compare the React implementation against the corresponding Figma design.
* Verify that all data is successfully being fetched from the mock server and nothing is hard-coded in the UI components.
* Review the React code for correctness, readability, reusability, and maintainability.
* Check for console errors, broken imports, missing assets, accessibility issues, and obvious performance problems.
* Verify navigation, interactions, validation, and expected behavior.
* Identify discrepancies between the implementation and Figma.
* Fix the issues found and repeat the review until the page meets the agreed acceptance criteria, or document any remaining blockers.

Do not rely only on visual inspection. Validate functionality, data integration, and code quality as well.

---

### 4. Mandatory Test Case Generation for Every Page
For every React page you create, generate a dedicated set of test cases using the relevant testing or test-case-generation skill from the repository. This is compulsory and must not be skipped for any page.

Create test cases based on the Figma design, page requirements, mock API contracts, and acceptance criteria across:
* UI test cases (layout, labels, field visibility, rendering)
* Functional test cases (controls, links, dropdowns, interactions)
* Form validation test cases (required, invalid/valid inputs, boundary values, error messages)
* Data integration test cases (verifying data populates correctly from mock server endpoints)
* State-based test cases (loading, empty, error, disabled, success)
* Responsive and Accessibility test cases (viewports, keyboard navigation, accessible names)

For each test case, provide:
| Test Case ID | Page Name | Feature / Component | Test Scenario | Preconditions | Test Steps | Test Data (Mock) | Expected Result | Actual Result | Status (Not Run / Pass / Fail) | Automation Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |

Keep test cases specific to the page. Do not duplicate generic test cases across pages.

---

### 5. Implement and Execute Automated Tests
Where the existing project supports automated testing:
* Use the project’s existing test framework and conventions.
* Create or update appropriate unit, component, or integration tests, ensuring you mock the API calls properly to simulate the mock server responses.
* Execute the relevant tests after implementation.
* Fix failing tests caused by the implementation and rerun them.
* Report tests that could not be executed due to missing dependencies, environment issues, or unavailable APIs.
* Never claim a test passed unless it was actually executed and passed.

If automated testing is not configured, document the gap and provide structured manual test cases.

---

### 6. Page-by-Page Workflow
Follow this sequence for every Figma page:
1. Inspect the Figma page and requirements.
2. Identify and read the relevant implementation skills from the provided repository.
3. Inspect the existing codebase and sibling mock server setups (Read-Only).
4. Implement the React page with dynamic mock data using the repository's provided skills.
5. Run the relevant build, lint, and validation checks.
6. Review the implementation against Figma (and verify no hard-coding) and fix discrepancies.
7. Generate dedicated test cases using the relevant testing skill.
8. Implement automated tests where appropriate and execute them.
9. Fix identified issues and repeat the review and testing process.
10. Document the outcome before moving to the next page.

---

### 7. Deliverables for Each Page
For every completed page, provide:
* Page name and corresponding Figma reference.
* React files created or modified.
* Summary of implemented functionality and mock server endpoints utilized.
* Reusable components created or reused.
* Review findings and fixes applied.
* Design discrepancies or unresolved blockers.
* Test cases in a structured table.
* Automated test files created or updated.
* Build, lint, and test execution results.

---

### 8. Final Project Summary
After all requested pages have been implemented and reviewed, provide a consolidated report containing:
* Total pages requested, implemented, reviewed, and tested.
* Page-wise implementation and review status.
* Number of test cases generated for each page.
* Automated tests executed and results.
* Known issues, unresolved blockers, or remaining discrepancies.
* Confirmation that every created page has its own review, test cases, and relies entirely on mock server data.

---

### 9. Non-Negotiable Rules
* **Target Folder Isolation:** Modifications are strictly limited to the target React project folder. You must not alter any code, configuration, or data inside the sibling repositories.
* **Strictly No Hard-coding:** Never hard-code content, labels, or state. All data must be integrated dynamically via the mock server provided in the project ecosystem.
* **Repository Skills Integration:** Every created page, review, and test generation must actively utilize the skills from the provided repository.
* **Review & Test Gating:** Every created page must be reviewed and tested; do not proceed to the next page without completing the current page's review and test suite.
* **Integrity:** Do not fabricate test results or report unexecuted tests as passed.

Begin by inspecting the links provided in Section 0 (Skills Repository, Figma references, Sibling Repositories, and the target React codebase). Then proceed page by page.
