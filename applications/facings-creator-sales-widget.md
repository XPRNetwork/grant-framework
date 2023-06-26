# Proton Blockchain Grant Proposal

- **Project Name:** FACINGS Creator
- **Team Name:** FACINGS, INC.
- **Payment Address:** facings
- **Level:** Company
- **Is Project Open-Source:** Partially
- **Project has a token:** No
- **Github Repo:** https://github.com/FACINGS/collection-manager

### Contact Information

- **Contact Name:** Robert Konsdorf
- **Contact Email:** rob@facings.io
- **Website:** https://FACINGS.io

### Project Details

> Describe your project in detail, include any screenshots or designs. What problem does it solve? What is the current state of the project?

This grant seeks to bring dedicated support for the [FACINGS Collection Manager](https://github.com/FACINGS/collection-manager) to Proton, while also extending its functionality to include the ability to launch a sale where publishers can offer AtomicAssets NFTs for sale via crypto or credit card payment. FACINGS will host and maintain the FACINGS Creator (our hosted instance of the Collection Manager) with Proton chain enabled on https://creator.facings.io.

The Sales plugin will allow teams of all sizes to reach their customers through cryptocurrency and credit card sales. This robust tool is created with NFTs in mind and the workflow is tailored to the needs of Antelope builders.

The Collection Manager is available on GitHub as an open source reference UI for the AtomicAssets NFT standard. It aims to implement the majority of AtomicAssets actions into one easy-to-use tool. The sales plugin and sales backend will be closed-source; however, all other functionality and plugins remain open.

Collection Manager includes a robust plugin system that allows for closed and open source features to be managed individually. With the plugin system, each implementation of the Collection Manager can be customized to meet the needs of its users.

Current development of the Collection Manager centers around team collaboration, with a focus on two features: CSV Data Import, and Advanced Airdrops. The Data Import plugin will enable an entire NFT set to be created in a CSV format and then imported into the tool onto either testnet or mainnet. Included data validation ensures that no mistakes are permanently made in your NFT metadata. The Advanced Airdrop plugin allows publishers to distribute assets by running specific queries against the userbase.

### Ecosystem Fit

> 1. Where and how does your project fit into the Proton ecosystem?

The Collection Manager is the first open source collection management interface using the AtomicAssets standard and will join closed source implementations of the same standard on Proton. Allowing for an open source codebase that the ecosystem can rely on will help foster an emerging dev community.

Plugins can be created on top of the open source Collection Manager, allowing companies to leverage the open source software and expand it with their own open or closed features. New plugins can be funded by additional grants submitted by various development teams drawing attention from the larger Antelope developer community.

The FACINGS Creator serves as an example of how the Collection Manager can be used while also being maintained and supported by the FACINGS team. It is used to gather feedback from the community that will help FACINGS maintain and support the app into the future.

> 2. Who is your target audience?

Our target audience consists of the Proton community, its developers, as well as NFT enthusiasts. We also aim to encourage new builders to create on Proton in the future by providing Proton with improved NFT management tooling and sales functionality.

> 3. What needs does your project meet for the community and what sets it apart from other similar projects?

Proton lacks an open-source reference interface using AtomicAssets, forcing the ecosystem to rely on closed source competitors. While other NFT creators do exist, such as Neftyblocks, they do not have the same feature set and goals as the Collection Manager.

Additionally, Proton does not have a sales function on any NFT creator that will include the feature set of the FACINGS sales plugin - namely, the ability to sell NFTs for cash using credit cards.

### Team

- Team Leader: [Rob Konsdorf (Robrigo)](https://github.com/robrigo), CEO
- [Keir Kleinknecht (Banana)](https://github.com/keirmon), COO
- [Roadscape](https://github.com/roadscape), Software Engineer
- [Felblob](https://github.com/felsin), Product Manager
- [Marcelo Souza](https://github.com/mr-souza), UI Engineer
- [Marcos Moreira](https://github.com/mmoreirasantosdev), DevOps Engineer
- [Edson Bonfim](https://github.com/edinhodiluviano), Backend Engineer

### Roadmap

Our roadmap consists of 3 milestones over a 4-month period, with work beginning immediately upon approval of this grant:
1. Proton Integration and testing (2 weeks)
2. Sales Infrastructure with crypto support (2.5 months)
3. Credit Card support and Affiliate System (1 month)

### Milestone Summary

- Total Estimated Duration: 4 months
- Full-Time Equivalent (FTE): 2.5 FTE
- Total Costs: 100,000 USD

### Milestones

#### Milestone 1 - Proton Integration & Support

- **Milestone:** 1
- **Estimated duration:** 2 weeks
- **FTE:** 2
- **Costs:** 10,000 USD

| ID    | Deliverable   | Specification |
| ----- | ------------- | ------------- |
| 0a.   | License       | GPLv3         |
| 0b.   | Documentation | Developer and user guides will be provided, with full out-of-the-box support for Proton. |
| 0c.   | Article       | PR Release demonstrating partnership between FACINGS and Proton. |
| 1.    | Integration   | Integrating Proton chain into the public codebase; Testing all features and updating guides. |
| 3.    | Deployment    | Deploy Proton to our hosted instance at https://creator.facings.io. |



#### Milestone 2 - Crypto Sales

- **Milestone:** 2
- **Estimated duration:** 2.5 months
- **FTE:** 3
- **Costs:** 75,000 USD

| ID    | Deliverable   | Specification |
| ----- | ------------- | ------------- |
| 0a.   | License       | Closed source |
| 0b.   | Documentation | Full user guide on creating and managing sales, including integration of the Sales Widget |
| 0c.   | Article       | PR Release announcing support for Proton sales from the FACINGS Creator. |
| 1.    | Sales Backend | Publisher API - Chain-auth methods for managing (1) sales & (2) payouts; Purchase API - UI methods (used by sales widget); and backend to manage inventory and process payments. |
| 2.    | Publisher UI  | Develop plugin for collection manager: (1) sales overview, (2) create/modify sales (set templates, price, dates, limits, payment options), (3) generate embed code |
| 3.    | Sales UI      | Embeddable iframe component ("Sales Widget") |


#### Milestone 3 - Fiat Sales (Proton KYC) & Affiliate System


- **Milestone:** 3
- **Estimated duration:** 1 month
- **FTE:** 1.5
- **Costs:** 15,000 USD

| ID    | Deliverable   | Specification |
| ----- | ------------- | ------------- |
| 0a.   | License       | Closed Source |
| 0b.   | Documentation | Updated documentation for credit card processing; user guide for affiliate system and accessing statistics. |
| 0c.   | Article       | PR Release announcing completion of the new sales system on Proton which handles crypto and credit card sales, as well as the Affiliate System as a promotion tool. |
| 1.    | Sales Backend | Integrate credit card processor; allow sales conducted in USD; integrate Proton KYC; sales tax handling.  |
| 2.    | Frontend | For Sales Widget, add credit card flow. For Sales Plugin, add fiat withdrawal flow. |
| 3.    | Affiliate Program  | allows publishers to create an affiliate system; Backend will track sales made by affiliates. Publisher will have access to leaderboards: sales count by affiliates; total sum. |

### Future Plans

> How do you intend to enhance, promote and support your project in the future?

FACINGS' goal with the Collection Manager is to make it easy for companies to use Proton to create or integrate NFT assets into game economies while providing value and gamification. To accomplish this, FACINGS will provide ongoing development support for the project including bug fixes, marketing content including blogs, and support.

FACINGS will continue to enhance the open source Collection Manager with prioritization based on community feedback and feature requests. Additional milestones may be submitted with enhancements and new features that bring the Collection Manager to the feature set found on most creators today and realize the wishes of the community at large.

### Additional Information

FACINGS was spun off from Detroit Ledger Technologies, a Proton block producer. DLT has provided initial bootstrapping funding and support to help FACINGS get to where it is today.

FACINGS has also received funding from the ENF to execute on the Collection Manager roadmap. The team is seeking complementary funding in this grant to continue executing on our roadmap and to enhance the app further for the benefit of all.

Paul Grey (protonnz) has forked the collection-manager and started working on Proton support in his own branch already. FACINGS' team will take that initial work and finish it with support from this grant. We are excited to continue to support his initiatives and bring The FACINGS Creator to Proton!
