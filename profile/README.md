# MagicAuth

## About

**MagicAuth** is a cryptography-driven authentication service that provides deterministic key generation across devices using familiar authentication methods. Built by [Web Heroes](https://webheroes.us), MagicAuth eliminates key synchronization headaches and device dependencies, offering developers a language-agnostic protocol for cryptographic key management without the chaos.

This organization contains all projects, packages, and source code for the MagicAuth ecosystem.

## Key Repositories

### Open Source
- **[magicauth-crypto](https://github.com/magicauth-io/magicauth-crypto)** - Core cryptographic operations compiled to WebAssembly for community auditing

### Coming Soon
- **secure.magicauth.io** - Web interface for managing root keys
- **MagicAuth SDK** - Client SDK for integrating MagicAuth into applications
- **Public API Client** - Public-facing API client library

## Getting Started

For integration support and access to MagicAuth, please contact us at **hello@magicauth.io**.

Full documentation site coming soon.

## Community Guidelines

### Contributing Principles

#### 1. Respect the work that came before you

> "In the matter of reforming things, as distinct from deforming them, there is one plain and simple principle; a principle which will probably be called a paradox. There exists in such a case a certain institution or law; let us say, for the sake of simplicity, a fence or gate erected across a road. The more modern type of reformer goes gaily up to it and says, 'I don't see the use of this; let us clear it away.' To which the more intelligent type of reformer will do well to answer: 'If you don't see the use of it, I certainly won't let you clear it away. Go away and think. Then, when you can come back and tell me that you do see the use of it, I may allow you to destroy it.'"
>
> — G.K. Chesterton, *The Thing* (1929)

Or more simply: "Don't ever take a fence down until you know the reason why it was put up."

Before removing or changing existing code, seek to understand why it was written that way. Previous developers made decisions for reasons that may not be immediately obvious. Understand the context and constraints before proposing changes.

#### 2. There are no temporary fixes

Temporary fixes become permanent technical debt. What seems like a quick solution today becomes a liability that compounds over time. Avoid shortcuts that compromise long-term code quality. The expedient path often leads to lasting negative consequences that are far more costly to fix later.

#### 3. There is no code without tests

"Tests are what hold the value over many iterations, not the implementation."

The true value accumulated over years of evolution is captured in tests, not the code itself. Implementations change, get refactored, and are rewritten—but tests preserve the intent, behavior, and requirements. Untested code has no verifiable value and cannot be safely evolved.

#### 4. No monorepos

"Every project must evolve on its own."

Each project must maintain independent responsibilities, versioning, and release cycles. Monorepos create artificial coupling between unrelated concerns and blur the boundaries of ownership. Clear separation allows each project to have its own lifecycle, stakeholders, and evolution without being held back by unrelated dependencies.

#### 5. Design for stakeholders, not dependencies

"A project (or tool) is designed for its stakeholders, not for its dependencies."

We make decisions that are best for the user, not based on what's convenient for our upstream dependencies. Be willing to fork, wrap, or replace dependencies that don't serve user needs. Unfit dependencies hurt the end-user and create technical debt. Don't pass upstream limitations down to your users.

#### 6. Force push is only for correcting falsities

The git history must be preserved to properly inform the future. Force push should only be used to correct actual mistakes—leaked secrets, commits to wrong branches, or factual errors. Never use force push to revise or cover up legitimate history. Git history is a truthful record of how and why the code evolved, and that context is invaluable for future maintainers.

## Resources

- **Website**: [magicauth.io](https://magicauth.io)
- **Built by**: [Web Heroes](https://webheroes.us)
- **Documentation**: Coming soon

