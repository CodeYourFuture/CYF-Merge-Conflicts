# Managing Merge Conflicts

## Learning Objectives
- [ ] Commit different changes to the same line
- [ ] Resolve the merge conflicts that occur
- [ ] Feature branch from main on a shared repo

## Requirements

### 1. Create and resolve merge conflicts

### 2. Reduce merge conflicts with feature branching


```mermaid
gitGraph
    commit
    branch feature-buttons
    checkout feature-buttons
    commit
    commit
    checkout main
    branch feature-footer
    checkout feature-footer
    commit
    checkout main
    branch feature-logo
    checkout feature-logo
    commit
    commit
    checkout main
    merge feature-buttons
    merge feature-logo
    branch feature-header
    checkout feature-header
    commit
    commit
    checkout main
    merge feature-header
    checkout feature-footer
    commit
    commit
    commit
    checkout main
    merge feature-footer
```

## Acceptance Criteria

- [ ] I have created a merge conflict
- [ ] I have resolved this conflict
- [ ] I have created a small scoped feature branch on a shared repo
- [ ] I have merged this feature branch to main
