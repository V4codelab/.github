## Branches
<br>

> **Branching standards for our environment:** each feature has its own branch. All changes related to the feature — including bug fixes, hotfixes, documentation, releases, or experiments (spikes) — are done within that branch.
>
> This approach ensures development standards and culture, maintains a clean commit history, and facilitates code reviews, testing, and traceability. Therefore, it must be followed rigorously.
<br>

| Branch | Description | 
|------------|-----------|
| `main`      | Final layer for deployment; code should reach here only after QA and code review. |
| `module/schema`     | Module in development; all changes related to the module are made here. |

## Commits
<br>

> To maintain a clean commit history and facilitate traceability, use the following commit types:
<br>

| Type       | Description | Example |
|------------|------------|--------|
| `feat`     | New functionality for the module | `feat: add login endpoint` |
| `fix`      | Bug fix | `fix: resolve null pointer exception` |
| `chore`    | Routine maintenance, updates, or tasks not affecting code behavior | `chore: update dependencies` |
| `docs`     | Documentation changes or improvements | `docs: add API usage examples` |
| `style`    | Formatting, linting, or non-functional code changes | `style: fix indentation` |
| `refactor` | Code restructuring or optimization without changing functionality | `refactor: simplify user service` |
| `perf`     | Performance improvements | `perf: optimize dashboard query` |
| `test`     | Adding or updating tests | `test: add unit tests for payment service` |
| `build`    | Changes affecting build system or external dependencies | `build: update webpack config` |
| `ci`       | Continuous Integration configuration changes | `ci: add GitHub Actions workflow` |
| `hotfix`   | Urgent fixes to production | `hotfix: fix crash on login` |
| `revert`   | Reverting previous commits | `revert: revert previous feature` |
| `wip`      | Work in progress, temporary commits during development | `wip: start payment module` |

> **Guidelines:**  
> - Commits should be concise but descriptive.  
> - Always use the appropriate type for better tracking and changelog generation.  
> - Avoid huge commits; keep them small and self-contained.  

This setup ensures development standards, clean commit history, traceability, and proper review workflow.

<br>

<p align="center" style="font-weight: bold">
© V4 Company — Internal Use Only. Unauthorized copying or distribution is strictly prohibited.
</p>

