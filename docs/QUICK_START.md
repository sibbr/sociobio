# Quick Start Guide

## Welcome to the Sociobiodiversity Data Standard Project

This guide will help you quickly understand the project structure and get started with using or contributing to the socio-biodiversity extension.

## What is This Project About?

The Sociobiodiversity Data Standard is an international collaborative project developing a Darwin Core extension to document and standardize information about:

- **Species**: Scientific names, vernacular names, and taxonomic information
- **Traditional Uses**: How indigenous and local communities use biological resources
- **Knowledge Holders**: Attribution to communities and traditional knowledge keepers
- **Cultural Context**: The practices and beliefs associated with species use

## Project Structure

### Quick Navigation

```
sociobio/
├── docs/
│   ├── QUICK_START.md          ← You are here
│   ├── TASK_GROUP.md            ← About the TDWG Task Group
│   ├── DARWIN_CORE_EXTENSION.md ← Extension technical details
│   └── [other documentation]
├── vocabulary/
│   └── term_versions.csv        ← Core vocabulary definitions
├── reports/
│   ├── PROJECT_CONTEXT.md       ← GBIF/CESP project details
│   ├── CASE_STUDIES_OVERVIEW.md ← Validation case studies
│   └── [implementation guides]
├── build/                       ← Scripts for generating outputs
├── dist/                        ← Generated distribution files
└── README.md                    ← Project overview
```

## Key Concepts

### 1. Sociobiodiversity

The integration of biological resources, traditional knowledge, and cultural practices within community contexts.

**Example**: An indigenous community's knowledge about medicinal plants, how to use them, and the spiritual practices associated with them.

### 2. Darwin Core Extension

A standardized addition to the Darwin Core schema (the international standard for biodiversity data) that allows documentation of traditional knowledge.

### 3. Traditional Knowledge Attribution

Proper recognition of communities and individuals who hold and practice traditional knowledge.

## Who Should Use This Project?

### Data Providers
- Researchers documenting traditional knowledge
- Communities sharing their biodiversity knowledge
- Biodiversity information systems
- National and regional data centers

### Data Users
- Conservation organizations
- Policy makers
- Researchers and educators
- Indigenous organizations

### Contributors
- Standard developers
- Community representatives
- Software developers
- Documentation specialists

## Getting Started Steps

### Step 1: Understand the Context

1. Read the [README.md](../README.md) for project overview
2. Review [PROJECT_CONTEXT.md](../reports/PROJECT_CONTEXT.md) for GBIF/CESP project details
3. Check [TASK_GROUP.md](TASK_GROUP.md) to learn about participating organizations

### Step 2: Learn the Standard

1. Review [DARWIN_CORE_EXTENSION.md](DARWIN_CORE_EXTENSION.md) for technical specifications
2. Examine `vocabulary/term_versions.csv` to see defined terms
3. Read [CASE_STUDIES_OVERVIEW.md](../reports/CASE_STUDIES_OVERVIEW.md) for implementation examples

### Step 3: Choose Your Role

#### If you want to USE the standard:

1. Review the [Implementation Guide](IMPLEMENTATION_GUIDE.md) (coming soon)
2. Look at case study examples in `/reports/`
3. Contact the task group for support

#### If you want to CONTRIBUTE:

1. Read [CONTRIBUTING.md](../.github/CONTRIBUTING.md)
2. Review open issues on GitHub
3. Contact the convenors to discuss your contribution

#### If you represent a COMMUNITY:

1. Review the [Community Guidelines](COMMUNITY_GUIDELINES.md) (coming soon)
2. Contact task group convenors
3. Discuss how your knowledge can be documented

## Key Terms to Know

| Term | Meaning |
|------|---------|
| **Darwin Core** | International standard for biodiversity data |
| **Extension** | Standardized additions to Darwin Core |
| **Traditional Knowledge** | Knowledge developed by communities over generations |
| **Knowledge Holder** | Person or community custodian of traditional knowledge |
| **FPIC** | Free, Prior, and Informed Consent |
| **Vernacular Name** | Common or local name for a species |
| **Taxonomy** | Scientific classification of organisms |
| **TDWG** | Taxonomic Databases Working Group |
| **GBIF** | Global Biodiversity Information Facility |

## Important Principles

### 1. Community Rights
- Communities must give permission (FPIC) before documenting their knowledge
- Communities should control how their knowledge is used
- Communities should benefit from uses of their knowledge

### 2. Ethical Practice
- Respect cultural protocols and restrictions
- Provide proper attribution and recognition
- Protect sensitive and sacred knowledge
- Follow international frameworks (Nagoya Protocol, CARE Principles)

### 3. Transparency
- Clear documentation of data sources
- Traceable information about who provided data
- Public access to non-sensitive information
- Open collaboration processes

## Finding Help

### Documentation
- **Technical Details**: See [DARWIN_CORE_EXTENSION.md](DARWIN_CORE_EXTENSION.md)
- **Project Context**: See [PROJECT_CONTEXT.md](../reports/PROJECT_CONTEXT.md)
- **Contributing**: See [CONTRIBUTING.md](../.github/CONTRIBUTING.md)

### People to Contact

**Project Convenors:**
- Clara Baringo Fonseca (clara.fonseca@consultores.rnp.br)
- Viviane Stern da Fonseca-Kruel (vivianekruel@gmail.com)

**GitHub Issues:** https://github.com/sibbr/cesp-sibbr-2024/issues

### Resources

- **GBIF Project**: https://www.gbif.org/project/CESP2024-015/
- **SiBBr Project**: https://www.sibbr.gov.br/page/cesp/cesp-2024.html
- **GitHub Repository**: https://github.com/sibbr/cesp-sibbr-2024/
- **TDWG Website**: http://www.tdwg.org

## Common Questions

### Q: Is this only for plants?
**A**: No. Initial case studies focused on plants, but the extension is designed to work with all organisms including animals and microorganisms.

### Q: Do communities have to share their knowledge?
**A**: No. Participation is voluntary. Communities decide what information to share and under what conditions.

### Q: How is sensitive knowledge protected?
**A**: The extension includes mechanisms for marking sensitive or restricted information. Communities can specify access restrictions.

### Q: Can I use this for commercial purposes?
**A**: The extension documents benefit-sharing agreements. Commercial use requires agreement from knowledge holders.

### Q: Is this open source?
**A**: Yes. The project is open and collaborative, but respects community intellectual property rights.

## Next Steps

1. **Explore the repository** - Browse files to understand the project structure
2. **Read relevant documentation** - Based on your role and interests
3. **Check open issues** - See current discussions and opportunities to contribute
4. **Contact the team** - Reach out with questions or ideas
5. **Get involved** - Contribute in whatever way fits your expertise

## Learning Resources

### About Darwin Core
- [Darwin Core Quick Reference](https://dwc.tdwg.org/)
- [Darwin Core Standard](https://www.tdwg.org/standards/dwc/)

### About Ethical Data Practices
- [CARE Principles](https://www.gida-global.org/care)
- [Nagoya Protocol Guide](https://www.cbd.int/abs/)

### About Traditional Knowledge
- [WIPO Traditional Knowledge](https://www.wipo.int/tk/en/)
- [UNESCO Intangible Heritage](https://ich.unesco.org/)

### About Biodiversity Standards
- [GBIF Data Standards](https://www.gbif.org/data-standards-and-best-practices)
- [TDWG Standards](https://www.tdwg.org/standards/)

## Contributing Ideas

Have an idea or want to contribute? Here are some ways:

- **Report Issues**: Found a problem? Open a GitHub issue
- **Suggest Improvements**: Have ideas? Share them in discussions
- **Share Case Studies**: Implementing the standard? Share your experience
- **Improve Documentation**: Help make guides clearer and better
- **Translate Content**: Help make project accessible in multiple languages
- **Develop Tools**: Create software to support the standard

## Project Timeline

- **Current Phase**: Foundation and Planning (Dec 2024 - Feb 2025)
- **Next Phase**: Community Consultation and Design (Jan - Apr 2025)
- **Completion**: March 2026

---

**For more information**: Visit the project repository and contact the task group convenors.

**Last Updated**: November 2024
