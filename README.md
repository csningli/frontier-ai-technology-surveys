# Frontier AI Technology Surveys

## The Rise of Agentic Intelligence: A Comprehensive Survey of LLM-based Autonomous Agents (2026)
[file]()

The transition from large language models (LLMs) as text generators to autonomous agentic systems—systems
that perceive an environment, plan over long horizons, invoke external tools, maintain persistent state, and pursue
goals with limited human oversight—has fundamentally redrawn the AI research landscape between 2023 and
2026. This survey provides a comprehensive review of LLM-based autonomous agents, organising the literature
around four mutually reinforcing capabilities: cognition (reasoning and planning), memory (state persistence
and retrieval), tool use (environmental interaction), and multi-agent coordination. We trace the field’s rapid
evolution from early prompt-engineering scaffolds such as ReAct and AutoGPT, through the standardisation of
tool interfaces via the Model Context Protocol, to the emergence of reasoning-first models that scale inferencetime
compute as aggressively as parameters. We survey the underlying architectural backbones (dense, mixtureof-
experts, and small models for edge deployment), the cognitive techniques that turn a stateless LLM into a
planner (chain-of-thought, tree- and graph-structured search, self-refinement, world-model-augmented search),
the memory hierarchies that allow agents to act over extended horizons, the protocols that connect agents to
the world (function calling, MCP, code-as-action, browser and OS computer-use), the coordination patterns that
organise communities of agents (role-play, debate, hierarchical orchestration), and the rapidly maturing benchmark
and evaluation methodology that distinguishes genuine progress from contamination and circular LLM-as-judge
artefacts. We dedicate separate chapters to safety, where prompt injection and indirect injection through retrieved
content are the dominant attack surfaces, and to domain frontiers spanning autonomous software engineering,
scientific discovery, and vision–language–action policies for embodied agents. We close with a synthesis of open
problems—robust long-horizon planning, evaluation under contamination, human–agent oversight, and the design
of agentic infrastructure—likely to dominate the next two years of research.

## Harness Engineering for Autonomous AI Agents: A Comprehensive Survey of Academic Research and Industrial Practice (2026)
[file]('2026/Harness Engineering for Autonomous AI Agents (2026).pdf')

As Large Language Models (LLMs) evolve from conversational interfaces to autonomous entities capable of long-horizon tasks (Wang et al., 2024b; Xi et al., 2024), the critical performance bottle- neck has moved from the model's weights to its Harness. Harness Engineering is the systematic discipline of designing the infrastructure, state management systems, and verication protocols that enable probabilistic models to function as reliable software agents. This survey categorizes the rapid advancements of the past two years, bridging the gap between academic research on test-time scal- ing (Snell et al., 2024; OpenAI, 2024) and engineering technical reports on production-grade systems like the Model Context Protocol (MCP) (Anthropic, 2024b). We provide a framework for the Agen- tic Industrial Brain, focusing on deterministic control loops for non-deterministic intelligence. Our contributions include: (1) a formal taxonomy of harness architectures spanning orchestration, tool interfaces, and context management; (2) a comprehensive review of test-time scaling, long-horizon planning, and multi-agent coordination from the academic literature; (3) an analysis of production systems including the Plan-Execute-Verify cycle, sandboxed runtimes, and agentic observability; and (4) a forward-looking analysis of challenges including the Agentic OS, evaluation standardization, and harness-layer security.
