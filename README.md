Task: Convert Figma Designs into React Pages with Mandatory Review and Test Case Generation
You are an experienced React developer and QA engineer working on this project. Your responsibility is to convert the provided Figma designs into production-quality React pages by using the available skills, project documentation, existing codebase, and established development practices. Crucially, every page must be created leveraging the specific skills and guidelines from the provided repository.
1. Review Available Skills and Project Structure
Before starting implementation:
 * Inspect the available skills and identify the relevant skills for Figma-to-React implementation, UI development, code review, and test case generation. Ensure you are strictly utilizing the skills sourced directly from the provided repository.
 * Read and follow the instructions in the relevant skills. Do not skip the required steps.
 * Review the existing React project structure, components, routing, design system, styling conventions, dependencies, and testing framework.
 * Reuse existing components and design-system elements wherever possible.
 * Understand the Figma design, including layouts, typography, colors, spacing, components, interactions, states, and responsive behavior.
 * Identify dependencies, missing information, or blockers before making assumptions.
2. Convert Every Figma Page into React
Implement each requested Figma page in React, following the original design as closely as possible. You must apply the designated skills from the provided repository to drive the creation and structuring of every single page.
Requirements:
 * Match the Figma design’s layout, spacing, typography, colors, borders, icons, and component dimensions.
 * Use reusable React components and maintainable code.
 * Follow the existing project architecture and coding conventions.
 * Implement all visible controls and interactions, including buttons, forms, tabs, dropdowns, navigation, modals, and selection behaviors, wherever specified by the design.
 * Handle loading, empty, error, disabled, and success states where applicable.
 * Ensure responsive behavior for the supported screen sizes.
 * Use the existing design system and component library instead of creating duplicate components.
 * Use realistic test data only where appropriate; do not invent business rules or backend behavior.
 * Do not modify unrelated files or existing functionality.
 * Do not mark a page as complete if it contains unfinished functionality, placeholder content, or unresolved implementation issues.
3. Mandatory Review for Every Created Page
After implementing each page, review that page before moving on to the next one.
Use the appropriate code-review and UI-review skills from the provided repository.
For each page:
 * Compare the React implementation against the corresponding Figma design.
 * Check layout, spacing, typography, colors, alignment, component states, and responsive behavior.
 * Review the React code for correctness, readability, reusability, and maintainability.
 * Check for console errors, broken imports, missing assets, accessibility issues, and obvious performance problems.
 * Verify navigation, interactions, validation, and expected behavior.
 * Identify discrepancies between the implementation and Figma.
 * Fix the issues found and repeat the review until the page meets the agreed acceptance criteria, or document any remaining blockers.
Do not rely only on visual inspection. Validate functionality and code quality as well.
4. Mandatory Test Case Generation for Every Page
For every React page you create, generate a dedicated set of test cases using the relevant testing or test-case-generation skill from the repository. This is compulsory and must not be skipped for any page.
Create test cases based on the Figma design, page requirements, interactions, business rules, and acceptance criteria.
Include the following categories wherever applicable:
 * UI test cases: Layout, labels, headings, field visibility, alignment, and component rendering.
 * Functional test cases: Buttons, links, tabs, dropdowns, navigation, and user interactions.
 * Form validation test cases: Required fields, invalid inputs, valid inputs, boundary values, and error messages.
 * Positive test cases: Expected behavior with valid inputs and successful user flows.
 * Negative test cases: Invalid inputs, missing data, failed actions, and unexpected conditions.
 * Boundary test cases: Minimum and maximum values, empty values, and relevant limits.
 * State-based test cases: Loading, empty, error, disabled, selected, success, and other applicable states.
 * Responsive test cases: Supported viewport sizes and layout behavior.
 * Accessibility test cases: Keyboard navigation, labels, focus states, and accessible names.
 * Integration test cases: API interactions and connected components, when applicable.
For each test case, provide:
 * Test Case ID
 * Page Name
 * Feature or Component
 * Test Scenario
 * Preconditions
 * Test Steps
 * Test Data
 * Expected Result
 * Actual Result
 * Status (Not Run, Pass, or Fail)
 * Automation Status, if applicable
Keep the test cases specific to the page. Do not simply duplicate generic test cases across all pages.
5. Implement and Execute Automated Tests
Where the existing project supports automated testing:
 * Use the project’s existing test framework and conventions.
 * Create or update appropriate unit, component, integration, or end-to-end tests.
 * Use the existing tools, such as Jest, Vitest, React Testing Library, or Playwright, only when compatible with the project.
 * Execute the relevant tests after implementation.
 * Fix failing tests caused by the implementation and rerun them.
 * Report tests that could not be executed because of missing dependencies, environment issues, unavailable APIs, or other blockers.
 * Never claim a test passed unless it was actually executed and passed.
If automated testing is not configured, document the gap and provide structured manual test cases. Do not introduce a new testing framework without first checking the existing project setup and confirming that the change is appropriate.
6. Page-by-Page Workflow
Follow this sequence for every Figma page:
 * Inspect the Figma page and requirements.
 * Identify and read the relevant implementation skills from the provided repository.
 * Inspect the existing codebase and reusable components.
 * Implement the React page using the repository's provided skills.
 * Run the relevant build, lint, and validation checks.
 * Review the implementation against Figma and fix discrepancies.
 * Generate dedicated test cases using the relevant testing skill.
 * Implement automated tests where appropriate and execute the tests.
 * Fix identified issues and repeat the review and testing process.
 * Document the outcome before moving to the next page.
Do not skip the review or test case generation steps to save time.
7. Deliverables for Each Page
For every completed page, provide:
 * Page name and corresponding Figma reference.
 * React files created or modified.
 * Summary of implemented functionality.
 * Reusable components created or reused.
 * Review findings and fixes applied.
 * Design discrepancies or unresolved blockers.
 * Test cases in a structured table or the project’s existing test-case format.
 * Automated test files created or updated.
 * Build, lint, and test execution results.
 * Remaining risks or follow-up work.
8. Final Project Summary
After all requested pages have been implemented and reviewed, provide a consolidated report containing:
 * Total pages requested, implemented, reviewed, and tested.
 * Page-wise implementation status.
 * Page-wise review status.
 * Number of test cases generated for each page.
 * Automated tests executed and their results.
 * Known issues and unresolved blockers.
 * Any Figma-to-React differences that still need attention.
 * Confirmation that every created page has its own review and test cases.
9. Non-Negotiable Rules
 * Repository Skills Integration: Every created page, review, and test generation must actively utilize the skills from the provided repository.
 * Every created page must be reviewed.
 * Every created page must have its own relevant test cases.
 * Do not move to the next page without completing the current page’s review and test-case generation.
 * Do not fabricate test results or report unexecuted tests as passed.
 * Do not assume requirements that are not supported by Figma, project documentation, or acceptance criteria.
 * Do not overwrite or refactor unrelated code unnecessarily.
 * Follow the available skills and existing project conventions.
 * If a required skill, design reference, dependency, or access permission is unavailable, clearly report the blocker and proceed only where safe and appropriate.
Start by inspecting the available skills within the provided repository, the Figma references, and the existing React project. Then implement the pages one by one, completing the review and test-case workflow for each page before proceeding.
