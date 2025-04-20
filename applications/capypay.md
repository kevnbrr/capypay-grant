# CapyPay 

## Project Overview
![CapyPay Logo](https://github.com/user-attachments/assets/077d0c49-d3b8-4a16-8e79-b362bf61e8e0)

CapyPay aims to start as a crowdfunding website allowing creators to receive funding on-chain for their projects (both digital and physical) by people who truly support their vision. We will provide lower fees compared to KickStarter, the go-to web2 competitor, and provide creators with the opportunity to KYC (which should increase the trust of the donnors and lead to increased donations).   

### Project Details

Project Overview

One-liner: "Kickstarter on chain!"

Description: Creators launch campaigns with funding goals and specific milestones. Backer's will donate to these campaigns. Once the campaign is fully funded, the creators will receive gradualy payouts once a milestone is comleted. The platform will require a minimum of 2 milestones per campaign to prevent creators from rugging and running away with 100% of the donated funds. 

Technical Stack
  Hosting: Vercel 
  Frontend: Next.js + React, Polkadot.js API for blockchain interactions 
  Smart Contracts: ink! on Substrate Contracts

What will be completed:
- Completed front-end with full users functionality allowing the user to fund campaigns
  - Users will also be able to create campaigns, set campaign goals (including milestones), upload photos (1-5) to support the campaign, and upload a YouTube video if needed
- Completed backend system that handles user signup/login, securely store user data and campaign data, smart contract integration to ensure the frontend properly displays the funding goal (at or near real-time)
- Smart contracts will be completed and launched on testnet
- Twitter will be created and start posting at least 2 times per week

What will not be completed at the current stage:
- Mainnet deploymented (may be deployed but depends on the launch fees so TBD)
- No cross-chain functionality at the current stage
- No on/off-ramp functionality (users will be directed to reputable CEXs) 

### Ecosystem Fit TODO TODO!!!

Help us locate your project in the Polkadot/Kusama landscape and what problems it tries to solve by answering each of these questions:

- Where and how does your project fit into the ecosystem?
- Who is your target audience (parachain/dapp/wallet/UI developers, designers, your own user base, some dapp's userbase, yourself)?
- What need(s) does your project meet?
- How did you identify these needs? Please provide evidence in the form of (scientific) articles, forum discussions, case studies, or raw data.
- Are there any other projects similar to yours in the Polkadot/Kusama ecosystem? Make sure to at least check the [Polkadot Forum](https://forum.polkadot.network/), the [wiki's Tech Stack doc](https://wiki.polkadot.network/docs/build-open-source) and [OpenGov](https://polkadot.subsquare.io/referenda?status=executed&is_treasury=true).
  - If so, how is your project different? Please identify and assess any projects addressing the same need and explain how your project is distinct. Feel free to include applicable research data, statistics, or metrics.
  - If not, please indicate why such a project might not have been possible, successful, or attempted. 
- Are there any projects similar to yours in related ecosystems? 

## Team

- **Team Name:** CapyPay
- **Contact Name:** Kevin Rodriguez-Romero
- **Contact Email:** kbr2125@columbia.edu
- **Website:** https://github.com/kevnbrr

### Team members

Kevin Rodriguez-Romero (Solo-Founder)

#### LinkedIn Profiles (if available)

- https://www.linkedin.com/in/kevnbrr/

### Team Code Repos

- https://github.com/kevnbrr/solana-sweepstakes
- https://github.com/kevnbrr/solana-builder-challenge-day-1
- https://github.com/kevnbrr/solana-builder-challenge-day-2
- https://github.com/kevnbrr/solana-builder-challenge-day-4

### Team's experience

- Currently completing a CS minor at Columbia University and the president for Blockchain at Columbia
- Built Solana‑based lottery and casino MVPs
- Completed an in-person Solana bootcamp with live testnet contract deployments

## Development Status

If you've already started implementing your project or it is part of a larger repository, please provide a link and a description of the code here. In any case, please provide some documentation on the research and other work you have conducted before applying. This could be:

- academic publications relevant to the problem,
- links to your research diary, blog posts, articles, forum discussions or open GitHub issues,
- references to conversations you might have had related to this project with relevant actors in the ecosystem,
- previous interface iterations, such as mock-ups and wireframes.

## Development Roadmap

This section should break the development roadmap down into milestones and deliverables. Since these will be part of the agreement, it helps to describe *the functionality we should expect in as much detail as possible*, plus how we can verify and test that functionality. Whenever milestones are delivered, we refer to this document to ensure that everything has been delivered as expected. Below, we provide an **example milestone** with mandatory (0a to 0e) and example deliverables. 

**Please notice that Polkadot Open Source Grants only accept projects up to 3 months of duration and up to 2 milestones.**

### Overview

- **Estimated Duration:** Duration of the whole project (e.g. 3 months)
- **Full-Time Equivalent (FTE):**  Average number of full-time employees working on the grant throughout its duration (see [Wikipedia](https://en.wikipedia.org/wiki/Full-time_equivalent), e.g. 2 FTE)
- **Total Costs:** Requested amount in USD for the whole project (e.g. 12,000 USD).

> Note that deliverables 0a to 0e are mandatory. Please adapt their specification to your project.

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 / GPLv3 / MIT / Unlicense. See the [delivery guidelines](https://github.com/PolkadotOpenSourceGrants/delivery/blob/master/delivery-guidelines.md#license) for details. |
| 0b. | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can... See the [delivery guidelines](https://github.com/PolkadotOpenSourceGrants/delivery/blob/master/delivery-guidelines.md#documentation) for details. |
| 0c. | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. See the [delivery guidelines](https://github.com/PolkadotOpenSourceGrants/delivery/blob/master/delivery-guidelines.md#testing-guide) for details. |
| 0d. | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish an **article**/workshop that explains [...] (what was done/achieved as part of the grant). (Content, language, and medium should reflect your target audience described above.) |
| 1. | Pallet X | We will create a Substrate module that will... (Please list the functionality that will be implemented for the first milestone. You can refer to details provided in previous sections.) |
| 2. | Smart contract Y | The Y Substrate module will... |
| 3. | Substrate chain | X and Y of our custom chain will interact in such a way... (Please describe the deliverable here as detailed as possible) |
| 4. | Library: ABC | We will deliver a JS library that will implement the functionality described under "ABC Library" |

### Budget Breakdown (Example, please adapt)
 **Category:** Budget Breakdown positions are split within the following categories: 
 
- Personnel
- Equipment
- Subcontracts/Subscriptions

| Category | Item | Cost | Amount | Total | Description |
| --- | ---- | --- | --- | --- | ---|
| Personell | Full-Stack Developer | 8,000 USD | 0.5 FTE | 4,000 USD | leading project with tech architecture and design |
| Personell | Smart Contract Developer | 10,000 USD | 1 FTE | 10,000 USD | focused on execution and implementation |
| --- | --- | --- | **Total** | **14,000 USD** |  |


## Future Plans

Please include here

- how you intend to finance the project's long-term maintenance and development,
- how you intend to use, enhance, and promote your project in the short term, and
- the team's long-term plans and intentions in relation to it.

## Additional Information

Here you can also add any additional information that you think is relevant to this application but isn't part of it already, such as:

- Work you have already done
- If there are any other teams who have already contributed (financially) to the project
- Other funding you may have applied for
