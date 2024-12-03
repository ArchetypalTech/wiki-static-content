# Example Static Content Repo For Wiki Instances
![Arcetypal Repo](archetypal-heading.jpg)
1. Sync Markdown content into `content` directory to be consumed by private Wiki Instance.
2. Markdown can be Frontmatter decorated.
3. Ensure Repo emits webhook to trigger workflow in order to rebuild site once content updates.
    * create repo secret: `REPO_PAT`
    * create repo variable: `REPO_OWNER`
    * create repo variable: `REPO_NAME`

---
## Welcome to Community content

This would be a community facing **public** repo.
Rules and regs in order to submit PRs