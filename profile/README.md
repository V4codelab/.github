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

## Pull Requests
<br>

> Pull Requests (PRs) are used to review and consolidate all changes from a feature/module branch before merging into `main`.
<br>

1. **One PR per feature/module branch**  
   - Open a PR only when the feature or module is complete and tested.

2. **Responsible party**  
   - Only the **Tech Lead** is authorized to approve and merge PRs into `main`.

3. **Descriptive title and description**  
   - PR title should be concise and informative: `feat/<feature>: brief description`.  
   - Description should include:
     - Purpose of the changes
     - Main modifications
     - QA/testing instructions
     - References or tickets, if any

4. **Review process**  
   - QA and code review are mandatory before merging.  
   - Ensure adherence to development standards, coding style, and traceability.

5. **Merge strategy**  
   - Merge into `main` only after QA and code review approval.  
   - Prefer **squash merge** to keep history clean.

> **Note:** All PR merges and production deployments will be performed **every Monday** by the Tech Lead. This ensures that all approved code is consolidated and released in an organized manner at the start of the week.

<br>

<p align="center" style="font-weight: bold">
© V4 Company — Internal Use Only. Unauthorized copying or distribution is strictly prohibited.
</p>

