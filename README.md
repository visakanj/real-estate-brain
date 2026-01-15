# Real Estate Brain

A shared knowledge base for our real estate investing team, focused on the Durham-Raleigh Triangle market. This repository feeds into our AI-powered real estate coach to help us make informed investment decisions.

## Purpose

This repo serves as our team's collective brain for real estate investing. Everything we learn—from podcasts, courses, market research, deal analysis, and team discussions—lives here. Our AI coach (powered by Claude) uses this knowledge to give us contextual, personalized guidance.

## Team

- **Visakan** - [Your role]
- **[Wife's name]** - [Her role]
- **[Brother-in-law's name]** - [His role]

## Repository Structure

```
real-estate-brain/
├── knowledge/
│   ├── _system-prompt.md      # How our AI coach behaves
│   ├── _team-context.md       # Our team's goals, criteria, and situation
│   ├── strategies/            # Investment strategy breakdowns
│   ├── podcasts/              # Podcast summaries and key insights
│   ├── market-research/       # Triangle market data and neighborhood info
│   ├── deals/                 # Deal analyses (templates and examples)
│   ├── financing/             # Loan types, lenders, financing strategies
│   ├── courses/               # Notes from courses and books
│   └── meetings/              # Team meeting notes and decisions
├── templates/                 # Templates for adding new content
└── README.md                  # You are here
```

## How to Add Content

### Adding a Podcast Summary

1. Go to `templates/podcast-summary-template.md` and copy the contents
2. Create a new file in `knowledge/podcasts/` with a descriptive name (e.g., `bp-episode-123-house-hacking.md`)
3. Fill out the template with your notes
4. Commit and push (see Git instructions below)

### Adding Deal Analysis

1. Copy `templates/deal-analysis-template.md`
2. Create a new file in `knowledge/deals/` (e.g., `123-main-st-durham.md`)
3. Fill out the analysis
4. Commit and push

### Adding Meeting Notes

1. Copy `templates/meeting-notes-template.md`
2. Create a new file in `knowledge/meetings/` (e.g., `2024-01-15-weekly-sync.md`)
3. Fill out during/after the meeting
4. Commit and push

### Adding Other Content

For market research, financing info, or strategy notes—just create a markdown file in the appropriate folder. Use clear, descriptive filenames.

## Git Quick Reference (for non-technical teammates)

### First-time setup (do once)
```bash
git clone https://github.com/visakanj/real-estate-brain.git
cd real-estate-brain
```

### Adding new content
```bash
# See what files you've changed/added
git status

# Add your changes
git add .

# Commit with a descriptive message
git commit -m "Add podcast summary for BP episode on house hacking"

# Push to GitHub
git push
```

### Getting latest changes from teammates
```bash
git pull
```

## Tips for Good Knowledge Entries

- **Be specific**: Include numbers, dates, and sources
- **Extract insights**: Don't just transcribe—pull out what's actionable for us
- **Connect the dots**: Reference other files when topics relate
- **Include your take**: Add your own analysis and questions
- **Keep it scannable**: Use headers, bullet points, and bold text

## AI Coach Integration

The files in `knowledge/` are used to give our AI coach context about:
- Our team's specific situation and goals
- What we've learned from various sources
- Our investment criteria and risk tolerance
- Past deals we've analyzed
- Decisions we've made as a team

This means the more we add here, the better our coach can help us.

---

*Built with love for the Triangle real estate market*
