OpenAML - Software Project Contribution and Onboarding

# 1. Describing The Contribution


## Business Problem

The increasing adoption of blockchain technology in financial systems demands a more transparent and collaborative approach to regulatory compliance, particularly in anti-money laundering (AML) efforts. 
Security systems should be open, allowing contributions from all industry players to ensure financial institutions, regulators, and blockchain-based services can effectively detect and prevent illicit transactions. 
Instead of relying on fragmented and proprietary solutions, the industry requires a unified standard that promotes interoperability, enabling seamless integration across blockchain networks. 
A transparent and standardized approach is necessary to enhance traceability, ensuring that suspicious activities can be identified and monitored consistently across different platforms. 
Furthermore, automation must be prioritized to reduce reliance on manual compliance processes, lowering operational costs and increasing efficiency in AML enforcement. 
To achieve this, an open-source initiative is needed to lead the development of a comprehensive, AI-powered framework that fosters collaboration and establishes a standardized approach to AML in the blockchain ecosystem.

## Proposed Solution

We propose contributing an open-source AML analytics tool to blockchain ecosystems, leveraging artificial intelligence to enhance AML monitoring, risk assessment, and regulatory compliance. 

## Tentative Roadmap

• Data Processing and Feature Engineering: Over 100 AI-powered features for blockchain transaction monitoring.

• Automated Risk Scoring: Assigns dynamic risk levels based on historical transaction data, patterns, and heuristics.

• Blockchain Interoperability: Supports Ethereum Virtual Machine (EVM) blockchains, with specialized features for Hyperledger and CBDC projects.

• Regulatory Compliance Framework: Enables integration with financial institutions’ AML workflows, supporting Know Your Transaction (KYT) and other compliance standards.

• Web Interface and API: Provides a user-friendly dashboard and an API for seamless integration into existing AML compliance processes.

## Current State

Hackathon Prototype: Initial version developed and tested during the DTCC AI hackathon supporting basic features and manual data pipeline. 
 
## Existing Materials

 - [x] GitHub / GitLab Repository 
   - [x] URL for the repository
     - [x] https://github.com/finos-labs/dtcch-2025-cipher-sentinel/tree/main/data-pipeline
     - [x] https://github.com/finos-labs/dtcch-2025-cipher-sentinel/tree/main/models
     - [x] https://github.com/finos-labs/dtcch-2025-cipher-sentinel/tree/main/site-sentinel

   - [x] Project Name 
     - [x] OpenAML 
   - [ ] @finos-admin has been given read-only permissions if private
 - [ ] Is Continuous Integration used? _If so, which system is used?_
 - [ ] Was the project ever released? _(Yes)_
   - [ ] If so, are releases public? _(Yes)_
   - [ ] And what's the latest released version? _(1.0.0)_
 - [x] Existing Project Documentation 
   - [x] https://github.com/finos-labs/dtcch-2025-cipher-sentinel/blob/main/README.md
 - [x] Does the name have a registered trademark? _(no)_
 - [x] Is there a logo? _(no)_
 - [x] High-Level Presentation prepared for Technical Oversight Committee _(~15 mins)_
    - https://drive.google.com/file/d/1guhrGkzAGH3uMPYBBiDc-GouQh3NQ3HP/view?usp=sharing
 - [ ] Are meetings currently held for the project? _(yes + details)_
 - [ ] Are meeting minutes, agenda and attendance tracked? _(yes + details)_
   

## Development Team

### Maintainers

- Luciano Juvinski | luciano.silva@duke.edu | https://github.com/juv1nsk1
- Haochen Li | haochen.li2@duke.edu | https://github.com/Harrisous
- Yiqing Liu | yiqing.liu@duke.edu | https://github.com/ludaladila
- Yifei Ren | yifei.ren@duke.edu | https://github.com/yifei888
- Cartier Huang | cartier.huang@duke.edu | https://github.com/cw183

### Confirmed contributors
- 

### Target Contributors
We are looking for industry collaborators to help us maintain and provide real-world feedback on the project.

## Project Communication Channel(s)

- [x] Contributor to ask maintainers which communications channels they'd like to use:
  - [x] Discord
- Asynchronous
  - [x] GitHub Issues _(public)_
  - [x] GitHub Discussions _(public)_
- Synchronous
  - [x] Recurring meetings

## Understanding FINOS Onboarding Requirements

As a project onboarding into FINOS, you will need to familiarize yourself and your contributor team with the following materials:

 - [FINOS overview](https://www.finos.org/hubfs/An%20Introduction%20to%20FINOS.pdf) (if necessary)
 - [FINOS Maintainers cheatsheet](https://community.finos.org/docs/finos-maintainers-cheatsheet/)
 - [FINOS Project/Standards Governance](https://community.finos.org/docs/governance)
 - [FINOS Project Lifecycle](https://community.finos.org/docs/governance/Software-Projects/project-lifecycle)

## Record The Contribution (FINOS Infra)
- [ ] (optional) Identify and Assign FINOS Strategic Advisor
- [ ] Submit contribution to LF by opening a ticket via https://jira.linuxfoundation.org/browse/SS and marking contribution as "Exploratory"; attach a summary of the **Business Problem** and **Proposed Solution** (above) of the project.

# 2. Approval

The [FINOS Technical Oversight Committee](https://github.com/finos/technical-oversight-committee) (TOC) is responsible for approving FINOS project contributions; feel free to check their [contribution principles](https://github.com/finos/technical-oversight-committee/blob/master/contribution-principles.md).

If needed, the TOC will request a follow up either via GitHub Issue comments or by inviting project leads to one of their recurrent meetings.

Tasks (for FINOS Infra/TOC)
- [ ] Prioritise this issue on the [TOC Backlog]
- [ ] Assign this issue to @eddie-knight
- [ ] Add the `ready-for-tsc` label
- [ ] TOC to invite contributors to present their project
- [ ] FINOS TOC approves/rejects the contribution
- [ ] Ask @jgavronsky to mark contribution as "Engaged" within LF systems
- [ ] (optional) If additional socialization is required, the Executive Director may bring projects to the FINOS Governing Board
- [ ] Update the contribution status to "Engaged" by sending another email to **LF Legal Representative** with the name of the project and its new status.

## TOC Findings / Report
*TOC to enter findings summary here.*

# 3. Preparing For Onboarding

Before the FINOS team can onboard your project, there are a few housekeeping that need to be taken care of.  These must be completed by the contributor, with help if required from the FINOS Infra.   

## Kick-off meeting
- [ ] Set up kick-off meeting with project leads
- [ ] Run kick-off meeting
  - [ ] Walk through the checklist in part 1, ensure all the questions are answered and remove items that don't apply
  - [ ] Write and send contribution proposal announcement (optional - see below)

## Proposal (Lead Maintainer)
- [ ] Lead maintainer to send out announcement to community@finos.org using this template:
    
    ```
    Dear FINOS Community, 
    
    We would like to propose a new FINOS project. Please review the proposal details at (_TODO: add link to the GitHub issue proposal_).
    
    If you're interested in participating, please :+1: the GitHub issue proposal and drop a comment with your name, org and email

   Thanks a lot,
   ```

## Logo / Trademarks
 - [ ] Sign the [project contribution agreement](https://community.finos.org/governance-docs/The.Linux.Foundation.--.Form.of.Trademark.Assignment.20221202.pdf) to allow FINOS to act on behalf of the contributor for accounts related to the project (e.g., GitHub, domain names, social media) and to optionally manage trademark assignment
 - [ ] Request logo design from `help@finos.org` _(if needed)_
 - [ ] The codebase doesn’t include any patent or copyright that conflicts with FINOS Governance and bylaws. _(Infra team to validate with FINOS Legal team if anything important is raised)_

## FINOS Project Blueprint
- [ ] [finos-admin](http://github.com/finos-admin) is Admin of the GitHub repository to transfer
- [ ] Apply project blueprint contents - see [our docs on collaboration infrastructure](https://community.finos.org/docs/collaboration-infrastructure#finos-project-blueprint)
    - [ ] README.md file contains the sections in the [README Template](https://github.com/finos/software-project-blueprint/blob/main/README.template.md)
    - [ ] Project FINOS badge in README (incubating)
    - [ ] [OpenSSF Passing Badge](https://bestpractices.coreinfrastructure.org/en)
    - [ ] License in README
    - [ ] Contributing in README
    - [ ] `CONTRIBUTING.md`
    - [ ] `LICENSE` (replace `{}` placeholders)
    - [ ] Ensure that the proper project governance is in the CONTRIBUTING.md file
- [ ] [All incubating criteria](https://community.finos.org/docs/governance/Software-Projects/stages/incubating) are checked and documented below

_Add documentation here_

# 4.  FINOS Onboarding

This is performed by FINOS Infra once the three previous stages are complete, with support from the contributor and the FINOS Infra team.

## Maintainers, Contributors and CLAs 
- [ ] Identify other existing contributors (assuming there's a contribution history (eg Git history)
- [ ] Check if maintainers and other contributors are all covered by FINOS CLA
- [ ] Engage with FINOS Legal team to figure out what’s needed to cover all maintainers and contributors with FINOS CLA
- [ ] Reach out to contributors and employers to coordinate CLA signatures
- [ ] Invite GitHub usernames to GitHub FINOS Org
- [ ] Create `<project-name>-maintainers` GitHub team and invite users

## Validation (only if code is contributed)
- [ ] Backup (even with screenshot) GitHub permissions of the repository to transfer
- [ ] Check GitHub repository transfer requirements:
  - [ ] [finos-admin](http://github.com/finos-admin) has `Admin` to all repositories to transfer
  - [ ] [finos-admin](http://github.com/finos-admin) ia allowed to transfer repositories out of the org
  - [ ] if the repository is owned by a user (and not an org), the user must be able to transfer the repository to [finos-admin](http://github.com/finos-admin)
- [ ] The codebase doesn’t have HIGH or CRITICAL CVEs across direct and transitive libraries
- [ ] The codebase doesn’t have any unfriendly licenses across direct and transitive libraries
- [ ] (optional - if a build system is provided) The build process runs successfully
- [ ] The codebase doesn’t include any patent or copyright that conflicts with FINOS Governance and bylaws (to be validated with FINOS Legal team)
- [ ] [All incubating criteria](https://community.finos.org/docs/governance/Software-Projects/stages/incubating) are met (review documentation provided above)

## Code transfer 
- [ ] Transfer all code assets as GitHub repositories under github.com/finos
- [ ] Rename main branch to `main` (instead of `master`)
- [ ] Configure `finos-admins` (`Maintain` role) and `finos-staff` (`Triage` role) team permissions

## Project Communication Channel(s)
- [ ] Create the identified communication channels during infra set up
- [ ] Create mailing-list on lists.finos.org (if requested)
    - [ ] Enable Hubspot Sync for all project mailing lists created
    - [ ] Aggregate mailing lists to community@finos.org
    - [ ] Update marketing lists (see `Email List` and `Email` filter fields), particularly [Hubspot all community list](https://app.hubspot.com/contacts/2419532/lists/2247/filters)
- [ ] Create Slack channels if requested.
- [ ] Link communication channels linked front-and-center in the project README.md

## Repository setup 
- [ ] Enable EasyCLA
- [ ] Add project to metadata
- [ ] Add identities, orgs and affiliations to metadata (deprecated by EasyCLA)
- [ ] Add logo to FINOS landscape
    - [ ] Create `staging` branch on `finos/finos-landscape`
    - [ ] Merge `finos/metadata` changes on master (will udpdate `landscape.yml` in `finos/finos-landscape`)
    - [ ] Create PR from `staging` branch on `finos/finos-landscape`
    - [ ] Review Netlify preview
    - [ ] Merge PR
- [ ] Add project maintainers emails to [finos-project-maintainers@finos.org](https://groups.google.com/a/finos.org/g/finos-project-maintainers/members) list
- [ ] Add project maintainers GitHub usernames to the [project-maintainers Team](https://github.com/orgs/finos/teams/project-maintainers/members)
- [ ] Ask @jgavronsky to mark contribution as "Active" within LF systems
- [ ] (best effort) Update release coordinates and code namespace to include `finos`
- [ ] Check that CVE (and preferably static code analysis, if applicable) scanning is in place
- [ ] Enable automated dependency update, using [Renovate](https://renovatebot.com/)
- [ ] Enable [branch protection](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/about-protected-branches) (`Require a pull request before merging`)
- [ ] (optional) Enable meeting attendance tracking
- [ ] (optional) Onboard into legend.finos.org/studio

# 5. Announcement 

(Lead: Project Lead and FINOS Infra team)

- [ ] Update the contribution status to "Active" by sending another email to **LF Legal Representative** with the name of the project and its new status.
- [ ] Lead maintainer works with FINOS marketing to send out announcement to announce@finos.org , checkout announcement template at the [Contribution page](https://community.finos.org/docs/governance/Software-Projects/contribution#step-5-contribution-announcements)
- [ ] Notify FINOS marketing (@grizzwolf + finos-marketing internal Slack channel)
