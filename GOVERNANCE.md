# SEAFOM GitHub Governance

This document defines the governance, roles, and contribution process for all repositories under the **SEAFOM GitHub Organization**.

## 1. Roles & Responsibilities

### Admins / Owners 
- Merge to protected branches
- Review and approve pull requests
- Full write access across repos
- Ensure compliance with governance and quality standards

### Maintainers / Developers 
- Create feature branches
- Submit pull requests for review
- Review pull requests (but cannot merge to `main`)
- Implement fixes and enhancements

### Contributors (Public)
- Fork repositories
- Submit pull requests
- Must receive review and approval before merge

### Steering Committee
- OTM + SEAFOM Steering Committee serves as overarching admin for all repos
- Provides governance oversight and resolves conflicts

## 2. Branch Protection (required in every repo)
- Require pull request reviews
- Require **2 approvals total**
- Require **status checks to pass** (CI)
- Require branches to be up to date before merging
- Dismiss stale PR approvals on new commits
- Enable “Require review from Code Owners”

## 3. Review Requirement (enforced by workflow)
Each PR must have:
- **1 approval from an Admin** (oversight/governance), and
- **1 approval from a Maintainer/Developer** (technical review)
- All required status checks passing

## 4. Contribution Workflow (high-level)
1. Fork or branch the repository
2. Create a feature branch
3. Make changes
4. Run tests locally
5. Open a Pull Request
6. Obtain required approvals (Admin + Maintainer)
7. Admin merges when checks pass

## 5. Governance Changes
- Changes to this policy require consensus of the Steering Committee and repository Admins.
- Updates will be tracked in this repo via pull requests.
