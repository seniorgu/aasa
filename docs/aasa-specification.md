# AI-Augmented Solution Architecture (ASA+)

---

## Overview

ASA+ (AI-Augmented Solution Architecture) adopts a more augmented, integrative, absorptive, evolutionary, hybrid, or fused approach to AI enterprise solutions, compared with the AI-first orientation of ASA approach (AI-Native Solution Architecture, see this [link](https://github.com/seniorgu/aisa/blob/main/docs/aisa-specification.md)). It is positioned as an enterprise AI absorption and coexistence architecture, aiming to maintain architectural continuity while enabling AI augmentation.

## ASA+ Architectural Approach

ASA+’s architectural approaches include:

- **AI absorption approach (beyond AI adoption):** progressing from adopted intelligence toward owned intelligence

- **Coexistence of operational modes:** supporting autonomy, semi-autonomy, automation, and semi-automation to enable gradual augmentation

- **Governance-heavy control:** emphasizing stronger governance mechanisms beyond the validation and adaptation focus of AI-native solution architecture

- **System integration focus:** addressing integration challenges in heterogeneous enterprise environments

- **Enterprise alignment:** stronger alignment with business requirements, data strategies, and organizational assurance objectives

## ASA+ Modeling Elements

As an AI-augmented architectural approach, ASA+ incorporates both non-AI elements and AI-specific elements (which are heavily emphasized in AI-native architecture). As a result, ASA+ operates on a mixed set of AI and non-AI elements, including a shared subset with the base ASA approach. Table 1 presents the primary AI and non-AI elements of ASA+.

| **Element Name**    | **AI-Specific** | **Definition**                                                                                                                             |
| ------------------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| Access Interface    |                 | Represents the interaction channels, UI/UX surfaces, and entry points through which humans engage with the solution.                       |
| Application         |                 | Represents a bounded software system, enterprise application, or business component that integrates with or consumes AI capabilities.      |
| App Logic           |                 | Represents explicitly defined non-GUI logic, control flow, or compositional behavior of an application.                                    |
| Data Service        |                 | Represents services responsible for data access, integration, transformation, federation, and transactional integrity.                     |
| Technical Component |                 | Represents reusable technical capabilities, utility services, and cross-cutting infrastructure functions available across the solution.    |
| AI Agent            | Yes             | Represents an autonomous AI entity capable of goal-directed reasoning, planning, and action.                                               |
| AI Coordinator      | Yes             | Represents the coordination logic, workflow control, and multi-agent management that sequences and routes AI operations.                   |
| Context State       | Yes             | Represents the mechanisms for managing conversational state, memory, prompt engineering, and interaction coherence.                        |
| AI Model            | Yes             | Represents the models, inference engines, and reasoning frameworks that generate predictions, decisions, or outputs.                       |
| Knowledge Service   | Yes             | Represents the semantic retrieval, RAG, embedding, and knowledge management capabilities that ground AI responses in relevant information. |
| AI/ML Lifecycle     | Yes             | Represents the lifecycle management processes for model training, experimentation, versioning, and deployment.                             |
| Autonomous Tool     | Yes             | Represents external functions, plugins, and third-party services that extend AI capabilities through invocation.                           |

*Table 1: Primary ASA+ Elements*

For the full list of ASA+ modeling elements and its foundational specification, refer to this [link](https://github.com/seniorgu/ai-esa/blob/main/docs/ai-esa-specification.md).

ASA+ architectural services can be categorized into three types: fully autonomous applications, agentic applications with varying degrees of autonomy, and deterministic automation applications.

---

## ASA+ Example

Here are examples of ASA+ modeling cases.

### Canonical Case Example

Figure 1 illustrates an ASA+ for an AI-Augmented Enterprise Operations Platform. This example demonstrates:

- AI augmentation instead of replacement,

- coexistence with enterprise systems,

- governance-heavy architecture,

- hybrid operational control,

- human approval boundaries,

- enterprise integration continuity.

![Canonical Case Example](images/aasa-canonical-example.png "Canonical Case Example")

*Figure 1: ASA+ for an AI-Augmented Enterprise Operations Platform*

### Edge Case Example

Figure 2 shows ASA+ edge case for a High-Risk Human-Governed AI Decision Environment. This edge case demonstrates:

- constrained autonomy,

- governance escalation,

- partial AI delegation,

- operational safeguards.

![Edge Case Example](images/aasa-edge-case.png "Edge Case Example")

*Figure 2: ASA+ Edge Case Example*

---

## Related Model Specification and Architecture

ASA+ uses its model specification and maintains a close relationship with AI-native solution architecture.

For the relationship and relevance among ASA model and approach, and AIS+ approach, see this [link](https://github.com/seniorgu/ai-esa/blob/main/docs/relationship-of-ai-esa-to-aisa-and-aasa.md). 
