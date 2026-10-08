# PromptRegistry

Problem: My company has 30 GenAI applications, each with hundreds of prompts.
I want to design a centralized: [Prompt Registry → Versioning → Testing → Evaluation → Approval → Deployment → Rollback]. Write practical implementation steps using GitHub which I can follow.

PromptRegistry project shows how to use GitHub as the single source of truth for your prompt Registry. It show how to maintain full version history, PR based approval, automated testing/evaluation via GitHub Actions and controlled deoployed/rollback.

**PromptsRegistry**
        ├── prompts/                  ← Registry
        ├── datasets/                 ← Evaluation data
        ├── .github/workflows/        ← Testing, Evaluation, Deployment
        ├── deployments/              ← Active version pointers per environment
        └── tools/                    ← Shared scripts / SDK helpers


**Promptfoo** tool to test, evaluate, compare and secure AI/LLM applications. It helps validate prompts, RAG applications, AI agents and model output in a structured, repeatable way instead of relying on manual testing.
        




## Quick Start Checklist (Do These First)

1. Create the prompts-registry repository.
2. Define the folder structure and metadata schema.
3. Move 5–10 critical prompts into the repo.
4. Add the Promptfoo GitHub Action and make it a required check.
5. Set up CODEOWNERS and branch protection.
6. Build a minimal SDK / fetch function for one application.
7. Create a simple promote + rollback workflow.





