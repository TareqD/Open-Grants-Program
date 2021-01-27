# Open Grant Proposal

> This document is referenced in the terms and conditions and therefore needs to contain all the required information. Don't remove any of the mandatory parts presented in bold letters or as headlines! See the [Open Grants Program Process](https://github.com/w3f/Open-Grants-Program/blob/master/README_2.md) on how to submit a proposal.

> This page is also available in [Chinese (中文)](./application-template-cn.md).

* **Project Name:** OptionRoom
* **Team Name:** OR Technology
* **Payment Address:** 0xF735A0Fd8207B8cCbC275a52881cbAeC5EEF2B38

*The above combination of your GitHub account submitting the application and payment address will be your unique identifier during the program. Please keep them safe.*

## Project Overview :page_facing_up: 
If this application in response to an RFP then please indicate this on the first line of this section.

### Overview

Please provide the following:
  * A brief description of the project:
  OptionRoom is a user governed oracle and forecast protocol built on Polkadot.
  * An indication of how you will integrate this project into Substrate / Polkadot / Kusama.
  We're going to build the project on Substrate after successfully launching on the Ethereum network. Our on-chain governance will be implemented on polkadot
  * An indication of why your team is interested in creating this project.
  We found something that can add value to the crypto space and a unique approach to the oracle, and we're very eager to make it happen. 

### Project Details 
We expect the teams to already have a solid idea about the project's expected final state.

Therefore, we ask the teams to submit (where relevant):
* We are going to provide our whitepaper, it contains documentation of core components and all the detailed struture of our project.
* Whitepaper Can be found at: 
https://github.com/OptionRoom/OptionRoom-Whitepaper/blob/main/OptionRoom_Whitepaper.pdf

### Ecosystem Fit 
Our project has 2 main components:
* Oracle:
    Our approach to the oracle is based on community voting and does not require any external data sources to acquire data, its completely community based (human oracle). We can complement the other oracles by supplying data they cant access, 
    such as certain types of verification (news, insurance claims). 
* Forecast Market:
    There are a few forecast market projects on the market, and we add value in this arena by providing a truly limitless forecast market protocol, where the choices and markets are not limited to a certain structure, 
    and initially verified by our governance to make sure we only list high quality markets. In addition to that, we have a solid user incentive program that includes a buy-back mechanism which with enough protocol 
    usage allows for reward generation without having to mint extra tokens, and this gives the opportunity of a sustainable long-term reward program.


## Team :busts_in_silhouette:

### Team members
* Name of team leader
Marsel Adawi
* Names of team members	
Tareq Doufish (Solidity developer/Devops Engineer)
Wajed Afaneh (CTO)
Nasser Najjar (Solidity developer/System Architecture)

### Contact
* **Contact Name:** Marsel Adawi
* **Contact Email:** marsel@optionroom.finance
* Website: optionroom.finance

### Legal Structure 
* **Registered Address:** Wickhams Cay II, Road Town, Torola, VG1110, British Virgin Islands
* **Registered Legal Entity:** OR TECHNOLOGY LIMITED - BVI resgistration number: 2051293

### Team's experience
Please describe the team's relevant experience.  If the project involves development work, then we'd appreciated if you can single out a few interesting code commits made by team members on their past projects. For research-related grants, references to past publications and projects in a related domain are helpful.  

### Team Code Repos

### Team LinkedIn Profiles
http://www.linkedin.com/in/marsel-adawi
https://www.linkedin.com/in/tareq-doufish-2270279/
https://www.linkedin.com/in/wajedafaneh/
https://www.linkedin.com/in/nasser-najjar/
https://www.linkedin.com/in/jackngc/ (Advisor)
https://www.linkedin.com/in/0xchristom/ (Advisor)

## Development Roadmap :nut_and_bolt: 

This section should break out the development roadmap into a number of milestones. Since the milestones will appear in the grant contract, it helps to describe the functionality we should expect, plus how we can check that such functionality exists in the product. Whenever milestones are delivered, we refer to the contract to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions it should be clear how the project is related to Substrate and/or Polkadot. We recommend that the scope of the work can fit within a 3 month period and that teams structure their roadmap as 1 month = 1 milestone. 

For each milestone:
* Please be sure to include a specification of your software. Treat it as a contract - the level of detail must be enough to later verify that the software meets the specification.
To assist you in defining it, we created a document with examples for some grant categories [here](../src/grant_guidelines_per_category.md).
* Please include total amount of funding requested per milestone.
* Please note that we require documentation (e.g. tutorials, API specifications, architecture details) in each milestone. This ensures that the code can be widely used by the community.
* Please provide a test suite, comprising unit and integration tests, along with a guide on how to run these.
* Please commit to providing a dockerfiles for the delivery of your project. 
* Please indicate the milestone duration, as well as number of Full-Time Employees working on each milestone, and include the number of days along with their cost per day.
* Deliverables 0a-0d are mandatory and should not be removed, unless you explicitly specify a reason within the PR's `Additional Notes` section (e.g. Milestone X is research oriented and as such there is no code to test)

### Overview
* **Total Estimated Duration:** Duration of the whole project (e.g. 2 months)
* **Full-time equivalent (FTE):**  Workload of an employed person ([see](https://en.wikipedia.org/wiki/Full-time_equivalent)) (e.g. 2 FTE)
* **Total Costs:** Amount of Payment in BTC or DAI for the whole project. The total amount of funding needs to be below $30k for initial grants and $100k for follow-up grants at the time of submission. (e.g. 0.80 BTC)

### Milestone 1 Example — Implement Substrate Modules 
* **Estimated Duration:** 1 month
* **FTE:**  1
* **Costs:** 0.75 BTC

| Number | Deliverable | Specification |
| ------------- | ------------- | ------------- |
| 0a. | License | Apache 2.0 / MIT / Unlicense |
| 0b. | Documentation | We will provide both inline documentation of the code and a basic tutorial that explains how a user can (for example) spin up one of our Substrate nodes. Once the node is up, it will be possible to send test transactions that will show how the new functionality works. |
| 0c. | Testing Guide | The code will have unit-test coverage (min. 70%) to ensure functionality and robustness. In the guide we will describe how to run these tests | 
| 0d. | Article/Tutorial | We will write an article or tutorial that explains the work done as part of the grant. 
| 1. | Substrate module: X | We will create a Substrate module that will... (Please list the functionality that will be coded for the first milestone) |  
| 2. | Substrate module: Y | We will create a Substrate module that will... |  
| 3. | Substrate module: Z | We will create a Substrate module that will... |  
| 4. | Substrate chain | Modules X, Y & Z of our custom chain will interact in such a way... (Please describe the deliverable here as detailed as possible) |  
| 5. | Docker | We will provide a dockerfile to demonstrate the full functionality of our chain |

### Milestone 2 Example — Additional features
...

## Future Plans
Please include the team's long-term plans and intentions.

## Additional Information :heavy_plus_sign: 
Any additional information that you think is relevant to this application that hasn't already been included.

Possible additional information to include:
* What work has been done so far?
* Are there are any teams who have already contributed (financially) to the project?
* Have you applied for other grants so far?
