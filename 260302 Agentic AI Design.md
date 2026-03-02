# **Three fundamental AI agent design patterns using the Agent Development Kit (ADK) to help build agentic systems**

**Single Agent**
    : This is the most basic pattern, suitable for simple tasks like planning a trip using a search tool. It's easy to implement and great for straightforward multi-step tasks. However, it lacks control and can be unreliable for complex workflows or when multiple tools are involved.

**Sequential Agent**
    : This pattern provides more control for highly structured and repeatable tasks, similar to an assembly line. Tasks are broken down into specialized sub-agents that run in a fixed order, where the output of one becomes the input for the next. This offers high reliability and predictability but can be inflexible.

**Parallel Agent**
    : This pattern is designed for tasks where sub-tasks don't need to happen in a specific order, like finding a museum, concert, and restaurant for a trip. Multiple specialized agents run concurrently to reduce latency. While it significantly reduces processing time, it can have higher initial costs and often requires an additional "aggregator" agent to combine results, adding complexity.