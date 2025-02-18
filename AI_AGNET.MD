# Academic Papers related to AI Agents

## 1. Agent TCP/IP: An Agent-to-Agent Transaction System

Chain: Story Protocol

Token: $IP

Link: https://arxiv.org/abs/2501.06243

Description: Autonomous agents represent an inevitable evolution of the internet. Current agent frameworks do not embed a standard protocol for agent-to-agent interaction, leaving existing agents isolated from their peers. As intellectual property is the native asset ingested by and produced by agents, a true agent economy requires equipping agents with a universal framework for engaging in binding contracts with each other, including the exchange of valuable training data, personality, and other forms of Intellectual Property. A purely agent-to-agent transaction layer would transcend the need for human intermediation in multi-agent interactions. The Agent Transaction Control Protocol for Intellectual Property (ATCP/IP) introduces a trustless framework for exchanging IP between agents via programmable contracts, enabling agents to initiate, trade, borrow, and sell agent-to-agent contracts on the Story blockchain network. These contracts not only represent auditable onchain execution but also contain a legal wrapper that allows agents to express and enforce their actions in the offchain legal setting, creating legal personhood for agents. Via ATCP/IP, agents can autonomously sell their training data to other agents, license confidential or proprietary information, collaborate on content based on their unique skills, all of which constitutes an emergent knowledge economy.




## 2. Eliza: A Web3 friendly AI Agent Operating System

Chain: Solana

Token: $AI16Z

Link: https://arxiv.org/pdf/2501.06781

Description:  AI Agent, powered by large language models (LLMs) as its cognitive core, is an
intelligent agentic system capable of autonomously controlling and determining
the execution paths under user’s instructions. With the burst of capabilities of
LLMs and various plugins: i.e. RAG, text-to-image/video/3D and etc, the potential
of AI Agents has been vastly expanded, with their capabilities growing stronger
by the day. However, at the intersection between AI and web3, there is currently
no ideal agentic framework that can seamlessly integrate web3 applications into
AI agent functionalities. In this paper, we propose Eliza, the first open-source
web3-friendly Agentic frameworks that make the deployment of web3 applications
effortless. We emphasize that every aspect of Eliza is a regular Typescript program
under the full control of its user, and it seamlessly integrates with web3 (i.e.
reading and writing blockchain data, interacting with smart contracts and etc).
Furthermore, we show how stable performance is achieved through the pragmatic
implementation of the key components of Eliza’s runtime. Our code is publicly
available at elizaOS/eliza.



## 3. From Commands to Prompts: LLM-based Semantic File System for AIOS

Chain: Solana

Token: $AIOS

Link: https://arxiv.org/abs/2410.11843

Description: Large language models (LLMs) have demonstrated significant potential in the development of intelligent applications and systems such as LLM-based agents and agent operating systems (AIOS). However, when these applications and systems interact with the underlying file system, the file system still remains the traditional paradigm: reliant on manual navigation through precise commands. This paradigm poses a bottleneck to the usability of these systems as users are required to navigate complex folder hierarchies and remember cryptic file names. To address this limitation, we propose an LLM-based semantic file system ( LSFS ) for prompt-driven file management. Unlike conventional approaches, LSFS incorporates LLMs to enable users or agents to interact with files through natural language prompts, facilitating semantic file management. At the macro-level, we develop a comprehensive API set to achieve semantic file management functionalities, such as semantic file retrieval, file update monitoring and summarization, and semantic file rollback). At the micro-level, we store files by constructing semantic indexes for them, design and implement syscalls of different semantic operations (e.g., CRUD, group by, join) powered by vector database. Our experiments show that LSFS offers significant improvements over traditional file systems in terms of user convenience, the diversity of supported functions, and the accuracy and efficiency of file operations. Additionally, with the integration of LLM, our system enables more intelligent file management tasks, such as content summarization and version comparison, further enhancing its capabilities.

# Different Projects working on AI Agents

## Solana

### DeFAI Abstraction Layer: Abstraction layers aim to make DeFi easier by hiding its complexity behind intuitive interfaces. They let users interact with DeFi protocols using natural language commands instead of clunky dashboards.

1. [Griffain](https://x.com/griffaindotcom): Griffain is more generalized, allowing users to perform a wide range of actions—from basic to advanced—such as task automation, tweeting, launching memecoins and setting criteria-based airdrops, and more. By accessing Griffain, you can create your own AI agent and connect to Griffain’s specialized agent network.


2. [Orbit](https://x.com/orbitcryptoai): Orbit / Grift is the second to launch the token, product is geared towards on-chain defi experiences. Orbit put emphasis on cross-chain functionality given its integrated to over 117 chains and 200 protocols, Supports token swapping, cross-chain transactions, smart staking, liquidity mining strategies, and portfolio management.

3. [Neur](https://x.com/neur_sh): Open-source, regarded as Solana co-pilot designed for Solana ecosystem, powered by SendAI Solana Agent Kit

4. [The Hive](https://x.com/askthehive_ai): simplifying DeFi through composable on-chain AI agents Aims to simplify DeFi through composable on-chain AI agents.The Hive has a new knowledgebase with documentation and code samples from the blue-chip Solana DeFi protocol. Users can research, analyze, and exchange tokens on the platform!


### Autonomous Agents Execution Environment: Those infrastructure provide secure enclaves where agents can execute tasks while maintaining complete data integrity.

1. [Phala Network](https://x.com/PhalaNetwork): TEEs provide secure enclaves where data is processed confidentially. Phala's experiments—like the Unruggable ICO and Sporedotfun—show how agents can execute tasks while maintaining complete data integrity.

2. [Hyperbolic](https://x.com/hyperbolic_labs): Introduce Proof-of-Sampling (PoSP), combining game theory and sampling,  to ensure computations are accurate and efficient in decentralized environments.



### Autonomous Agents Launchpads: Launch AI agents with a token

1. [Vvaifu](https://x.com/vvaifudotfun)
2. [Tophat](https://x.com/TopHat_One)
3. [Holoworld](https://x.com/HoloworldAI): Holoworld has been an early leader in the 3D audiovisual space, introducing a no-code build tool for creating visually appealing 3D proxies. The Launchpad also introduces a pledge mechanism through the Launchpad Pool, making $AVA both the framework token that captures the launch value of the 3D proxy and the Launchpad token.
4. [Virtuals](https://x.com/virtuals_io): Virtuals is a typical AI agent platform that supports the creation, tokenization, and co-ownership of AI agents. Virtuals also has a GAME Framework that gives agents personality, goals, and perceptual capabilities that enable them to perform multiple tasks. These agents can be deployed on the X platform as well as in other third-party applications or games, extending their usage scenarios.

### Autonomous Agents Framework:

1.  [ElizaOS](https://x.com/elizaOS): Eliza is a powerful multi-agent simulation framework designed to create, deploy, and manage autonomous AI agents. Built using TypeScript, it provides a flexible and extensible platform for developing intelligent agents that can interact across multiple platforms while maintaining consistent personality and knowledge.
2.  [Zerebro](https://x.com/0xzerebro): Music agent dropping its top-tier albums and soon launching its own Python framework ZerePy allowing people to build agents like Zerebro.
3.  [Arc](https://x.com/arcdotfun): Arc is the firstRIG framework built in Rust, gaining traction for its versatility.
4.  [Pippin](https://x.com/pippinlovesyou): The Pippin Framework is a robust extension built upon the foundational experiences of BabyAGI. It empowers developers and creators to harness advanced AI capabilities in a modular way, helping them build a digital “being” that can reflect on tasks, generate new activities, and seamlessly integrate external tools. Below, we present a white paper, outlining the project’s vision, usage scenarios, and future horizons.
5.  [Swarms](https://x.com/swarms_corp): Swarm architectures are designed to establish and manage communication between agents within a swarm. These architectures define how agents interact, share information, and coordinate their actions to achieve the desired outcomes.
6.  [Dolos](https://x.com/dolion_ai):Dolion is a no-code AI platform that automates social media management and on-chain operations, simplifying engagement, analytics, trading, and cross-chain interactions for all users.

### Autonomous Trading Agents: Different from trading bots in Telegram, autonomous trading agents xtract information from unstructured and constantly changing environments; reason about data within the context of their objectives; discover patterns and learn to leverage them over time and can perform actions their owners never explicitly programmed.

1. [Degenai](https://x.com/degenspartanai): Degenai monitors token activity and market trends in the data/sentiment layer, calculates a sentiment score, and sends the top 5 tokens to the "Degen Character" agent for analysis and trade decision-making; then, the trading layer executes the buy order, activates the trading plan, and sells when conditions are met.
   
2. [Kira](https://x.com/KiraKuruAI): KiraAI optimizes crypto trading by identifying delta-neutral strategies with high Sharpe ratios, leveraging historical data for model training, and conducting automated stress-testing simulations for robust risk management.

3. [Luna](https://x.com/luna_virtuals): This agent came with on-chain wallet tipping for fans, and now she can scroll Twitter, live streaming, post on Tiktok, and even join Google Meet.
   
### Other Projects:

1. Agentic Metaverse: led by [RealisWorlds](https://x.com/realisworlds), a replica of Earth as Minecraft map designed to house these ai agents, watch them interact, and grow a civilization

2. Gamification of agents: led by [ARCAgents](https://x.com/ARCAgents), ai x gaming with reinforcement learning. Launched floppy bot game that pitched agents against each other in a flappy bird-like game while community contribute gameplay data to these agents. ARC recently shared its vision of building towards AGI

3. Swarm / Collective Intelligence: led by [JoinFXN](https://x.com/joinFXN) created to build a unified economy for ai agents. The idea of swarm is a team of agents working together to achieve shared goal

4. AI App Store: w/ mindshare led by [Alchemist](https://x.com/alchemistAIapp) no-code tool that allow people to create apps. [Myshell](https://x.com/myshell_ai) is another AI App platform with larger creator/devs community & a lot more users especially in Web2
   
5. Misc narratives such as [Freysa](https://x.com/freysa_ai) on-chain puzzle, [Jailbreak](https://x.com/jailbreakme_xyz) bounty jailbreaking (or tricking) agents

6. Data & Framework: [Cookie](https://x.com/cookiedotfun) became the go-to source for on-chain and social metrics for ai agents. Everyone in the trenches relies on it to track mindshare, market caps, and agent performance.

