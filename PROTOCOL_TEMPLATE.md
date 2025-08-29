# Protocol Template

This template provides a standardized structure for creating new protocols in this repository. Using this template ensures consistency and improves discoverability.

## YAML Frontmatter Template

```yaml
---
tags:
  - protocol
  - [category]           # e.g., protein, dna, chemistry, etc.
  - [technique]          # e.g., expression, cloning, spectroscopy
  - [specific-method]    # e.g., PCR, Bradford, FTIR
category: [category]     # primary category (protein, dna, molbio, chemistry, biophysics, buffers)
---
```

## Protocol Structure Template

```markdown
---
tags:
  - protocol
  - [category]
  - [technique]
category: [category]
---
# Protocol Title

**Last Updated**: YYYY-MM-DD  
**Authors**: Author Name(s)  
**Instrument Responsible**: [Name](contact-link) *(if applicable)*

## Introduction

Brief description of the protocol purpose, background, and when to use it.

Key points to include:
- What this protocol accomplishes
- When it should be used
- Any important background information
- Expected time investment
- Safety considerations

## Materials and Equipment

### Equipment
- List major equipment needed
- Include model numbers if specific equipment is required
- Note any booking requirements

### Reagents and Chemicals
- List all chemicals with concentrations
- Include catalog numbers for specific products
- Note any special storage requirements

### Consumables
- Pipet tips, tubes, plates, etc.
- Quantities needed for typical batch size

## Procedure

### Preparation (Time estimate)
1. Pre-protocol setup steps
2. Solution preparation
3. Equipment preparation

### Main Protocol (Time estimate)
1. Step-by-step instructions
2. Include timing for each major step
3. Note critical steps with **bold** text
4. Include incubation times and temperatures
5. Add break points where protocol can be paused

#### Subsection for Complex Steps
- Break down complex procedures
- Include troubleshooting tips inline
- Note alternative approaches

### Cleanup (Time estimate)
1. Equipment cleanup
2. Waste disposal
3. Storage of products

## Expected Results

- What to expect from a successful protocol
- Typical yields, concentrations, or measurements
- Quality control checks

## Troubleshooting

| Problem | Possible Cause | Solution |
|---------|---------------|----------|
| Issue 1 | Cause 1 | Solution 1 |
| Issue 2 | Cause 2 | Solution 2 |

## Notes

- Important observations
- Protocol optimization tips
- Alternative methods or modifications
- Safety reminders
- Literature references

## Related Protocols

- [Related Protocol 1](link)
- [Related Protocol 2](link)

## References

1. Reference 1
2. Reference 2
```

## Tagging Guidelines

### Primary Categories
- `protein` - Protein expression, purification, analysis
- `dna` - DNA manipulation, cloning, mutagenesis
- `molbio` - Molecular biology techniques
- `chemistry` - Analytical chemistry, assays
- `biophysics` - Biophysical characterization
- `buffers` - Buffer and media preparation

### Common Technique Tags
- `expression` - Protein expression protocols
- `purification` - Protein purification methods
- `cloning` - DNA cloning techniques
- `mutagenesis` - Mutagenesis methods
- `transformation` - Bacterial transformation
- `assay` - Activity or analytical assays
- `spectroscopy` - Spectroscopic methods
- `analytical` - Analytical techniques

### Specific Method Tags
Use specific tags for the exact method:
- `PCR`, `qPCR`, `RT-PCR`
- `FTIR`, `EPR`, `ICP-OES`
- `Bradford`, `BCA`, `Lowry`
- `SDS-PAGE`, `Native-PAGE`
- `IPTG-induction`, `arabinose-induction`

## File Naming Convention

- Use descriptive names with hyphens: `Protein-Expression-BL21.md`
- Include method if specific: `Site-Directed-Mutagenesis-QuikChange.md`
- Add version or author suffix if needed: `Competent-Cells-B.md` (B for Briggi)

## Metadata Best Practices

1. **Keep update dates current** - Update whenever protocol is modified
2. **Credit all contributors** - Include original authors and those who made modifications
3. **Use consistent tag vocabulary** - Check existing protocols for tag conventions
4. **Fill all required fields** - Don't leave empty categories or missing information
5. **Add timing estimates** - Help users plan their experiments
6. **Include safety information** - Note hazards and safety requirements

## Quality Checklist

Before submitting a new protocol, ensure:

- [ ] YAML frontmatter is properly formatted
- [ ] All required metadata fields are filled
- [ ] Tags are relevant and follow conventions
- [ ] Step-by-step procedure is clear and detailed
- [ ] Timing estimates are included
- [ ] Materials list is complete
- [ ] Troubleshooting section addresses common issues
- [ ] Related protocols are cross-referenced
- [ ] Safety considerations are noted
- [ ] Protocol has been tested and validated

---

*For questions about protocol formatting or to suggest improvements to this template, please contact the repository maintainers.*