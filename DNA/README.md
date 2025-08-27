# DNA Manipulation Protocols

This directory contains protocols for DNA cloning, mutagenesis, and molecular manipulation techniques.

## Available Protocols

### Mutagenesis
- **[Site-Directed Mutagenesis](./Site-Directed-Mutagenesis.md)** - Targeted introduction of point mutations or small insertions/deletions
- **[Megaprimer Mutagenesis](./Megaprimer-Mutagenesis.md)** - Method for introducing larger fragments or multiple mutations

### Cloning
- **[Restriction Enzyme Cloning](./Restriction-Enzyme-Cloning.md)** - Traditional cut-and-paste cloning using restriction enzymes and ligase

### DNA Purification
- **[DNA Fragment Isolation](./DNA-Fragment-Isolation-from-Gel-B.md)** - Gel extraction and purification of DNA fragments

## Protocol Selection Guide

### Mutagenesis Methods
- **Site-directed mutagenesis**: Best for single point mutations or small changes (<20 bp)
- **Megaprimer mutagenesis**: Suitable for larger insertions, deletions, or multiple mutations

### Cloning Approaches
- **Restriction cloning**: Reliable traditional method, requires compatible restriction sites
- Consider Gibson assembly or other modern methods for seamless cloning (protocols may be added)

## General Guidelines

### Planning
- Design primers carefully with appropriate melting temperatures
- Check for secondary structures and primer dimers
- Verify restriction sites don't cut within your insert
- Plan appropriate controls for each experiment

### Quality Control
- Sequence verify all constructs before use
- Use high-fidelity polymerases for PCR steps
- Gel-purify DNA fragments to remove contaminants
- Transform into high-efficiency competent cells

### Best Practices
- Use positive and negative controls
- Prepare fresh reagents when possible
- Document all primer sequences and plasmid maps
- Maintain proper storage conditions for enzymes and DNA

## Related Protocols

For upstream work:
- [Molecular Biology](../Molecular-Biology/) - Competent cells and transformation
- [Buffers](../Buffers/) - Buffer and media preparation

For downstream applications:
- [Protein expression](../Protein/) - Using cloned constructs for protein production

## Troubleshooting Resources

Common issues and solutions:
- Low transformation efficiency → Check competent cell quality
- No colonies after ligation → Verify insert:vector ratio and enzyme activity
- Wrong sized bands → Check primer design and PCR conditions
- Multiple bands → Optimize annealing temperature and primer specificity