# CoreySham Developer Portfolio

Personal developer portfolio for **Corey Shamburger**, showcasing software development projects, technical skills, experience, and professional work.

Built with **Next.js, React, TypeScript, Tailwind CSS, and shadcn/ui** and deployed with **Vercel**.

## Live Site

**Production:** https://coreysham.dev

## Technology Stack

- Next.js
- React
- TypeScript
- Tailwind CSS
- shadcn/ui
- pnpm
- Vercel
- GitHub
- Jira

## Getting Started

### Prerequisites

Before running the project locally, make sure you have **Node.js** and **pnpm** installed.

Check your installations:

```bash
node --version
pnpm --version
```

### Clone the Repository

Clone the repository from GitHub:

```bash
git clone https://github.com/CoreyShamb/coreysham.dev.git
cd coreysham.dev
```

### Install Dependencies

Install the project dependencies:

```bash
pnpm install
```

### Start the Development Server

Run:

```bash
pnpm dev
```

The development server is configured to run on:

```text
http://localhost:3002
```

Open the URL in your browser to view the application.

The development server automatically reloads the application as changes are made.

## Project Structure

The repository is organized around the Next.js App Router architecture.

```text
coreysham.dev/
├── .vscode/
├── app/
├── components/
├── lib/
├── public/
├── .gitignore
├── components.json
├── eslint.config.mjs
├── next.config.ts
├── package.json
├── pnpm-lock.yaml
├── pnpm-workspace.yaml
├── postcss.config.mjs
├── tsconfig.json
├── LICENSE
└── README.md
```

### Main Directories

- `app/` — Next.js application routes, layouts, pages, and application-level files.
- `components/` — Reusable React and UI components.
- `lib/` — Shared utilities and supporting application logic.
- `public/` — Static assets such as images, documents, and other public files.
- `.vscode/` — VS Code workspace configuration.

## Development Workflow

Development work for the portfolio is tracked through **Jira** and integrated with **GitHub**.

Changes should be developed on dedicated branches rather than directly on `main`.

### Jira Work Items

Development work uses the `CSD` Jira project key.

Example:

```text
CSD-2 Improve GitHub project documentation
```

### Branches

Branch names should include the associated Jira work-item key.

Example:

```text
CSD-2-improve-GitHub-project-documentation
```

Create or switch to the appropriate development branch before making changes.

### Commits

Commit messages should also include the Jira work-item key so GitHub development activity can be associated with the corresponding Jira work item.

Example:

```bash
git add .
git commit -m "CSD-2 Improve GitHub project documentation"
git push
```

### Pull Requests

Changes are reviewed through **GitHub pull requests** before being merged into `main`.

A typical development workflow is:

```text
Jira Work Item
      ↓
Development Branch
      ↓
Code Changes
      ↓
Git Commit
      ↓
GitHub
      ↓
Pull Request
      ↓
Review
      ↓
Merge to main
      ↓
Vercel Deployment
```

## Deployment

The production application is deployed with **Vercel** and integrated with GitHub.

Changes merged into `main` are automatically built and deployed through the GitHub and Vercel integration.

**Production:** https://coreysham.dev

## Repository

**GitHub:** https://github.com/CoreyShamb/coreysham.dev

## Project Status

This portfolio is actively maintained and continues to evolve as new projects, technologies, technical skills, and professional experience are added.

Development tasks, improvements, documentation changes, and bug fixes are managed through the project's Jira development workflow.

## Author

**Corey Shamburger**  
Software Developer

- Portfolio: https://coreysham.dev
- GitHub: https://github.com/CoreyShamb