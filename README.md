# My Company OS

This is your personal brain and private backup. Your agent manages it through conversation.

- Personal backup: https://github.com/bradhavegit/company-os-personal
- Shared company: https://github.com/bradhavegit/leanlabs-company-os

Repository identities and branches are managed in .company-os/setup.json. The agent reads that file before syncing. Both destinations must remain private.

personal/ holds private context, research, drafts, and deliverables. All wiki/ and corrections/ content is company-shareable. Personal backup saves the full intended brain, including unpublished shared edits. Company publication requires your review of the exact batch and stops on conflicts.

Say “Load my Company OS” to continue. On a new machine, give your agent this personal backup URL and ask it to restore Company OS. It reconnects the saved company destination and reconciles newer team knowledge with your saved work.

Agents: read AGENTS.md, then .company-os/workflows/prime.md. Recovery instructions and the necessary sync tools live in .company-os/. Never push the full personal tree to the company repository.
