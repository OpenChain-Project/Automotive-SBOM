# Automotive SBOM Framework

The Automotive SBOM Framework defines a common framework for the creation, exchange, and use of Software Bill of Materials (SBOM) information across the automotive supply chain.

While general-purpose SBOM standards and specifications such as SPDX and CycloneDX provide mechanisms for representing SBOM data, the Automotive SBOM Framework provides automotive-focused guidance on the information that should be exchanged and how that information can support software supply chain transparency, vulnerability management, license compliance, and lifecycle management.

The framework is intended to support interoperability among organizations participating in the automotive ecosystem, including OEMs, suppliers, tool providers, and other stakeholders.

## Objectives

The Automotive SBOM Framework aims to:

- Enable a common language for software component information across the automotive supply chain
- Improve efficiency and productivity by reducing organization-specific SBOM requirements
- Support software risk management activities, including vulnerability management and license compliance
- Provide a common set of requirements for the SBOM tool ecosystem
- Promote interoperability among organizations using different SBOM formats, tools, and processes

## Scope

The Automotive SBOM Framework focuses on defining a common set of SBOM information and related practices for the automotive industry.

The framework consists of three areas:

### Data Fields

Defines the software component information that should be exchanged between organizations.

Examples include:

- SBOM metadata
- Component identification information
- Software supplier information
- Component relationships
- License information
- Cryptographic hash information
- External SBOM references

### Automation Support

Provides guidance on expressing Automotive SBOM information using common SBOM document formats.

The framework does not prescribe any specific SBOM document format and supports multiple formats, including:

- SPDX
- CycloneDX

### Practice and Process

Provides guidance on the generation, exchange, management, and use of Automotive SBOM information throughout the software lifecycle.

Examples include:

- SBOM generation
- SBOM exchange
- Hierarchical SBOM management
- Vulnerability management
- License compliance activities

## Relationship to Existing Standards

The Automotive SBOM Framework builds upon existing industry standards and guidance, including:

- NTIA Minimum Elements for a Software Bill of Materials (SBOM)
- 2026 Minimum Elements for a Software Bill of Materials (SBOM)
- CISA guidance
- SPDX
- CycloneDX
- BSI TR-03183
- OpenChain Telco SBOM Guide

The framework is intended to complement these standards rather than replace them.

## Design Principles

The Automotive SBOM Framework follows these principles:

- Format independent
- Tool independent
- Organization independent
- Compatible with existing industry standards
- Focused on software component identification and exchange
- Suitable for automated processing and integration

## Intended Audience

This framework is intended for:

- Automotive OEMs
- Tier-N suppliers
- Software suppliers
- Open source compliance teams
- Product security teams
- PSIRT organizations
- SBOM tool vendors
- Regulators and industry organizations

## Repository Structure

```text
docs/
├── AutomotiveSBOM_Framework.md
└── images/
```

## Contributing

Contributions, feedback, and discussion are welcome.

Please use GitHub Issues and Pull Requests to propose improvements, report issues, and discuss future enhancements to the Automotive SBOM Framework.

## Meetings
 
Community meetings are held regularly to discuss ongoing work, issue resolution, and future development of the Automotive SBOM Framework.
 
Please refer to the following page for the latest meeting schedule:
 
[Automotive Open Source Governance Monthly Meeting Schedule](https://openchain-project.github.io/Automotive-Open-Source-Governance-Monthly/)
 
We welcome participation from all interested stakeholders.
 
## Join Us
 
Everyone is welcome to participate in the Automotive SBOM Project, which is part of the OpenChain Automotive Work Group.
 
The primary communication channel is the Automotive SBOM mailing list:
 
[OpenChain Automotive SBOM Mailing List](https://lists.openchainproject.org/g/automotive-sbom)
 
## Copyright and License

Copyright © 2026 OpenChain Project.

This work is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

You are free to share and adapt this work, including for commercial purposes, provided appropriate attribution is given.

Contributors are acknowledged in the CONTRIBUTORS.md file, which forms part of the project record. Attribution should preserve applicable contributor and project credits.

For details, see the CC BY 4.0 license:
https://creativecommons.org/licenses/by/4.0/