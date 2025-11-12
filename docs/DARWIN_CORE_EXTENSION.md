# Darwin Core Extension for Socio-Biodiversity

## Overview

The Socio-Biodiversity Extension is a standardized addition to the Darwin Core schema designed to document and represent species information linked to traditional knowledge regarding biodiversity use practices and benefits.

## Extension Rationale

Traditional biodiversity knowledge held by indigenous and local communities represents centuries of accumulated research and validation. However, this knowledge is often documented separately from formal biodiversity databases, creating:

- **Fragmentation**: Traditional knowledge isolated from species data
- **Attribution Loss**: Inadequate credit to knowledge holders and communities
- **Interoperability Issues**: Inconsistent data formats across systems
- **Legal Risks**: Potential violations of access and benefit-sharing requirements
- **Knowledge Loss**: Risk of information disappearing as communities change

This extension bridges these gaps by providing standard terms and structures for integrating traditional knowledge with biodiversity data.

## Core Principles

### 1. Ethical Data Handling
- Respect for community rights and intellectual property
- Implementation of CARE Principles (Collective Benefit, Authority to Decide, Responsibility, Ethics)
- Protection of sensitive and sacred knowledge

### 2. Traceability
- Clear documentation of information sources
- Attribution to knowledge holders and communities
- Maintenance of chain of custody for knowledge

### 3. Interoperability
- Alignment with existing biodiversity standards
- Compatibility with GBIF and national data systems
- Support for multilingual and multicultural contexts

### 4. Legal Compliance
- Adherence to Nagoya Protocol requirements
- Support for access and benefit-sharing arrangements
- Respect for Free, Prior, and Informed Consent (FPIC)

### 5. Sustainability
- Long-term preservation of traditional knowledge
- Community involvement in maintenance and evolution
- Integration into formal information systems

## Extension Structure

### Primary Classes

#### 1. Traditional Use (tbUse)
Documents how a biological resource is used by communities, including:

- **Use Category**: Type of use (medicinal, food, ritual, craft, agricultural, etc.)
- **Use Description**: Detailed description of application
- **Cultural Context**: Community or cultural group context
- **Usage Practice**: Methods and techniques employed
- **Frequency**: Regularity or seasonality of use
- **Evidence Level**: Basis of documentation (empirical, traditional, scientific validation, etc.)

#### 2. Knowledge Holder (tbKnowledgeHolder)
Identifies and credits custodians of traditional knowledge:

- **Holder Type**: Individual, family, community, or organization
- **Identity Information**: Name or identifier (with privacy considerations)
- **Affiliation**: Community, region, or institutional affiliation
- **Expertise**: Areas of knowledge specialization
- **Consent Status**: FPIC documentation status

#### 3. Community Protocol (tbCommunityProtocol)
Documents agreements and guidelines for knowledge sharing:

- **Protocol Type**: Type of agreement (benefit-sharing, access terms, etc.)
- **Effective Date**: When protocol became active
- **Terms**: Specific conditions for data use
- **Attribution Requirements**: How knowledge holders must be credited
- **Benefit Sharing Arrangements**: How benefits are distributed

#### 4. Cultural Context (tbCulturalContext)
Provides cultural and ecological context:

- **Cultural Practice**: Associated ritual or traditional practice
- **Ecological Knowledge**: Environmental insights embedded in use
- **Seasonal Information**: Timing relative to ecological cycles
- **Sacred or Restricted Information**: Flags for sensitive knowledge
- **Language**: Original language of knowledge documentation

### Supporting Classes

#### Benefit Sharing (tbBenefitSharing)
Documents benefit-sharing arrangements and outcomes:

- **Type of Benefit**: Monetary, capacity building, recognition, etc.
- **Beneficiary**: Organization or community receiving benefits
- **Date**: When benefit sharing occurred
- **Amount/Description**: Details of benefit
- **Status**: Completed, pending, or ongoing

#### Data Provenance (tbProvenance)
Tracks information sources and documentation history:

- **Source**: Original source of information
- **Collector**: Person who documented the information
- **Collection Date**: When information was collected
- **Documentation Method**: How information was gathered
- **Prior Permissions**: Documentation of FPIC and agreements

## Term Definitions

### Essential Terms

| Term | Definition |
|------|-----------|
| **Sociobiodiversity** | The variety and relationships between biological resources, associated traditional knowledge, cultural practices, and human communities that collectively form integrated systems. |
| **Traditional Knowledge** | Cumulative body of knowledge, practices, and beliefs developed by indigenous and local communities through generations of interaction with their environment. |
| **Traditional Use** | Application or practice of biological resources by indigenous peoples and local communities based on accumulated knowledge and cultural practices. |
| **Vernacular Name** | Common or traditional name given to a species by local, indigenous, or rural communities in their respective languages. |
| **Knowledge Holder** | A person, family, or community recognized as custodian and practitioner of traditional knowledge related to biological resources. |
| **Biocultural Heritage** | The integrated system of biological resources, ecological knowledge, cultural practices, and associated intellectual and cultural property of communities. |
| **Access and Benefit Sharing** | Regulatory framework ensuring fair and equitable distribution of benefits arising from the use of genetic resources and associated traditional knowledge. |

### Use Categories

- **Medicinal Use**: Application for healing, therapeutic, or medicinal purposes
- **Food Use**: Utilization as food, beverages, supplements, or nutritional sources
- **Ritual Use**: Application in ceremonial, spiritual, or religious practices
- **Craft Use**: Utilization in production of handicrafts and artisanal products
- **Agricultural Use**: Application in farming, cultivation, or pest management
- **Veterinary Use**: Application for animal health and care
- **Industrial Use**: Commercial or manufacturing applications

## Data Model Example

### Specimen with Traditional Use Information

```
Taxon:
  scientificName: Ocimum basilicum
  vernacularName: [
    "Holy Basil" (English),
    "Tulsi" (Hindi),
    "Manjericão" (Portuguese)
  ]

Traditional Uses:
  Use 1:
    useCategory: medicinal
    useDescription: "Decoction of leaves used for respiratory conditions, fever reduction, and digestive complaints"
    culturalContext: "Traditional Ayurvedic medicine in India"
    knowledgeHolder: "Ayurvedic practitioners and village healers"
    validationStatus: "Supported by scientific studies"

  Use 2:
    useCategory: ritual
    useDescription: "Sacred plant in Hindu temples, used in daily worship rituals"
    culturalContext: "Hindu religious practices"
    knowledgeHolder: "Hindu communities across Indian subcontinent"

  Use 3:
    useCategory: food
    useDescription: "Fresh leaves used as culinary herb in various traditional dishes"
    culturalContext: "South Asian cuisine"

CommunityProtocol:
  protocolType: "Traditional Knowledge Attribution Agreement"
  benefitSharingArrangement: "Research findings must be shared with communities; commercial use requires benefit-sharing agreement"
  attributionRequirement: "Must credit Ayurvedic tradition and knowledge holders in publications"

Provenance:
  originalSource: "Charaka Samhita (ancient Ayurvedic text), oral traditions"
  collectionDate: "2024-11-12"
  documentationMethod: "Literature review and community consultation"
  priorPermissions: "FPIC obtained from community representatives"
```

## Implementation Considerations

### Data Collection Best Practices

1. **Community Engagement**
   - Obtain Free, Prior, and Informed Consent (FPIC)
   - Respect community decision-making processes
   - Provide clear information about data use

2. **Knowledge Protection**
   - Identify sensitive or sacred knowledge
   - Implement appropriate access restrictions
   - Document restrictions clearly

3. **Attribution**
   - Credit knowledge holders properly
   - Include multilingual information
   - Maintain traceability to sources

4. **Legal Compliance**
   - Document all permissions and agreements
   - Adhere to Nagoya Protocol requirements
   - Establish benefit-sharing arrangements

### Data Quality Standards

- **Accuracy**: Information verified through community consultation
- **Completeness**: Include relevant context and provenance
- **Consistency**: Use controlled vocabularies and standard terms
- **Currency**: Maintain version history and update dates

## Integration with Darwin Core

### Related Darwin Core Terms

The extension complements existing Darwin Core elements:

- **Taxon**: Core species information (scientificName, kingdom, etc.)
- **Identification**: Taxonomic identification details
- **Location**: Geographic and ecological context
- **Event**: Temporal information about observations or collections
- **Occurrence**: Details of organism occurrences
- **Record-level**: General record metadata and provenance

### Namespace

The extension uses the namespace prefix **tb** (Traditional Biodiversity) to clearly identify extension terms and avoid conflicts with Darwin Core.

## Validation and Testing

### Case Study Approach

The extension has been validated through three complementary case studies:

1. **Ethnobotany Case Study**: Medicinal and food plant uses in South America
2. **Traditional Ecological Knowledge Case Study**: Indigenous land management practices
3. **Biodiversity Monitoring Case Study**: Community-based species documentation

### Future Validation

Planned expansions to include:
- Animal species and traditional uses
- Microorganism applications
- Cross-cultural comparisons
- Regional adaptations

## Standards Alignment

### International Frameworks

- **CBD (Convention on Biological Diversity)**: Supports implementation of Article 15 on genetic resources
- **Nagoya Protocol**: Facilitates access and benefit-sharing documentation
- **WIPO (World Intellectual Property Organization)**: Supports traditional knowledge protection
- **UNESCO**: Aligns with intangible cultural heritage conventions

### Related Technical Standards

- **GBIF Darwin Core Standard**: Provides taxonomic data framework
- **ISO 8601**: Date and time standardization
- **ISO 639**: Language code standardization
- **ISO 3166**: Country and region code standardization

## Version Management

- **Current Version**: 1.0 (Draft)
- **Status**: Under development and community review
- **Maintenance**: TDWG Socio-Biodiversity Task Group
- **Discussion**: https://github.com/sibbr/cesp-sibbr-2024/issues

## Resources for Implementation

- [Darwin Core Quick Reference](https://dwc.tdwg.org/)
- [GBIF Data Standard Guide](https://www.gbif.org/data-standards-and-best-practices)
- [CARE Principles](https://www.gida-global.org/care)
- [Nagoya Protocol Guide](https://www.cbd.int/abs/)

---

**Last Updated**: November 2024
**Managed By**: TDWG Socio-Biodiversity Task Group
