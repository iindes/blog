# evaluating AI agents using Google's Agent Development Kit (ADK)
## 3-tier testing pyramid to ensure agents perform reliably

### Tier 1: Component-level unit tests
focus on testing the smallest building blocks in isolation, such as
tool usage and correct response formatting. These tests are fast, cheap,
and automated, making them ideal for continuous integration.

### Tier 2: Trajectory-level integration tests
assess a full multi-step task end-to-end. This tier checks if the agent
plans logically, uses tools in the correct order, adapts to failures,
remembers earlier information, and ultimately reaches its goal.

### Tier 3: End-to-end human review
involves human feedback to evaluate the overall user experience,
including helpfulness, safety, and common sense. While slower and more
expensive, this tier acts as the final quality gate.

## Conclusion:
Trajectory is the entire journey an agent takes to solve a task, including tool calls, intermediate steps, reasoning, and the final response.
Key ADK built-in metrics like trajectory average score and response match score are introduced to define passing criteria for tests.