# Sociobiodiversity Data Standard

A vocabulary and data standard for organizing and sharing information about sociobiodiversity, integrating scientific names, vernacular names, and traditional uses of species within their cultural and ecological contexts.

## Overview

This project develops a standardized framework for documenting sociobiodiversity—the variety and relationships between biological resources, associated traditional knowledge, cultural practices, and human communities. The standard aligns with international frameworks including the Darwin Core, the Nagoya Protocol, and CARE Principles for Indigenous Data Sovereignty.

## Key Features

- **Comprehensive Terminology**: Defines terms for species, traditional uses, knowledge holders, and cultural practices
- **Multilingual Support**: Framework for supporting multiple languages and vernacular names
- **Standards Alignment**: Compatible with Darwin Core, GBIF, and international biodiversity standards
- **Community-Driven**: Developed collaboratively with indigenous communities and biodiversity specialists
- **Ethical Framework**: Incorporates access and benefit-sharing principles

## Project Structure

```
├── vocabulary/          # Core vocabulary definitions (term_versions.csv)
├── build/              # Scripts and tools for generating outputs
├── dist/               # Generated outputs (XML, CSV formats)
├── docs/               # Documentation and website content (Jekyll)
├── reports/            # Implementation guides and technical documentation
├── .github/            # Community guidelines and contribution guides
└── README.md           # This file
```

### Directory Descriptions

- **vocabulary/**: Contains the authoritative vocabulary source file (`term_versions.csv`) with the complete history of all terms
- **build/**: Python scripts, Jupyter notebooks, and templates for processing vocabulary and generating documentation
- **dist/**: Auto-generated distribution files in various formats (not edited manually)
- **docs/**: Markdown source files for the Jekyll documentation site
- **reports/**: Technical implementation documentation and case studies

## Use Cases

1. **Scientific Research**: Document species interactions with traditional knowledge systems
2. **Conservation Planning**: Integrate traditional ecological knowledge with biodiversity conservation
3. **Policy Development**: Support implementation of access and benefit-sharing frameworks
4. **Data Standardization**: Enable interoperability of sociobiodiversity databases across regions
5. **Community Empowerment**: Protect and formalize traditional knowledge

## Getting Started

### Basic Vocabulary Access

The vocabulary is defined in `vocabulary/term_versions.csv`. Key term categories include:

- **Core Concepts**: Sociobiodiversity, Indigenous Knowledge, Biocultural Heritage
- **Taxonomy**: Scientific Name, Vernacular Name, Taxonomic Classification
- **Traditional Uses**: Medicinal, Food, Ritual, Craft, and Agricultural applications
- **Knowledge Systems**: Traditional Knowledge, Customary Practices, Cultural Values
- **Governance**: Access and Benefit Sharing, Intellectual Property Rights, Protocols

### Viewing Terms

To view available terms, check the generated documentation files in `dist/` or visit the website documentation in `docs/`.

## Contributing

We welcome contributions from researchers, indigenous communities, conservation practitioners, and data specialists. Please see [CONTRIBUTING.md](.github/CONTRIBUTING.md) for guidelines.

### Types of Contributions

- New terms or improvements to existing terminology
- Documentation and case studies
- Translations and multilingual adaptations
- Implementation experiences and feedback
- Code improvements and build scripts

## Ethical Principles

This project adheres to:

- **CARE Principles**: Collective Benefit, Authority to Decide, Responsibility, Ethics
- **Nagoya Protocol**: Fair and equitable benefit-sharing from genetic resources
- **Free, Prior, and Informed Consent (FPIC)**: Respect for community rights and knowledge
- **Open Access**: While respecting cultural sensitivities and community protocols

## Related Standards

- [Darwin Core](https://dwc.tdwg.org/) - Biodiversity data standard
- [Nagoya Protocol](https://www.cbd.int/abs/) - Access and benefit-sharing framework
- [GBIF](https://www.gbif.org/) - Global biodiversity information facility
- [WIPO](https://www.wipo.int/) - Intellectual property protection

## References

The development of this standard was informed by:

1. **CESP-SIBBR Project**: Collaborative effort to create data standards for socio-biodiversity in Brazil (2024-2026)
2. **SIBBR Network**: Sistema de Informação sobre a Biodiversidade Brasileira
3. **TDWG Community**: Taxonomic Databases Working Group standards

## License

This work is licensed under the Creative Commons Attribution 4.0 International License.

You are free to:
- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material for any purpose, even commercially

Provided you give appropriate credit and indicate any changes made.

See [LICENSE](LICENSE) for full details.

## Contact and Support

For questions, suggestions, or to contribute:

- Open an issue on GitHub
- Check the [documentation](docs/) for detailed guides
- Review case studies in [reports/](reports/) for implementation examples

## Acknowledgments

This project was developed with support from:
- Sistema de Informação sobre a Biodiversidade Brasileira (SIBBR)
- Taxonomic Databases Working Group (TDWG)
- Biodiversity Heritage Library
- Indigenous communities and traditional knowledge holders
- Conservation and research institutions across South America

---

**Current Version**: 1.0
**Last Updated**: November 2024
