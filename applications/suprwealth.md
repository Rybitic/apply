# SUPRWEALTH

## Project Overview

Please provide the following:

- **Tagline**: Making investing stress-free for the masses.
- **Description**: SuprWealth aims to make investing easier, less time-consuming, and highly rewarding regardless of the investor's expertise. Think of it as the next-generational hedge fund that's built not just for the wealthy, but for everyone. We eliminate the need for learning to invest. That era is long gone! Instead, Invest, sit back, and relax while our autonomous trading engine does the heavy lifting.
- **Polkadot Integration**: SuprWealth is poised to leverage Polkadot’s secure and scalable infrastructure as we scale our platform. We plan to launch a native token on Polkadot to drive utility features such as rewards, governance, and premium access. By integrating with Polkadot, we aim to bring real-world financial tools into the Web3 space, driving mainstream adoption and creating new opportunities for the Polkadot ecosystem as we grow.
- **Why We’re Interested**: The world doesn’t need another complex investing app. What people truly crave, often silently, is a way to grow their money without stress, without noise, without needing to become financial experts. We believe investing was never meant to be chaotic or time-consuming. It was meant to work quietly for you. SuprWealth isn’t reinventing investing. We’re restoring it to what it was always supposed to be. A calm, smart, and effortless path to wealth that is built for everyone.
- **Pitch Video**: 

### Project Details

- **Technology Stack**:
  - **Frontend & Backend**: Built with **Next.js** for a seamless full-stack experience.
  - **Authentication**: Handled using **Clerk**, ensuring secure and scalable user auth.
  - **Database**: **PostgreSQL** for structured, reliable storage of user and transaction data.

- **Core Components**:
  - **Website**: A clean, minimal interface for users to invest and monitor their balance.
  - **Beta Investment Feature**: A monthly compounding mechanism targeting **3.5%** growth for users participating in the beta program.
  - **Transaction Management**: Every deposit, withdrawal, and gain is tracked through a dedicated transactions table for full transparency.

- **MVP**: Live with a **beta version** where users can invest and see their money grow at a rate of 3.5% monthly. Access is currently limited to beta users.

- **Limitations**:
  - **No insurance**: Funds are not protected. Users may lose their full investment.
  - **Beta access only**: Platform is currently open to a closed group of beta testers.

### Ecosystem Fit

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

> Please note that the data provided in this section is for administrative and informational purposes only. All beneficiaries of a grant must also be listed in the KYC/KYB process during the application phase.

- **Team Name:** Name of your team. If you apply as a legal entity, please use its name.
- **Contact Name:** Full name of the contact person in your team
- **Contact Email:** Contact email
- **Website:** Your website, GitHub org, blog, or similar

### Team members

Please list the legal name of all grant beneficiaries.

#### LinkedIn Profiles (if available)

- https://www.linkedin.com/{person_1}
- https://www.linkedin.com/{person_2}

### Team Code Repos

- https://github.com/{your_organisation}/{project_1}
- https://github.com/{your_organisation}/{project_2}

Please also provide the GitHub accounts of all team members. If they contain no activity, references to projects hosted elsewhere are also fine.

- https://github.com/{team_member_1}
- https://github.com/{team_member_2}

### Team's experience

Please describe the team's relevant experience, such as Polkadot-related projects in progress or contributions to the ecosystem made by team members in the past.

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
