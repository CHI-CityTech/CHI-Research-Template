# <Project Title>

> **One-sentence purpose**: <why this matters in the CHI ecosystem>  
> **Meta-Project link**: See [`/references/meta-projects.md`](references/meta-projects.md)  
> **Advisor(s)**: <Name(s)> • **Term**: <e.g., Fall 2025> • **Status**: Draft

## 1. Abstract
<~150 words: problem, approach, expected outcome.>

## 2. Goals & Deliverables
- **LVP this term**: <e.g., sensor → data → one transformation → audio output>
- **Stretch**: <optional>

## 3. Research Plan (SRDMPA)
- **Speculate → Research → Design → Make → Publish → Assess**
- Keep weekly notes in `docs/research-notes/`. Use the **Research Log** issue template.

## 4. Repo Structure
Briefly describe `src/`, `notebooks/`, `data/`, `docs/`, `references/`. 

📖 **Detailed explanation**: See [`docs/repository-structure.md`](docs/repository-structure.md) for complete file descriptions.

### Project Board
A Kanban board will be automatically created with columns:
- **Backlog** - New issues and planned work
- **In Progress** - Currently active tasks  
- **In Review** - Work awaiting feedback
- **Done** - Completed work

Issues and PRs automatically move through the board based on their status.

### Repository Files
**Core Files** (update these for your project):
- `README.md` - This file, your project overview
- `CITATION.cff` - How others should cite your work
- `LICENSE` - MIT license for your code

**Configuration Files** (usually don't need changes):
- `CONTRIBUTING.md` - Guidelines for contributing
- `CODE_OF_CONDUCT.md` - Behavior expectations  
- `SECURITY.md` - Security policies
- `.gitignore` - Files Git should ignore
- `.gitattributes` - Git LFS configuration for large files
- `.editorconfig` - Consistent code formatting
- `.vscode/` - VS Code settings and recommended extensions

## 5. Setup

### First Steps After Using This Template

**Essential Updates** (do these first):
1. **Update `README.md`** - Replace all `<placeholder>` text with your project details
2. **Update `CITATION.cff`** - Add your name, project title, ORCID (if you have one)
3. **Connect to CHI Meta-Project** - Link your work in `references/meta-projects.md`
4. **Create First Issues** - Use the Milestone and Research Log templates

**Development Environment**:
- **Requirements**: <language / versions>
- **Quick start**:
  ```bash
  # Run setup script
  ./scripts/setup.sh
  
  # Or manually create project board
  # Go to Actions → Setup Project Board → Run workflow
  ```
- **Data**: Put raw files in `data/raw/` (consider Git LFS for large files)

**Optional Customizations**:
- Update `.vscode/settings.json` for personal preferences
- Modify `CONTRIBUTING.md` if working with collaborators
- Add project-specific files to `.gitignore`

## 6. How We Work

- **Project Board**: Automatic Kanban board (Backlog → In Progress → In Review → Done)
- **Issues**: Use Milestone & Research Log templates (auto-added to Backlog)
- **PRs**: Small, frequent; see checklist in PR template (auto-moves through board)
- **AI Collaboration**: Log with the **AI Collaboration Report** issue template
- **Labels**: Use CHI research phase labels (`speculate`, `research`, `design`, `make`, `publish`, `assess`) and activity types (`milestone`, `research-log`, `ai-collaboration`)

## 7. License & Citation

See `LICENSE` and `CITATION.cff`.