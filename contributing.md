# Contributing to Awesome OBS

Thanks for helping improve Awesome OBS! We welcome submissions that help OBS Studio creators and developers find reliable, high-quality open-source tools.

Please review these guidelines before opening a pull request.

---

## Inclusion Criteria

Every submission must meet these standards:

### 1. Open Source
The software being listed must have publicly accessible source code under a valid, [OSI-approved open-source license](https://opensource.org/licenses) (such as MIT, Apache-2.0, GPL, or BSD).

* ✅ **Valid open-source license required**: The software must be covered by a valid, OSI-approved open-source license. A public repository without a verifiable license does not qualify.
* ✅ **Permissive and copyleft**: Both copyleft (GPL, AGPL) and permissive (MIT, Apache, BSD) licenses are equally welcome.
* ✅ **Free and paid open source**: Both free and paid open-source software are allowed.
* ❌ **No closed-source software**: Closed-source software is excluded, even if it is free to use or offers a free tier or trial. See [What Does Not Belong](#what-does-not-belong).

### 2. Quality, Maintenance, and Compatibility
* **Directly relevant to OBS Studio**: Plugins, scripts, docks, filters, themes, and external tools that directly integrate with or support OBS workflows.
* **Maintained and working**: The project must be maintained and functional. Archived, abandoned, or broken projects are not accepted.
* **OBS Studio compatibility**: Plugins, scripts, and integrations must work with at least one currently supported stable version of OBS Studio. Prefer projects compatible with the latest stable release. External tools that do not depend on a specific OBS version are exempt.
* **Documentation**: Clear installation instructions and useful documentation are preferred. English documentation is preferred, but other languages are also accepted.

---

## What Does Not Belong

Do not submit:

* ❌ Closed-source or proprietary software, regardless of price, free tiers, or trial availability.
* ❌ Archived, abandoned, or broken projects.
* ❌ Static overlay graphics, stream overlays without code, or raw scene collection JSON files.
* ❌ Trivial or proof-of-concept projects that offer little practical value.
* ❌ Duplicates of existing entries or forks without significant new functionality.

---

## Entry Guidelines

### Entry Format

Use this format for every entry:

```markdown
- [Project Name](URL) - Short factual description.
```

### Choosing the Link

Link to the most useful official project page. Readers must be able to find and verify the source code and its open-source license.

You can link to any of the following:

- **Source code repository:** Link directly to the GitHub, GitLab, or other source repository.
- **Official project website:** Link to the website if it provides access to the source code.
- **Official documentation:** Link to the documentation if it clearly links to the source repository.

**Examples:**

```markdown
- [Sample Tool](https://github.com/OWNER/REPOSITORY) - Automates scene switching based on audio levels.
- [Example Overlay](https://PROJECT-WEBSITE) - Displays live chat and alerts in browser sources.
- [Demo Integration](https://DOCUMENTATION-PAGE) - Connects hardware controllers to OBS Studio.
```

> *These examples are illustrative only. Replace the names, URLs, and descriptions with those of the actual project.*

> [!NOTE]
> If the entry links to a project website or documentation rather than the source repository, include the source repository and license links in your pull request description so reviewers can verify them.


### Description Style
* Start with a capital letter.
* End with a period (`.`).
* Do not start with `"A"` or `"An"`.
* Do not repeat the project name in the description.
* Keep it short, factual, and concise (aim for 80 characters or fewer).
* Describe what the tool does, not how great it is. Avoid promotional language or buzzwords (e.g., "fastest", "best", "powerful", "game-changing").
* Do not include pricing tags, labels, currency symbols, or status badges.

### Placement & Ordering
* Add the entry to the most appropriate section or subsection.
* **Sort alphabetically** by project name within the chosen section.
* **Proposing a new section**: If you believe a new section is needed, you may propose it directly in your pull request. Include the proposed section name and explain why it is needed. The maintainer will review the proposal and decide whether to create the new section or place the resource in an existing section.

## How to Submit

1. **Check for duplicates**: Search the [README](README.md) and [open pull requests](https://github.com/Pralhad-Nasane/awesome-obs/pulls) to make sure the resource has not already been submitted.
2. **Fork and branch**: Fork the repository and create a new branch for your addition:
   ```bash
   git checkout -b add-project-name
   ```
3. **Add your entry**: Insert the entry in alphabetical order in `README.md`.
4. **Validate**: Run the repository linter locally to check for formatting errors:
   ```bash
   npx awesome-lint README.md
   ```
5. **Open a pull request**: Submit a pull request with a descriptive title (e.g., `Add ProjectName to Category`). Fill out the pull request checklist completely and include a link to the project's source code and license if not obvious from the entry URL.

---

## Questions?

If you have questions about whether a tool qualifies, feel free to [open an issue](https://github.com/Pralhad-Nasane/awesome-obs/issues/new).
