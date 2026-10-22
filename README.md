# AI Test Case Generator

A portfolio experiment exploring how AI can assist with test-design activities such as functional scenarios, negative cases, boundary values, and edge-case ideas.

## Demo

The previous README listed this hosted demo endpoint:

[Open the demo](https://ca6c8f39e3472b7e-223-233-86-180.serveousercontent.com/)

Hosted demo URLs can expire or become unavailable. Treat the link as optional until it has been checked recently.

## Intended test-design use cases

The README and demo description focus on generating ideas for:

- Functional test scenarios
- Negative test scenarios
- Boundary-value ideas
- Edge-case suggestions
- API scenario suggestions
- Test-data ideas

AI-generated scenarios are suggestions, not verified test results. A tester should review them for correctness, completeness, testability, and business context before use.

## Current repository scope

The public repository currently contains this README rather than the application's implementation source. As a result, the underlying prompt logic, model/provider configuration, dependencies, and generated-output handling cannot be reviewed from this repository.

For a stronger technical portfolio, add the source code, setup instructions, a safe example input/output, and tests for the generation logic. Do not describe Jira or Azure DevOps integrations as implemented unless working code is added.

## Conceptual workflow

```text
Requirement or feature description
              |
              v
      Prompt / input handling
              |
              v
      AI-assisted generation
              |
              v
   Human review of suggested cases
```

This diagram describes the intended concept, not a verified implementation architecture.

## Author

**Harshada Khopade** · QA Automation and AI testing interests

- [GitHub profile](https://github.com/harshadakhopade6)
- [LinkedIn](https://www.linkedin.com/in/harshadakhopade/)
