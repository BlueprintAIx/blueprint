# Colosseum Cypherpunk Hackathon Note

This repository has been created specifically for the Solana Colosseum Cypherpunk Hackathon review process. Our team’s full project codebase contains proprietary infrastructure and integrations that we are unable to make public at this time due to ongoing product development and security considerations.

To respect both the integrity of our IP and the hackathon’s review requirements, this repository provides:
- A detailed technical overview of our architecture, design decisions, and on-chain integrations.
- Walkthroughs, visuals, and documentation explaining how our system operates end-to-end.
- An outline of Blueprint’s main features and the thinking behind our design choices, explaining how each element fits into the overall product vision.
  
We’re happy to provide private beta access to Blueprint to all judges and reviewers to verify functionality.
Thank you for your understanding.

— Blueprint Team


# Introduction 
At our core, we're simplifying Web3 interactions through intelligent agents and infrastructure. To start, we're showing you exactly how you can leverage Blueprint to build a powerful agent, take it to market, and turn it into a protocol of its own. Soon, we'll put the the tools in your hand to build anything on-chain.

---
We’re entering a new era of intelligent systems — one where AI Agents don’t just answer questions, they act. At Blueprint, we’re building the infrastructure for this agentic future — starting on-chain, expanding beyond it, and ultimately redefining how people and systems interact.

# Architecture
![Blueprint Architecture](https://files.readme.io/a1b1b5ae84f132916bda0fb4f95fb397690fe8eba6d8346d97b241498730636b-image.png)

Blueprint empowers developers and users to unlock the full potential of AI agents in Web3, providing the foundational technology for a new era of intelligence on-chain.

Blueprint’s AI Orchestration layer is the foundation that powers intelligent, autonomous behavior across decentralized ecosystems. Designed with flexibility, scalability, and Web3-native functionality in mind, our platform is both powerful and intuitive, abstracting away complexities for developers and offering a seamless experience for end-users.

# Core Infrastructure Components

Tool Calling & Integration Framework

Our tool calling functions are built for transactional use cases, enabling pre-load and post-execution customization. This allows for precise control over agent interactions with external systems. Users can also switch to existing agent frameworks, offering flexibility and compatibility.

Elastic Search & Data Indexing

We simplify data management by allowing users to easily upload unstructured data to Blueprint. We handle indexing and structuring using integrated Elastic Search, enabling powerful, context-aware retrieval and processing.

Comprehensive RAG Engine

Our Retrieval-Augmented Generation (RAG) system enables dynamic, contextually relevant AI responses based on internal and external data sources. This ensures that our agents have access to relevant and up-to-date information, enhancing their accuracy.

MCP (Model Context Protocol) Server

Our MCP server provides a standardized way for Blueprint to securely and efficiently interact with external tools. This eliminates the need for custom integrations, allowing AI agents to access real-time information and perform actions across diverse systems.

Dynamic Chat History and User Profiles

We facilitate dynamic chat history, advanced prompting capabilities, and customized user profiles. This allows our agents to snapshot key elements from user conversations, leading to more personalized and context-aware interactions.

# Web3 Specific Features

On-chain Task Management

Blueprint provides a robust on-chain task management and tracking system. This ensures transparent records of agent activities on any chain.

User Notifications

Integrated notification systems, such as Telegram alerts, keep users informed of task progress and agent interactions.

Deep Web3 Integrations and Tools

Our platform comes preloaded with tools and integrations essential for interacting with DeFi and other types of decentralized protocols right out of the box. This includes indexing of on-chain data, which supports both our agents and task management feature.

Web3 Specific Knowledge Base

We maintain a dedicated knowledge base tailored to Web3 information, providing our AI agents with a comprehensive understanding of blockchains, decentralized finance, and other Web3 paradigms.

# Nest

Nest is the first agent built using Blueprint – think of it as your automated crypto wealth manager.

What is Nest?
Nest enables any user to find and invest in yield opportunities across EVMs, Solana, and Sui. Don't let your capital sit idle – with Nest, you can effortlessly manage your portfolio and participate in vaults for:

Lending

Liquid staking

Yield aggregation

Auto-compounding

...and more!

How does Nest work?
Start by logging into the platform with just your email – new EVM, Solana, and Sui addresses will be generated for you upon onboarding.

Add funds to your new addresses by transferring from an existing wallet, on-ramping via your bank account, or using a card. Add funds to whichever chain you're most comfortable with – Nest can handle any bridging or swapping as needed.

Use chat or widgets to find attractive opportunities to deploy your capital.

Just ask Nest to deposit your preferred amount.

We'll help you get started by providing you with prompts to discover opportunities and manage or optimize your portfolio. Here are some examples of prompts you can ask Nest:

What are popular DeFi strategies that Nest can execute for me?

Are there any new opportunities that I should be aware of?

Rebalance my portfolio to a 60% stablecoin and 40% blue-chip allocation across all chains.

Automatically move my USDC to a higher-yield stablecoin vault if the APY difference is greater than 2%.

Simulate the potential returns of allocating 10% of my portfolio to the top yield farming strategy on Sui for the next 6 months.

Partnerships

We've built Nest by working with top protocols and projects across Web3:

Nest works with Lulo, Kamino, Jupiter Lend on Solana, as well as protocols on other networks to ensure that users always have access to the best yield opportunities on every ecosystem.

LI.FI powers bridging and swapping so that users can take advantage of the best available routes and prices.

We'll be announcing additional partnerships and integrations for wallet abstraction, on/off ramping, and more soon.

# Agent Building

With Blueprint, creating advanced, autonomous agents for Web3 is no longer a challenge — it’s an advantage. Let us handle the infrastructure, so you can focus on what matters.

Blueprint empowers users and enterprises to create, configure, and deploy their own custom AI Agents tailored specifically for Web3. Our infrastructure is designed to offer flexibility and out-of-the-box functionality, accelerating your journey from concept to deployment.

Build What You Need

Blueprint is designed for configurability. You can adjust your agent’s behavior, tools, and data access to suit your specific workflow — whether you’re automating DAO operations, interacting with DeFi protocols, or managing multi-step actions. Use only the features relevant to your objectives, without unnecessary complexity.

From Tasks to Goals: Agentic Automation

Blueprint agents are more than reactive tools — they’re autonomous, proactive systems.
Instead of scripting individual actions, you can hand off high-level goals and let the agent determine the optimal path to fulfillment.

Web3-Native Integration Layer

Blueprint comes equipped with deep integrations across the Web3 stack. This means your custom agents can seamlessly interact with your choice of top protocols, liquidity pools, or core Web3 infra, without needing custom bridge code or external tooling.

Speed-to-Value

With Blueprint’s out-of-the-box tools, you'll be able to go from zero to a functional Web3 agent in days — not months. Pre-integrated services and template workflows accelerate deployment and let you focus on outcomes, not infrastructure. Everything you need is already included.

Scheduled Tasks & Event-Driven Triggers

Leverage our Scheduled Tasks Module to enable recurring or condition-based transactions and operations. This allows your agents to perform actions automatically at specified intervals or in response to on-chain events and external signals.

Intelligent Context with RAG + MCP

Every Blueprint agent is powered by a Retrieval-Augmented Generation (RAG) engine and our Model Context Protocol (MCP).

This allows agents to:

Ingest and act on relevant historical, real-time, and user-provided data.

Maintain persistent memory and personalized context across sessions.

Deliver more accurate, informed, and user-specific outcomes over time.


# Security and Safety

At Blueprint, your security and safety are a top priority. Whether you're deploying agents to execute trades, manage assets, or interface with dApps, you deserve peace of mind knowing that your data and transactions are handled responsibly. We build every layer of our product with safety, integrity, and user control in mind.

Secure-by-Design Architecture

Our core architecture is built with security in mind. We have deliberately abstracted transaction signing and execution from the AI orchestration layer. This means that agents, by design, do not have the inherent ability to create and sign transactions without explicit instructions. All execution flows are gated by strict logic, policies, and user-approved guardrails to prevent unauthorized behavior or unintended actions.

Moderation & Compliance Layer

To maintain platform integrity and user safety:

Every agent response and output undergoes a verification step to ensure it aligns with safety and compliance protocols.

All user prompts are similarly filtered to prevent the initiation of harmful or illegal activities.

This two-way moderation system provides a robust safeguard against misuse from both ends of the interaction.

Blueprint is Non-Custodial

Blueprint does not have ownership or access to your private keys or funds. Our platform is designed to ensure that you retain full control over your wallets, assets, and permissions:

Agent-initiated interactions are always authorized by you and executed through integrated partner protocols that uphold strong security boundaries.

Your keys are never stored by Blueprint.

Granular Automation Controls

We empower you with granular control over your automated interactions. You have the flexibility to define the size of transactions you wish to automate, providing a critical layer of control. Furthermore, we offer the opportunity to review every transaction before it's executed, even conveniently via Telegram, giving you the final say. For the highest level of control, you always have the option to manually sign every transaction.

Trusted Infrastructure Partnerships

Blueprint exclusively partners with trusted and thoroughly vetted infrastructure providers who share our unwavering commitment to robust and transparent security standards. These partners, including industry leaders like LI.FI, Lulo, and Vaults.fyi, are integral to maintaining the integrity and security of our platform.

Ongoing Monitoring & Resilience

Security isn’t a one-time event. We’re committed to continuous monitoring, agent sandboxing, and threat modeling as part of our development cycle. Our AI agents are designed with clear permissions and boundaries, and we regularly evaluate for emerging vulnerabilities across the Web3 ecosystem.

Learn More

We encourage all users to review Blueprint's Terms of Service and Privacy Policy for a full breakdown of how we handle your data, your assets, and your experience on the platform.
