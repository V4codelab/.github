## Codebase 
<br>

| Repo | Service | Scope | Stage |
|------|---------|-------|-------|
| [v4-api](https://github.com/NK/v4-main) | ![API](https://img.shields.io/badge/Services-API-blue) | Integrates with V4’s central Matrix to retrieve and process data. | `Production` |
| [loopvisit](https://github.com/NK/v4-main) | ![Saas](https://img.shields.io/badge/Services-SaaS-red) | Tracking commercial visits from first contact to deal closure. | `Architecture` |
| [loopreps](https://github.com/NK/v4-main) | ![Saas](https://img.shields.io/badge/Services-SaaS-red) | Corporate expense management for travel, meals, and reimbursements. | `Backlog` |
| [loopcupom](https://github.com/NK/v4-main) | ![Saas](https://img.shields.io/badge/Services-SaaS-red) | Customer management, bonus allocation, and coupon handling | `Backlog` |

## Branches
<br>

> **Branching standards for our environment:** each feature has its own branch. All changes related to the feature — including bug fixes, hotfixes, documentation, releases, or experiments (spikes) — are done within that branch.
>
> This approach ensures development standards and culture, maintains a clean commit history, and facilitates code reviews, testing, and traceability. Therefore, it must be followed rigorously.

| Branch | Description | 
|------------|-----------|
| `main`      | Final layer for deployment; code should reach here only after QA and code review. |
| `module/schema`     | Module in development; all changes related to the module are made here. |

<p align="center" style="font-weight: bold">
© V4 Company — Internal Use Only. Unauthorized copying or distribution is strictly prohibited.
</p>

