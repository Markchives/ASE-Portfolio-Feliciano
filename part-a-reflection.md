# Reflection from Part A (Concept Analysis)

Agentic Software Engineering means building software that uses AI agents, or using AI agents to help build software. An AI agent is a program that can look at a situation, decide what to do, and take action on its own to reach a goal. Engineers still follow the software development life cycle (SDLC), which covers planning, designing, coding, testing, releasing, and maintaining. The difference is that they also set the agent's goals, the tools it may use, and the limits it must follow, and then check that it behaves well.

This is what separates an AI agent from a traditional application. A traditional application does exactly what the programmer wrote, so the same input gives the same output every time. An AI agent decides for itself how to reach a goal. It can choose which tools to use, adjust to new situations, and give different answers to the same request. This makes agents more flexible and useful, but also harder to predict and test.

Because of this, Agile methods are a good fit for building agentic systems. It is hard to plan an agentic system completely at the start, since we only learn how an agent behaves once we try it. Agile methods such as Scrum build software in short cycles called sprints. After each sprint, the team reviews the results, gets feedback, and makes changes. This helps the team catch problems early, fix the agent's instructions and safety limits, and keep improving. Sommerville also explains that building in small steps works well when requirements keep changing.

Developers must also think about the risks of deploying autonomous agents. On the ethical side, an agent may be unfair or biased, or take harmful actions. For privacy, it may expose or misuse personal data. For security, attackers may trick it with harmful instructions, known as prompt injection, or it may be given more access than it needs. It can also be unclear who is responsible when the agent makes a mistake, and an agent may give wrong answers with confidence or get worse over time. The NIST AI Risk Management Framework says organizations should govern, map, measure, and manage these risks. Simple safeguards include giving the agent only the access it needs, keeping logs of its actions, testing thoroughly, and being able to undo what it did.

Finally, human oversight is what ties these safeguards together. Humans must stay in charge because AI can be wrong even when it sounds sure. People understand context and ethics better, and they can stop the agent if it does something it should not. NIST's Govern function also says that clear roles and accountability are needed. Asking a person to approve important actions protects users and builds trust.

## What I Learned

Writing this analysis showed me that an AI agent is not the same as a normal program. A normal program follows fixed instructions, but an agent makes its own choices, so it needs limits, testing, and a person watching over it.

I also learned that Agile fits agentic systems well. Since we cannot predict everything an agent will do, building and testing it in small steps lets us find and fix problems early.

The idea that stood out most to me is human oversight. Even a very capable AI can be confidently wrong, so important decisions should not be left to it alone. Going forward, I want to use AI as a helper in my coding, while reviewing, testing, and understanding everything it produces.
