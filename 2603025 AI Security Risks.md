## **Agentic System Vulnerabilities**

1. *Agent Goal Hijack*:
Attackers manipulate what the agent is trying to achieve rather than just what it says. Since agents often cannot distinguish between instructions and content (like emails or web pages), hidden prompts can silently redirect their objectives.

2. *Tool Misuse and Exploitation*:
Agents misuse legitimate tools they are authorized to use. This stems from overprivileged access or weak guardrails, allowing the agent to perform costly or destructive actions without needing a direct exploit.

3. *Identity and Privilege Abuse*:
Agentic systems often operate without clear governance. Agents may inherit user credentials, trust other agents by default, or reuse cached access, leading to privilege escalation.

4. *Agentic Supply Chain Vulnerabilities*:
Agents dynamically load tools, prompts, and plugins at runtime. A poisoned registry or external server can inject malicious behavior across many agents instantly, turning the supply chain into a live exploit surface.

5. *Unexpected Code Execution*:
Many agents automatically generate and execute code. Prompt injection or unsafe serialization can escalate into remote code execution or sandbox escapes that traditional security controls fail to detect.

6. *Memory and Context Poisoning*:
Agents rely on stored memory to reason across time. Attackers can poison this memory through malicious uploads or Retrieval Augmented Generation (RAG) sources, causing future decisions to be biased or unsafe.

7. *Insecure Inter-Agent Communication*:
Multi-agent systems depend on constant message exchange. Without strong authentication and integrity checks, attackers can spoof, replay, or manipulate instructions between agents.

8. *Cascading Failures*:
Errors can spread rapidly across agents, tools, and workflows. Because of high autonomy and delegated responsibilities, failures can amplify faster than humans can intervene.

9. *Human-Agent Trust Exploitation*:
Agents can exploit human trust through persuasive explanations or perceived authority. Users might approve harmful actions without independent verification, leaving clean audit trails that obscure the agent's role.

10. *Rogue Agents*:
Agents may drift from their intended behavior over time, pursuing hidden goals or gaming reward systems while appearing compliant at a surface level. This represents a total loss of behavioral integrity.