# Contributing to the Sociobiodiversity Data Standard

Thank you for your interest in contributing to this project! We welcome participation from researchers, indigenous communities, conservation practitioners, and data specialists from around the world.

## Our Values

We are committed to:
- **Respect**: Honoring the rights and knowledge of indigenous and local communities
- **Inclusivity**: Creating space for diverse perspectives and ways of knowing
- **Transparency**: Open communication and clear documentation
- **Ethical Stewardship**: Protecting sensitive cultural and biological information

## Types of Contributions

### 1. Vocabulary Enhancements

- **New Terms**: Propose new terms for sociobiodiversity concepts
- **Term Improvements**: Suggest refinements to existing definitions
- **Multilingual Support**: Add translations and vernacular terminology
- **Standards Alignment**: Integrate with other emerging standards

### 2. Documentation

- Case studies from your region or work
- Implementation guides and tutorials
- Best practices for data collection
- Integration examples with existing systems

### 3. Technical Contributions

- Build scripts and automation tools
- Export formats and templates
- Data validation tools
- Integration with other platforms (GBIF, Darwin Core, etc.)

### 4. Community Engagement

- Feedback from your organization or community
- Use case documentation
- Workshops and training materials
- User experiences and lessons learned

## Contribution Process

### Before You Start

1. **Check Existing Issues**: See if your suggestion or issue already exists
2. **Review Standards**: Familiarize yourself with Darwin Core, Nagoya Protocol, and CARE Principles
3. **Community Consultation**: For changes affecting cultural knowledge, consult relevant communities

### Making a Contribution

1. **Fork the Repository**: Create your own copy of the project
2. **Create a Branch**: Use a descriptive branch name (e.g., `add-medicinal-plants-terms`)
3. **Make Your Changes**:
   - For vocabulary: Edit `vocabulary/term_versions.csv` or propose changes
   - For documentation: Add/modify files in `docs/` or `reports/`
   - For code: Add Python scripts to `build/` with clear documentation
4. **Document Your Changes**: Include description of what and why
5. **Submit a Pull Request**: Include:
   - Clear description of changes
   - Reference to related issues
   - Testing or validation performed
   - Any community consultations conducted

### Vocabulary Term Format

When adding new terms to `vocabulary/term_versions.csv`:

```
term_id,term_name,term_definition,term_type,version,date_issued,status,subject_area,related_standards
SBD_XXX,Term_Name,"Clear, concise definition in English",Concept/Term,1.0,YYYY-MM-DD,active,CategoryName,"Related Standard 1, Related Standard 2"
```

**Guidelines**:
- Use descriptive term IDs (e.g., SBD_001)
- Write definitions that are clear to both specialists and practitioners
- Include cultural context when relevant
- Reference related standards
- Add appropriate subject area classification

### Documentation Standards

- Use clear, accessible English
- Include examples from real-world applications
- Provide context for technical concepts
- Link to related resources and standards

### Code Contributions

- Include docstrings and comments
- Test your code with sample data
- Follow Python best practices (PEP 8)
- Document external dependencies

## Ethical Considerations

### Protecting Traditional Knowledge

- **Obtain Consent**: Always get free, prior, and informed consent (FPIC) from knowledge holders
- **Attribution**: Properly credit indigenous and local communities
- **Benefit Sharing**: Discuss how benefits from knowledge use will be shared
- **Sensitivity**: Respect confidentiality of sacred or restricted knowledge
- **Protocols**: Follow community-established protocols for knowledge sharing

### Inclusive Participation

- Accommodations: Request any accessibility needs
- Language: We can work with translators
- Time: Be respectful of different time zones and availability
- Format: Flexible options for participation (written, oral, visual)

## Review Process

### What to Expect

1. **Initial Review**: We check for completeness and alignment with project goals
2. **Substantive Review**: Community and technical experts review the content
3. **Community Consultation**: For significant changes, we may consult broader communities
4. **Feedback**: You'll receive constructive feedback and suggestions
5. **Revision**: Work with reviewers to refine your contribution
6. **Acceptance**: Once approved, your contribution is merged

### Timeline

- Simple changes (documentation): 1-2 weeks
- Vocabulary additions: 2-4 weeks (may require community consultation)
- Technical contributions: 2-4 weeks
- Major changes: 4-8 weeks (includes community engagement)

## Getting Help

- **Questions**: Open an issue with the "question" label
- **Ideas**: Start a discussion in the "Discussions" section
- **Problems**: Report bugs with the "bug" label
- **Guidance**: Ask about contributing style and standards

## Code of Conduct

All contributors agree to:
- Treat others with respect and dignity
- Welcome diverse perspectives and backgrounds
- Address conflicts constructively
- Report concerning behavior to project maintainers

## Recognition

We recognize all contributions! Contributors will be:
- Listed in project documentation
- Acknowledged in release notes
- Credited appropriately for translations or specialized work

## Questions?

If you have questions about contributing, please:
1. Check this guide and project documentation
2. Open an issue with your question
3. Contact project maintainers

---

Thank you for helping build a more inclusive and equitable approach to biodiversity data!
