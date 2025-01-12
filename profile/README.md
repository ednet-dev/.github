# EDNet.dev (Explicit Democracy Network)

Welcome to **EDNet.dev**, where we’re building a suite of tools, libraries, and applications that simplify and supercharge **domain-driven** app development. Our ecosystem supports **business rule–rich**, **gamified** domain models, delivering a streamlined path from **abstract concepts** to **full-featured MVPs**—all while championing **user-centric** design and **direct democracy** principles.

---

## Our Mission

1. **Empower Domains**: We believe in placing real-world business logic and user interactions at the heart of software design.  
2. **Democratize Software**: By leveraging **domain-driven design** and **event storming**, we strive to make complex app-building accessible to both developers and domain experts.  
3. **Bridge Gaps**: We focus on bridging the divide between business logic, design, and implementation using **code generation**, **content management**, and **collaborative modeling**.  

---

## The Toolbox

EDNet.dev delivers a growing ecosystem of Flutter and Dart packages, each addressing a critical piece of the puzzle:

- **[EDNet Core](https://github.com/ednet-dev/cms/tree/main/packages/core)**  
  A meta-framework for modeling your domain. Captures business rules, relationships, invariants, and events in a consistent, event-storming–inspired structure.

- **[EDNet CMS](https://github.com/ednet-dev/cms/tree/main/packages/cms)**  
  Your content management superpower for Flutter. Creates a powerful synergy of domain modeling, content orchestration, and UI scaffolding.

- **[EDNet One (App)](https://github.com/ednet-dev/cms/tree/main/apps/one)**  
  A multiplatform Flutter application that **visualizes** your EDNet.dev domain models. Navigate, drill down, and interact with your data from domain to entity.

- **EDNet Semantics & Design System**  
  - **[EDNet Semantics](https://github.com/ednet-dev/cms/tree/main/packages/semantics)**: Flutter bindings to default attribute widgets—automatically generated from your domain.  
  - **[EDNet Design System](https://github.com/ednet-dev/cms/tree/main/packages/design_system)**: A Figma-inspired design system that configures UI/UX consistently across your domain.

- **[EDNet Figma Libraries](https://github.com/ednet-dev/ednet_figma_library)**  
  Integrate your Figma designs directly into EDNet.dev workflows, generating domain-specific UI components and bridging the gap between design and code.

- **[EDNet Code Generation](https://github.com/ednet-dev/cms/tree/main/packages/code_generation)**  
  Streamlines the boilerplate. Takes your domain definitions (in YAML or code) and generates robust, typed repositories, event handling, and UI scaffolds.

---

## The Monorepo

Most of our active development happens in our **[CMS Monorepo](https://github.com/ednet-dev/cms)**. Within it, you’ll find the key projects above under one roof:
```
cms/
├─ packages/
│   ├─ core
│   ├─ cms
│   ├─ content
│   ├─ types
│   └─ code_generation
├─ apps/
│   └─ one  (EDNet One)
└─ …
```
By centralizing all packages, we ensure tight integration, easier iteration, and a **single source of truth** for EDNet.dev’s evolving capabilities.

---

## Key Principles

1. **Domain-Driven Design**: Your code *is* your business logic.  
2. **Event Storming**: Visualize how your domain reacts and changes over time.  
3. **No-Code/Low-Code**: Empower domain experts to define models in YAML, automatically generating code stubs and scaffolds.  
4. **User-Centric**: Start from the **user**’s perspective—always.  
5. **Democracy in Design**: Our name stems from “Explicit Democracy,” focusing on transparent, adaptable solutions.

---

## Example Use Cases

- **Business-Rich MVPs**: Accelerate your proof-of-concept with minimal boilerplate and instant domain modeling.  
- **Domain Exploration**: Use **EDNet One** to explore entity relationships, master-detail views, and even tweak your domain on the fly.  
- **Figma-to-Flutter**: Seamlessly import your Figma layouts into EDNet’s design system and generate adaptive, data-bound widgets.

---

## Get Started

1. **Check out the [CMS Monorepo](https://github.com/ednet-dev/cms)**.  
2. **Read the README** in each package ([ednet_core](https://pub.dev/packages/ednet_core), `[ednet_cms](https://pub.dev/packages/ednet_cms), etc.) to understand usage.  
3. **Clone and Explore**:  
   ```bash
   git clone https://github.com/ednet-dev/cms.git
   cd cms/apps/one
   flutter pub get
   cd lib/requirements

	4.	Model Your Domain using .ednet.yaml files, or dive into Dart-based domain definitions.
	5.	Generate your code:

dart run build_runner watch --delete-conflicting-outputs


	6.	Run EDNet One (apps/one) to visualize and interact with your domain.

Contribute & Community

We’re building a community of devs and domain experts who believe in open, maintainable, and democratic software. Contributions, issues, and discussions are always welcome!
	•	Open an Issue
	•	Fork and Submit PRs
	•	Join the Discussion in our repository forums

For specific inquiries, reach our dev team.

License

Each package in EDNet.dev may have its own license. See the respective LICENSE file in each package directory for full details.

<p align="center">
  <img src="https://img1.wsimg.com/isteam/ip/4896c6bc-229c-47e9-afdd-ff5ab2d2fdbf/Logo-eb329c1.png/:/rs=w:107,h:107,cg:true,m/cr=w:107,h:107/qt=q:95" width="80" alt="EDNet Logo"/>
</p>


<p align="center">
  <b>Explore • Interact • Integrate </b>
</p>
```
