# Example Static Content Repo For Wiki Instances
![Arcetypal Repo](archetypal-heading.jpg)
1. Sync Markdown content into `content` directory to be consumed by private Wiki Instance.
2. Markdown can be Frontmatter decorated.
3. Ensure Repo emits `dispatch.yml` to trigger workflow in order to rebuild site once content updates.
    * create repo secret: `REPO_PAT` * requires Organisaztion PAT 
    * create repo variable: `REPO_OWNER`
    * create repo variable: `REPO_NAME`
4. Connect workflows with other REPO by having a consuming end:
*workflow*
```
on:
    repository_dispatch:
        types:
            - trigger_build
```

---
## Welcome to Community content

This would be a community facing **public** repo.
Rules and regs in order to submit PRs