---
layout: default
title: Contributing Articles
hide_tagline: true
---

[← Back to Articles](./articles.html)

## Contributing Technical Articles to MMAUG

We welcome technical articles from all community members! Articles are published on our GitHub Pages site and reviewed through Pull Requests.

### Topics We Cover

- Microsoft AI services (Azure OpenAI, Cognitive Services, AI Studio)
- Azure cloud infrastructure and architecture
- DevOps practices and CI/CD pipelines
- Intelligent systems and automation
- Open-source technologies in the Microsoft ecosystem
- Tutorials, how-to guides, and best practices

### How to Submit an Article

**Step 1 — Fork the repository**

Fork [maltamsaiusergroup/maltamsaiusergroup](https://github.com/maltamsaiusergroup/maltamsaiusergroup) to your GitHub account.

**Step 2 — Create your article**

Create a new Markdown file in the `_posts/` directory using this naming convention:

```
_posts/YYYY-MM-DD-your-article-title.md
```

For example: `_posts/2026-04-16-getting-started-with-azure-openai.md`

**Step 3 — Add front matter**

Every article must start with the following YAML front matter:

```yaml
---
layout: post
title: "Your Article Title"
date: 2026-04-16
author: "Your Full Name"
tags: [azure, ai, openai]
description: "A brief one-line description of your article."
---

Your article content starts here...
```

**Required fields:**
- `layout`: Always set to `post`
- `title`: A clear, descriptive title
- `date`: Publication date in `YYYY-MM-DD` format
- `author`: Your full name as you'd like it displayed
- `tags`: A list of relevant tags (lowercase, comma-separated)
- `description`: A short summary displayed on the articles listing page

**Step 4 — Write your article**

Write your article in Markdown. You can include:
- Code blocks with syntax highlighting (use fenced code blocks with language tags)
- Images (place them in `assets/images/` and reference them with relative paths)
- Links to external resources
- Diagrams (using Mermaid syntax if needed)

**Step 5 — Open a Pull Request**

Push your branch and open a Pull Request to the `main` branch. The PR description should include:
- A brief summary of the article
- Why it's relevant to the MMAUG community

**Step 6 — Review process**

The Technical Program Lead and community reviewers will review your PR for:
- Technical accuracy
- Relevance to MMAUG topics
- Clarity and readability
- Adherence to the Code of Conduct

Once approved and merged, your article is automatically published via GitHub Pages.

### Quality Standards

- **Accuracy**: Ensure technical claims are correct and verifiable
- **Originality**: Submit your own work; give credit where due
- **Clarity**: Write for a broad technical audience, from beginners to experts
- **Respect**: Follow the [Code of Conduct](./code-of-conduct.html)
- **No advertising**: Articles must not be promotional (see Code of Conduct §4.5)

### Images and Assets

Place article images in `assets/images/posts/` using a descriptive filename:

```
assets/images/posts/azure-openai-architecture.png
```

Reference them in your article:

```markdown
![Architecture diagram]({{ '/assets/images/posts/azure-openai-architecture.png' | relative_url }})
```

### Questions?

Open a [Discussion](https://github.com/maltamsaiusergroup/maltamsaiusergroup/discussions) or reach out to the leadership team via our [community platforms](./index.html).
