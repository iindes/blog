# Evaluating AI agents, highlighting why traditional testing methods are insufficient for autonomous system

unlike deterministic traditional software, AI agents are probabilistic and autonomous. They plan, adapt, use tools, and can make different valid decisions, meaning a single pass/fail test isn't enough. Therefore, evaluation must observe the entire journey of an agent, including how plans are formed, tools are used, and information is passed.
Agent evaluation encompasses the entire AI stack, including:

The LLM brain
Prompts that guide it
External tools and APIs
The memory system
Orchestration logic
A full-stack checklist for system-level testing is presented, emphasizing the need to check:

Final output: task success rate, output quality, and safety.
Planning and reasoning: how the model logically breaks down goals and justifies steps.
Tool use: effectiveness in picking the right tool, passing parameters, handling outputs, and avoiding redundant costs.
Memory and context: accurate retrieval of past information and handling of long-range context.

### Conclusion
evaluating individual agents in a multi-agent system can be misleading if the overall system goal isn't considered.