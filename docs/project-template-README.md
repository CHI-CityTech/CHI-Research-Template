# CHI Research Project Board Template

## Overview

This project board template supports the **CHI (Center for Holistic Integration) research methodology** using a structured Kanban workflow combined with SRDMPA phase tracking through issue labels.

## Board Structure

### 5-Column Kanban Workflow

| Column | Purpose | Description |
|--------|---------|-------------|
| 📋 **Backlog** | Ready Tasks | Refined issues ready for assignment |
| 👤 **Assigned** | Committed Work | Tasks assigned and ready to start |
| ⚡ **Active** | In Progress | Currently active work (limit 2-3 items) |
| 🔵 **Review** | Quality Control | Work ready for faculty/peer review |
| ✅ **Done** | Completed | Finished and assessed work |

## SRDMPA Methodology Integration

Research phases are tracked through **issue labels**, not board columns:

- `01-speculate` - Research questions, hypotheses, initial ideas
- `02-research` - Literature review, data collection, investigation  
- `03-design` - Planning experiments, designing methods, prototyping
- `04-make` - Implementation, coding, data analysis, creation
- `05-publish` - Documentation, writing, presentation preparation
- `06-assess` - Evaluation, reflection, iteration planning

## Workflow Examples

### Individual Research Project
```
Speculation → Create Issue → Backlog → Assign to Self → Research → Active → Review → Assess → Done
```

### Team Research Project  
```
Team Meeting → Prioritize Backlog → Faculty Assigns → Student Works → Submit for Review → Complete
```

## Getting Started

### 1. Create Your Research Issues

Use the **CHI Issue Templates**:
- **Milestone** - Define concrete deliverables and acceptance criteria
- **Research Log** - Weekly notes, sources, and phase tracking
- **AI Collaboration Report** - Document AI tool usage and contributions
- **Bug Report** - Technical issues and debugging tasks

### 2. Apply SRDMPA Labels

Tag each issue with the appropriate research phase:
```markdown
- Milestone: "Complete literature review analysis" → 01-speculate + 02-research
- Research Log: "Week 23-15 AI bias investigation" → 02-research  
- Milestone: "Build bias detection prototype" → 03-design + 04-make
- Research Log: "Week 23-16 Statistical analysis" → 04-make
- Milestone: "Draft conference paper" → 05-publish
- Research Log: "Week 23-17 Reflection on methods" → 06-assess
```

### 3. Move Issues Through Columns

**Backlog → Assigned:**
- During weekly planning meetings
- When committing to work for the sprint/week
- Self-assignment for individual projects

**Assigned → Active:**  
- When actually starting the work
- Limit to 2-3 active items to maintain focus

**Active → Review:**
- When work is complete and needs feedback
- Research methodology validation required
- Documentation/code review needed

**Review → Done:**
- After faculty/peer approval
- Quality standards met
- Ready to build upon for next phase

## Best Practices

### For Students
- **Start with speculation** - Create issues with `01-speculate` for all research ideas
- **Limit active work** - Keep 2-3 items in Active column maximum  
- **Seek review actively** - Move work to Review column when ready for feedback
- **Update labels** - Add new SRDMPA phase labels as work evolves
- **Weekly planning** - Review and assign upcoming work during meetings

### For Faculty Advisors
- **Review backlog priorities** - Help students focus on high-impact work
- **Provide timely feedback** - Monitor Review column for work needing attention
- **Track methodology** - Ensure SRDMPA phases are properly represented
- **Celebrate completion** - Acknowledge work moving to Done column

### For Research Teams
- **Collaborative planning** - Use weekly meetings to assign from backlog
- **Clear ownership** - One person per assigned issue
- **Cross-review** - Team members can review each other's work
- **Knowledge sharing** - Comment on issues to share insights

## Integration with Repository

This project board works seamlessly with:
- **CHI Issue Templates** - Structured issue creation
- **SRDMPA Labels** - Automated via repository template
- **GitHub Actions** - Automated project setup and linking
- **Documentation Standards** - Issue tracking supports reproducible research

## Troubleshooting

**Common Issues:**

**"Too many columns don't fit on screen"**
- Use browser zoom out (Ctrl/Cmd + -)
- Focus on 2-3 relevant columns at a time
- Use GitHub's column collapse feature

**"Issues stuck in Review"** 
- Set review SLAs (e.g., 48 hours for feedback)
- Use `needs-review` label to highlight urgency
- Schedule regular review sessions

**"Backlog becomes overwhelming"**
- Regular backlog grooming sessions
- Archive or close outdated issues  
- Focus on current research priorities

**"Individual projects don't need Assigned column"**
- Use it for personal commitment ("This week I will...")
- Self-assignment creates accountability
- Can skip directly to Active if preferred

## Support

For questions about this project board template:
- Review CHI Research Template documentation
- Contact CHI faculty advisors
- Reference GitHub Projects documentation
- Check CHI methodology resources

---

**Template Version:** 1.0  
**Last Updated:** September 2025  
**Maintained by:** CHI Center for Holistic Integration, City Tech