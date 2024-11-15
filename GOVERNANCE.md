# Governance Document for the Erlang Ecosystem Foundation CNA

## Introduction

This document outlines the governance structure, roles, responsibilities, and
voting mechanisms for the Common Vulnerabilities and Exposures (CVE) Numbering
Authority (CNA) led by the Erlang Ecosystem Foundation (EEF). The CNA operates
in collaboration with multiple projects within the Erlang ecosystem, including
Elixir, Gleam, the Hex Package Manager. and the projects distributed via Hex.pm.

## Overview

The CNA is a joint effort aimed at improving the security and vulnerability
management of projects within the Erlang ecosystem. The key participants include:

- **Erlang Ecosystem Foundation (EEF)**: Hosts the CNA initiative through its
  Security Working Group.
- **Collaborating Projects**:
  - **Elixir**: [https://elixir-lang.org/](https://elixir-lang.org/)
  - **Erlang**: [https://www.erlang.org/](https://www.erlang.org/)
  - **Gleam**: [https://gleam.run/](https://gleam.run/)
  - **Hex Package Manager**: [https://hex.pm/](https://hex.pm/)

### Scope of Participation

- **Project Withdrawal**: The projects specified in the CNA's scope—along with
  their GitHub repositories—can unilaterally decide to leave the CNA scope at
  any time.
- **Hex.pm Packages**: Projects hosted on Hex.pm can only leave the CNA scope if
  they are covered by a CNA with a more specific scope.

For detailed scope information, refer to the
[Scope Definition](https://cna.erlef.org/scope).

## Roles and Responsibilities

### 1. CVE Points of Contact

**Responsibilities**:

- Handle incoming vulnerability reports.
- Manage access to undisclosed and embargoed vulnerability information.
- Coordinate with Project Contacts for vulnerability assessment and resolution.

**Appointment**:

- Each voting party (Elixir, Erlang, Erlang Ecosystem Foundation, Gleam, Hex)
  has the right to appoint one or more individuals to serve as CVE Points of
  Contact.

### 2. Project Contacts

**Responsibilities**:

- Serve as the primary liaison for security matters related to their specific
  project.
- Receive embargoed information involving their project.
- Participate in the decision-making process to determine if a report
  constitutes a vulnerability. Projects participating in the CNA have a veto
  right on that decision.

**Appointment**:

- Each voting party and every project with a pre-arranged agreement can appoint
  a group of contacts to handle reports regarding their project.

### 3. CNA Supporters

**Responsibilities**:

- Participate in the governance and policy-making processes of the CNA.
- Support the CNA's operations without accessing embargoed or undisclosed
  vulnerability information.

**Note**: CNA Supporters do not have access to sensitive vulnerability data to
maintain impartiality and confidentiality.

## Voting Mechanism

### Voting Parties

The following groups constitute the voting parties within the CNA:

- **Elixir**
- **Erlang**
- **Erlang Ecosystem Foundation** (via its Security Working Group)
- **Gleam**
- **Hex**

### Voting Process

- **Decision-Making**: Policies, scope definitions, security policies, and
  internal processes are subject to a majority vote among the voting parties.
- **Abstention**: Any group may choose to abstain from a vote.

### Triggering a Vote

Votes can be triggered by:

- Proposed changes to policies, scope, or internal processes.
- Disputes arising from external reporters.

## Conflict of Interest

All participants are expected to act in the best interest of the entire Erlang
ecosystem rather than their individual projects. Given that members may maintain
their own projects under the CNA, they must exercise impartial judgment when
making decisions.

- **Disclosure**: Participants should disclose any potential conflicts of
  interest related to matters under discussion.
- **Expectation**: Decisions should prioritize the security and well-being of
  the broader community over individual project interests.

## Confidentiality and Data Handling

Maintaining the confidentiality of sensitive information is crucial for the
integrity of the CNA's operations.

- **Access Control**:
  - Only CVE Points of Contact and relevant Project Contacts have access to
    undisclosed and embargoed vulnerability information.
  - CNA Supporters do not have access to sensitive vulnerability data.
- **Data Handling**:
  - Embargoed information must be stored and transmitted securely.
  - Unauthorized disclosure of sensitive information is prohibited.
- **Confidentiality Obligations**:
  - All participants with access to sensitive data are required to adhere to
    strict confidentiality agreements.
  - Breaches of confidentiality may result in removal from the CNA and other
    consequences as deemed appropriate.

## Dispute Resolution

Disputes that cannot be resolved through initial discussions will trigger an
internal referendum, following the established voting mechanism.

- **Process**: While specific procedures are defined internally, disputes are
  handled promptly to minimize impact on security operations.
- **Alignment with Policies**: All resolutions must adhere to the
  [CVE Numbering Authority (CNA) Operational Rules](https://www.cve.org/ResourcesSupport/AllResources/CNARules/#section_4-4_CNA_Judgment).

## Code of Conduct

All participants are expected to adhere to the [CNA's Code of Conduct](CODE_OF_CONDUCT.md).

## References to Existing Policies

- **Security Policy**: Detailed operational procedures, including vulnerability
  handling and disclosure processes, are outlined in the Security Policy
  available at [https://cna.erlef.org/security-policy](https://cna.erlef.org/security-policy).
- **Scope Definition**: The CNA's scope is defined at
  [https://cna.erlef.org/scope](https://cna.erlef.org/scope).
- **CVE Numbering Authority (CNA) Operational Rules**: All decisions regarding
  vulnerabilities or policies must align with the CNA Operational Rules as
  specified by the CVE Program. Refer to the rules at
  [CNA Rules](https://www.cve.org/ResourcesSupport/AllResources/CNARules/#section_4-4_CNA_Judgment).
