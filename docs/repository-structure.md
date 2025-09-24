# Repository Structure Guide

This document explains every file and folder in your CHI research repository.

## Root Directory Files

### Files You Should Update

**`README.md`**
- **Purpose**: Main project documentation, first thing people see
- **Action**: Replace placeholder text with your project details
- **Why Root**: GitHub displays this automatically on the repository page

**`CITATION.cff`** 
- **Purpose**: Tells others how to cite your work academically
- **Action**: Update with your name, project title, and details
- **Why Root**: GitHub creates a "Cite this repository" button automatically
- **Format**: YAML file following Citation File Format standard
- **Comments**: Use `#` for comments to guide you through filling it out

### Configuration Files (Usually Don't Change)

**`LICENSE`**
- **Purpose**: Legal permissions for your code (MIT License)
- **Action**: Usually leave as-is unless you have specific requirements
- **Why Root**: Standard location, GitHub recognizes it automatically

**`CONTRIBUTING.md`**
- **Purpose**: Guidelines for others contributing to your project
- **Action**: Update if you want specific contribution rules
- **Why Root**: GitHub links to this in issue/PR templates

**`CODE_OF_CONDUCT.md`**
- **Purpose**: Expected behavior for project participants
- **Action**: Usually leave as-is
- **Why Root**: GitHub policy and community standard

**`SECURITY.md`**
- **Purpose**: How to report security issues
- **Action**: Usually leave as-is for student projects
- **Why Root**: GitHub security tab links here

### Git Configuration Files

**`.gitignore`**
- **Purpose**: Tells Git which files to never track
- **Contains**: System files (.DS_Store), Python cache, environment files
- **Why Root**: Git looks for it here
- **Action**: Add project-specific files you don't want in version control

**`.gitattributes`**
- **Purpose**: Git LFS (Large File Storage) configuration
- **Contains**: Rules for handling large binary files (images, data)
- **Why Root**: Git looks for it here
- **Action**: Usually leave as-is

### Development Environment Files

**`.editorconfig`**
- **Purpose**: Consistent code formatting across different editors
- **Contains**: Indentation, line endings, character encoding rules
- **Why Root**: Most editors look for it here
- **Action**: Usually leave as-is

**`.vscode/`**
- **Purpose**: VS Code workspace configuration
- **Contains**: Recommended extensions, workspace settings
- **Why Root**: VS Code looks for `.vscode` folder in project root
- **Action**: Customize if you have specific VS Code preferences

## Directories

### Research Content

**`docs/`**
- **Purpose**: Project documentation
- **Contains**: `index.md`, `research-notes/` with weekly logs
- **Use**: High-level documentation, research progression notes

**`references/`**
- **Purpose**: CHI meta-projects and bibliography
- **Contains**: `meta-projects.md` with CHI framework connections
- **Use**: Link your work to broader CHI research initiatives

**`data/`**
- **Purpose**: All data files for your research
- **Structure**: `raw/` (original), `processed/` (cleaned)
- **Use**: Organize your datasets with clear provenance

### Code and Analysis

**`src/`**
- **Purpose**: Source code for your research
- **Use**: Python modules, analysis scripts, utilities

**`notebooks/`**
- **Purpose**: Jupyter notebooks for exploration and analysis
- **Use**: Data exploration, prototyping, narrative analysis

**`scripts/`**
- **Purpose**: Utility and automation scripts
- **Contains**: `setup.sh` for initial repository setup
- **Use**: CLI tools, data processing pipelines

**`tests/`**
- **Purpose**: Unit tests for your code
- **Use**: Ensure code reliability (even for research!)

**`assets/`**
- **Purpose**: Static files (images, media, etc.)
- **Use**: Figures, logos, presentation materials

## GitHub-Specific Directories

**`.github/`**
- **Purpose**: GitHub repository configuration
- **Contains**: Issue templates, PR templates, workflows, labels
- **Subdirectories**:
  - `ISSUE_TEMPLATE/` - Forms for creating standardized issues
  - `workflows/` - GitHub Actions automation
  - `labels.yml` - Repository label definitions

## Why This Structure?

1. **Standards Compliance**: Follows GitHub and academic conventions
2. **Tool Integration**: Works with VS Code, Git, package managers
3. **Discoverability**: Other researchers can easily understand your work
4. **CHI Methodology**: Supports SRDMPA research cycle
5. **Reproducibility**: Clear organization aids in research reproduction

## Getting Started Checklist

When you create a repository from this template:

1. **Update Core Files** (Essential):
   - [ ] `README.md` - Replace all `<placeholder>` text with your project details
   - [ ] `CITATION.cff` - Add your name, project title, and ORCID (if you have one)
   
2. **Connect to CHI Framework**:
   - [ ] Link to meta-project in `references/meta-projects.md`
   - [ ] Create first Research Log issue (choose your SRDMPA phase)
   - [ ] Create first Milestone issue with concrete deliverables
   
3. **Set Up Project Management**:
   - [ ] Run `./scripts/setup.sh` or manually trigger "Setup Project Board" workflow
   - [ ] Configure git if needed: `git config user.name` and `git config user.email`
   
4. **Start Research**:
   - [ ] Begin documentation in `docs/research-notes/`
   - [ ] Add initial data to `data/raw/` if available
   
5. **Optional Customizations**:
   - [ ] Update `.vscode/settings.json` for personal preferences
   - [ ] Modify `CONTRIBUTING.md` if working with collaborators
   - [ ] Add project-specific patterns to `.gitignore`

The template is designed so you can start research immediately while maintaining professional standards!