I have provided Mermaid diagrams representing an existing application's/business process.

Analyze the diagrams and reverse-engineer the actual process and system flow shown in them.

Do NOT focus on Mermaid syntax, Mermaid code, styling, colors, diagram types, or how the diagrams were technically created.

Your goal is to understand and explain the process represented by the diagrams.

Analyze the following:

1. Complete End-to-End Process
   
   - Start from the first user/business action.
   - Follow the process step by step until the final outcome.
   - Explain what happens at every stage.

2. Actors and Systems
   
   - Identify every actor, user, team, application, service, backend system, database, external system, or component involved.
   - Explain the responsibility of each one in the process.

3. Interactions
   
   - For every interaction, explain:
     - Who initiates it
     - Who receives it
     - What information/action is passed
     - What happens after it
   - Preserve the direction and sequence shown in the diagrams.

4. Business Logic
   
   - Identify all business rules, validations, eligibility checks, conditions, approvals, decisions, exceptions, and dependencies.
   - Explain what causes each decision and what happens for each possible outcome.

5. Data Flow
   
   - Identify what information is created, entered, retrieved, validated, updated, transferred, or stored at each stage.
   - Identify where the data originates and where it goes next.

6. System Flow
   
   - Explain how the different systems/components work together.
   - Identify which system is responsible for each step.
   - Identify synchronous vs asynchronous interactions where this can be determined from the diagrams.

7. User Journey
   
   - Describe the process from the user's perspective.
   - Explain what the user does, what the system does automatically, and where the user receives a response or outcome.

8. Decision Points and Alternate Flows
   
   - Identify every decision point.
   - Explain the main/positive path.
   - Explain failure, rejection, exception, or alternate paths.
   - Do not ignore branches that appear small or secondary in the diagram.

9. Dependencies
   
   - Identify prerequisites for each major step.
   - Explain which steps depend on previous steps, approvals, data, systems, or external responses.

10. End-to-End Business Scenario
    After analyzing everything, describe the entire process in plain English as if explaining it to someone who needs to understand how the application actually works.

11. Process Reconstruction
    Reconstruct the process in this format:

User/Actor
→ Action
→ System
→ Validation/Decision
→ Next System/Action
→ Result
→ Next Step

Continue until the complete process is finished.

12. Gaps / Ambiguities
    Identify anything that cannot be determined from the diagrams.
    Clearly separate:

- Explicitly shown information
- Reasonable inference
- Information that is missing/unclear

Important rules:

- Analyze the actual process, not the Mermaid implementation.
- Do not redesign the process.
- Do not suggest improvements.
- Do not assume functionality that is not represented.
- Do not skip seemingly minor steps.
- Maintain the exact sequence and relationships represented in the diagrams.
- If multiple diagrams describe different parts of the same process, combine them into one coherent end-to-end process.
- If diagrams contradict each other, explicitly point out the contradiction instead of choosing one interpretation.
- Use the terminology/names shown in the diagrams.
- The final output should make it possible for another person to understand the application's real end-to-end workflow and business process without looking at the Mermaid diagrams.
