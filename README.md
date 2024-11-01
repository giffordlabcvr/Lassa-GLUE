Lassa-GLUE: Phylogenomic Analysis of Lassa Virus
================================================

Welcome to the GitHub repository for **Lassa-GLUE**!

Lassa-GLUE is a sequence-oriented resource for comparative genomic analysis of Lassa virus (LASV), developed using the **[GLUE](https://github.com/giffordlabcvr/gluetools)** software framework.

GLUE is an open, integrated software toolkit designed for storing and interpreting sequence data. It supports the creation of bespoke projects, incorporating essential data items for comparative genomic analysis, such as sequences, multiple sequence alignments, genome feature annotations, and other associated data.

Projects are loaded into the GLUE "engine," forming a relational database that represents the semantic relationships between data items. This foundation supports systematic comparative analyses and the development of sequence-based resources.

**Lassa-GLUE** contains LASV feature definitions, alignments, and reference sequences, designed to facilitate genomic studies across LASV lineages and provide insight into the virus's phylogenomic relationships.

For more information, please see the **[User Guide](https://github.com/giffordlabcvr/Lassa-GLUE/wiki)**

Key Features
------------

-   **Phylogenetic Structure**: Sequence data in Lassa-GLUE is organized in a phylogenetically-structured manner, allowing users to explore evolutionary relationships within and between LASV lineages.

-   **Rich Annotations**: Annotated reference sequences enable rigorous comparative genomic analysis related to conservation, adaptation, structural context, and genotype-to-phenotype associations.

-   **Automated Genotyping**: Lassa-GLUE includes tools for automated genotyping of LASV sequences, utilizing GLUE's **[maximum likelihood clade assignment (MLCA)](https://github.com/giffordlabcvr/Lassa-GLUE/wiki/Genotyping-Tools)** algorithm to support robust lineage classification.

-   **Exploratory and operational**: The GLUE framework allows sequence-based resources to be used for exploratory research and operational work in public health, supporting genomic surveillance and monitoring.

Installation
------------

Please refer to the **[User Guide](https://github.com/giffordlabcvr/Lassa-GLUE/wiki)** for installation instructions.

Usage
-----

GLUE offers an interactive command-line environment designed to facilitate the development and use of GLUE projects by bioinformaticians. This environment includes features such as command completion, command history, and interactive paging through tabular data.

For detailed usage instructions, please refer to **[GLUE's reference documentation](http://glue-tools.cvr.gla.ac.uk/)**.

Data Sources
------------

Lassa-GLUE relies on the following data sources:

-   [NCBI Nucleotide](https://www.ncbi.nlm.nih.gov/nuccore)

Contributing
------------

We welcome contributions from the community! If you're interested in contributing to Lassa-GLUE, please review our [Contribution Guidelines](./md/CONTRIBUTING.md).

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](./md/code_of_conduct.md)

License
-------

The project is licensed under the [GNU Affero General Public License v. 3.0](https://www.gnu.org/licenses/agpl-3.0.en.html)

Contact
-------

For questions, issues, or feedback, please open an issue on the [GitHub repository](https://github.com/giffordlabcvr/Lassa-GLUE/issues).
