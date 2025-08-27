# Protocol Template

Use this template when creating new protocols to maintain consistency across the repository.

## YAML Frontmatter

Add the following metadata block at the top of every protocol file:

```yaml
---
tags:
  - protocol
  - [category1]
  - [category2]
  - [specific-technique]
category: [main-category]
---
```

**Categories:**
- `protein` - Protein expression, purification, activity
- `molbio` - Molecular biology, cloning, transformation
- `chemistry` - Analytical chemistry, metal analysis
- `biophysics` - Spectroscopy, biophysical characterization
- `dna` - DNA manipulation, mutagenesis
- `buffers` - Buffer and media preparation
- `education` - Educational/outreach protocols

## Standard Protocol Structure

```markdown
# Protocol Title

**Last Updated**: YYYY-MM-DD
**Authors**: [Your name]
**Duration**: [Estimated time]
**Difficulty**: [Beginner/Intermediate/Advanced]

## Introduction
Brief description of the protocol purpose and applications.

## Materials and Equipment

### Chemicals
- List all chemicals with concentrations
- Include catalog numbers if specific brands required

### Equipment
- List required instruments
- Include any special setup requirements

### Solutions (prepare fresh)
- Solution 1: Recipe
- Solution 2: Recipe

## Procedure

### Day 1 (if multi-day protocol)
1. Step-by-step instructions
2. Include timing estimates for each step
3. Add safety notes where relevant

### Day 2
Continue with clear, numbered steps...

## Expected Results
Describe what success looks like and typical yields/outcomes.

## Troubleshooting

| Problem | Possible Cause | Solution |
|---------|----------------|----------|
| Issue 1 | Cause | Fix |
| Issue 2 | Cause | Fix |

## Notes
- Additional tips and tricks
- Important considerations
- References to related protocols

## Related Protocols
- [Related Protocol 1](./path-to-protocol.md)
- [Related Protocol 2](../Category/protocol.md)
```

## Style Guidelines

### Formatting
- Use clear, descriptive headings
- Include timing estimates in italics: *5 min*
- Use **bold** for important warnings
- Use bullet points for lists
- Number procedure steps clearly

### Content Guidelines
- Write in imperative voice ("Add solution" not "Solution is added")
- Include safety warnings where appropriate
- Provide troubleshooting for common issues
- Cross-reference related protocols
- Include expected results/outcomes

### Chemical Notation
- Use proper chemical formulas (H₂O, CO₂, etc.)
- Include concentrations and volumes
- Specify grades of chemicals when important

### File Naming
- Use descriptive, hyphenated names
- Avoid spaces and special characters
- Follow existing naming conventions in each directory

## Review Checklist

Before submitting a new protocol:
- [ ] YAML frontmatter is complete and correct
- [ ] All sections are filled out appropriately
- [ ] Timing estimates are included
- [ ] Safety considerations are noted
- [ ] Troubleshooting section is helpful
- [ ] Related protocols are cross-referenced
- [ ] File is saved in appropriate directory
- [ ] Filename follows naming conventions