# Abelian Improvement Proposals (AIPs)

## Introduction

This repository serves as the central location for proposing, discussing, and documenting improvements to the Abelian blockchain ecosystem. AIPs provide a structured framework for enhancing the functionality, usability, and governance of the Abelian network.

AIPs should provide concise technical specifications and rationale for the proposed changes. The community will discuss proposals to reach a consensus before their implementation. All accepted AIPs will be documented and maintained within this repository.

---

## Proposal Process

### Submitting an AIP

1. **Open an Issue**:
   - Submit a new issue in the [AIP GitHub repository issues section](https://github.com/pqabelian/aips/issues).
   - Clearly describe the proposal and its objectives.
   - Engage in discussions with the community for feedback and refinement.

2. **Community Discussion & Confirmation**:
   - The proposal will be reviewed and discussed by the community.
   - If the idea gains consensus, maintainers will approve it for further development.

3. **Create a Branch from the Issue**:
   - Once the proposal is approved, create a branch from the issue for drafting the AIP.
   - Use the proposal in [aips/aip0011_v005.pdf](aips/aip0011_v005.pdf) as a reference for structuring the document.
   - Follow the standard AIP format:
     - Preamble (Metadata such as AIP number, title, authors, etc.)
     - Abstract
     - Specification
     - Motivation
     - Rationale
     - Reference Implementation (if applicable)
     - Security Considerations
     - Copyright and License

4. **Submit a Pull Request (PR)**:
   - Commit the drafted AIP to the branch and submit a pull request (PR).
   - Engage in further discussions and refinements based on community and maintainer feedback.

5. **Merge into Master branch**:
   - Once the PR is approved, maintainers will merge the branch into the master branch.
   - The AIP will be assigned a number and marked with the appropriate status.

6. **Ongoing Updates**:
   - AIPs may be updated with errata or amendments if necessary.
   - Deprecated or superseded AIPs will be marked accordingly.


### Proposal Status

A proposal can have one of the following statuses:

- **Draft**: Initial stage for community feedback.
- **Proposed**: Undergoing formal review.
- **Final**: Approved and implemented.
- **Active**: Actively in use within the network.
- **Rejected**: Not accepted by the community.
- **Deprecated**: No longer in active use.

---

## Repository Structure

```plaintext
aips/
├── aips/                         # Directory containing all proposals
│   ├── aip0011_v005.md           # AIP-0011 in Markdown document
│   └── aip0011_v005.pdf          # AIP-0011 original PDF document
├── README.md                     # Overview of the repository
├── CONTRIBUTING.md               # Contribution guidelines for AIPs
└── LICENSE                       # MIT License information for the AIPs
└── media/                        # Media files (e.g., diagrams, images)
```

---

## Guidelines and Philosophy

AIPs should:
- Provide a clear technical specification.
- Address a specific issue or propose a well-defined improvement.
- Include rationale and justifications to help reviewers understand the motivation.
- Be structured and written in a way that facilitates implementation.

Maintainers and contributors strive to ensure a fair and inclusive decision-making process. Proposals should be based on community consensus and technical merit.

### Community Consensus

The acceptance of an AIP does not automatically make it a standard. The ultimate authority lies with the consensus of the Abelian community and users. AIPs may be implemented in client software, but their adoption depends on broad network consensus.

---

## AIP Editors

AIP editors are responsible for reviewing and maintaining the quality of AIPs. They ensure that proposals are properly formatted, technically sound, and documented in the repository.

Responsibilities include:
- Reviewing draft AIPs to check for clarity, completeness, and technical feasibility.
- Assigning AIP numbers and maintaining the repository.
- Merging accepted AIPs into the repository.
- Making minor editorial corrections when necessary.

---

## Licensing

This repository is licensed under the [MIT License](LICENSE). By contributing, you agree that your contributions will be licensed under the same terms.

---

## Resources

- [Abelian Website](https://www.pqabelian.io)
- [Abelian Documentation](https://community.pqabelian.io/guide/)
- [AIP GitHub Issues](https://github.com/pqabelian/aips/issues)

---

## Acknowledgments

We thank the Abelian community for their contributions and commitment to the project's development.