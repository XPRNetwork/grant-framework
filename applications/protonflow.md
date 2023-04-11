# ProtonFlow Grant Proposal

- **Project Name:** ProtonFlow
- **Team Name:** justmert
- **Payment Address:** mertkkl
- **Level:** Individual
- **Is Project Open-Source:** Yes
- **Project has a token:** No
- **Github Repo:** <https://github.com/justmert/eco-flow-frontend>

### Contact Information

- **Contact Name:** Mert Köklü
- **Contact Email:** kklumert@gmail.com
- **Website:** https://github.com/justmert

### Project Details

As the Proton protocol ecosystem continues to grow, it's becoming increasingly challenging to stay informed about the ecosystem's status and trends, as well as the activities of the many open-source projects being built on or integrated with the protocol. With data scattered across various platforms through Github to Twitter, gaining a comprehensive view of the ecosystem can be a daunting task.

ProtonFlow offers a cutting-edge solution to this problem, providing a comprehensive platform that delivers various insights and metrics to track the activities and development of the Proton ecosystem. Through intuitive and interactive visualizations and charts, ProtonFlow empowers users to gain a clear understanding of code contributions, community engagements, trend data, and many other critical metrics related to the Proton ecosystem.

By tracking various off-chain sources, ProtonFlow is the go-to platform for gaining a comprehensive view of the Proton protocol and becomes uniqueness in the space.

**Links**

* **MVP Website:** <https://protonflow.netlify.app/>
* **Open-source Backend:** <https://github.com/justmert/eco-pulse-backend>
* **Open-source Frontend:** <https://github.com/justmert/eco-pulse-frontend>


**Mockups**

| Dashboard Page | Project List Page | Project Detail Page |
| ----- | ----------- | ------------- |
|![ProtonFlow Dashboard](https://user-images.githubusercontent.com/37740842/231267607-0838560a-4383-4022-91c7-edea443e11c7.png)|![ProtonFlow Projects](https://user-images.githubusercontent.com/37740842/231268126-dddea8d6-755b-462e-b424-8ac5e06fc4a3.png)|![ProtonFlow Project Page](https://user-images.githubusercontent.com/37740842/231267635-568c4d30-d671-420d-ad8b-0d68d794f36a.png)|


| Scheme |
| ----- |
|![protonflow_technical_scheme](https://user-images.githubusercontent.com/37740842/231266660-feebd7d2-681a-469f-b64b-e389d3ea960f.png)|

**Project Goals**

* To provide a comprehensive analytics dashboard and intuitive visualizations for the Proton ecosystem.
* To empower users with valuable data and insights on project activity, code contributions, community engagements, trend data, and other critical metrics related to the Proton ecosystem.
* To track various off-chain sources, ProtonFlow becomes the go-to platform for gaining a comprehensive view of the Proton ecosystem.



### Ecosystem Fit

* **Comprehensive analytics platform:** ProtonFlow provides a comprehensive platform that delivers various insights and metrics to track the activities and development of the Proton ecosystem and its associated open-source projects.

* **Consolidated data sources:** By consolidating data sources and presenting key metrics and insights in an intuitive and interactive format, ProtonFlow addresses the challenge of scattered data sources, making it easier for users to understand the ecosystem's status and trends.

* **Helping to make informed decisions:** By providing valuable insights and metrics, ProtonFlow can help ecosystem users make more informed decisions about which projects to support and contribute to as well as identify promising projects and high-risk ones.

* **Gap in the market:** ProtonFlow fills the gap in the market by being the only project that becomes go-to core off-chain analytics dashboard for the Proton ecosystem.

* **Discovering the evolution of the ecosystem:** ProtonFlow provides historical data and visualizations of key metrics, enabling developers and ecosystem users to better understand the development trajectory of Proton and its projects. This feature helps users identify areas where protocol gains trends and track the ecosystem's progress over time.

* **Integration with approved grants and hackathons:** ProtonFlow can be integrated with approved grants and hackathons to keep track of the activity and development of these projects within the Proton ecosystem. By tracking the progress and development of grant recipients and hackathon projects, ProtonFlow can provide valuable data and visualizations, which can be used to evaluate the success of these programs and their impact on the ecosystem.

* **Encourage Community Collaboration:** ProtonFlow provides a centralized location for viewing project activity and contributions, encouraging community collaboration and engagement. By enabling users to easily identify areas where they can contribute to projects, thus empowers the community to work together towards a common goal, further strengthening the Proton ecosystem.

**Target audience**

The target audience for ProtonFlow includes developers, researchers, and enthusiasts who are interested in monitoring the development and activity of Proton network and its open-source projects. The platform's analytical tools and visualizations can provide valuable insights into the performance of various projects, making it useful for those who want to gain a better understanding of the progress of the network and the direction it's headed in.


### Team

- **Mert Köklü** - Full Stack Development

As an experienced Web3 developer, I have become a grantee for Web3 Foundation, AAVE, Lens and Filecoin ecosystems by developing innovative projects. As a certified NVIDIA instructor, AAVE Turkey Community Co-Manager and ambassador for organizations such as Microsoft and The Graph protocol, I have become a trusted voice within the communities and gained a deep understanding of their needs and requirements. 

Currently, I'm focused on developing open-source and user-friendly applications that bring value to the Proton protocol ecosystem.

* Github: <https://github.com/justmert>
* Linkedin: <https://www.linkedin.com/in/mertkoklu>
* Email: kklumert@gmail.com
* Telegram: @mertkklu
* Discord: MertK#2634
* Stackoverflow: https://stackoverflow.com/users/10515117



### Roadmap

Project will be completed with 2 milestones in 2 months.
- Milestone 1 - Will be completed in 1 month after the grant is approved.
- Milestone 2 - Will be completed in 1 month after milestone 1 is completed.

### Milestones

**Summary**
- **Total Estimated Duration:** 2 months 
- **Full-Time Equivalent (FTE):** 1 FTE
- **Total Costs:** 10,000 USD

### Milestone 1 — Build

- **Milestone:** 1
- **Estimated duration:** 1 month
- **FTE:**  1
- **Costs:** 5,000 USD

| ID | Deliverable | Specification |
| ----- | ----------- | ------------- |
| 0. | License | MIT |
| 1. |  Database | Set up a Firebase project and Firestore database to store chart data and project metadata. |
| 2. |  Backend | To integrate Github Data to the ProtonFlow, develop a Python backend that uses both the Github Rest and GraphQL APIs to fetch latest data from the Github. |
| 3. |  Frontend | Build the Project Detail and Dashboard pages, including the following implementations: commit history, code frequency, top contributors, issue activity, issue count, star count, pull request count, recent issues, recent commits, pull request activity, recent stargazing activiaty. |
| 4. |  Frontend | Develop a Project List page that lists all Proton ecosystem projects in order of their respective stargazing counts. |
| 5. |  Integration | Integrate Algolia to improve the search functionality of the platform. |
| 6. |  Integration | Integrate Typeform to allow ecosystem users to suggest new projects for the platform. |
| 7. |  Integration | Integrate Google Analytics to track user engagement and improve the platform accordingly. |
| 8. |  Backend | Set up a regular update schedule for the backend to keep the database up-to-date with the latest data. |


### Milestone 2 - Expand

- **Estimated Duration:** 1 month
- **FTE:**  1
- **Costs:** 5,000 USD

| ID | Deliverable | Specification |
| ----- | ----------- | ------------- |
| 1. |  Feature | Integrate Twitter data of Proton and its associated projects into the platform, including metrics such as the number of tweets posted per day or week, the number of likes, retweets, and replies received, and other relevant analytics. |
| 2. |  Feature | Develop categorization feature to classify projects based on various criteria within the ProtonFlow, such as DeFi, DEX. The feature will make it easier for users to find projects that are of interest to them. |
| 3. |  Feature | Develop project health score feature that evaluates multiple metrics to provide users with an overview of a project's health. The score helps identify promising projects and high-risk ones. The resulting score, weighted by metric importance, will display on the project detail page. |
| 4. |  Feature | Develop an API for ProtonFlow that provides developers with access to ProtonFlow charts and metadata. The API will use RESTful architecture and documented using OpenAPI Specification. Using the API, developers can embed charts and data into their own applications. |
| 5. |  Feature | Up-to-date ecosystem project list on ProtonFlow will be customized based on the protocol's preference. If the protocol wishes project list to be updated independently, a GitHub crawler will be implemented to automatically discover ecosystem projects and adds them to the ProtonFlow. Alternatively, if the protocol has a project list available on a platform such as Notion, we will use the platform's respective API to access the list. In addition, if the protocol has a website that displays its ecosystem projects, such as an awesome list or other third-party application, we can parse the GitHub links and incorporate them into ProtonFlow. We will collaborate with the protocol to determine the most effective approach and ensure the project list is kept up-to-date and accurate. |



### Future Plans

In the short term, we intend to use ProtonFlow to provide a comprehensive and user-friendly platform for developers and ecosystem users to track and analyze projects in the Proton ecosystem. We will continuously enhance and update the platform to ensure that it is the go-to resource for up-to-date information on Proton projects. 

In the long term, our team's plan is to continue supporting and improving ProtonFlow to meet the evolving needs of the Proton community. This includes incorporating additional metrics and data sources to provide more detailed insights into projects. Besides, if the platform is well-received by the community, and gains traction, we are going to **open a Twitter account** for ProtonFlow to engage with the community and promote top open-source projects on the Proton ecosystem. 

### Additional Information

If you have any questions or requests, please feel free to contact me. Thank you.

* Email: kklumert@gmail.com
