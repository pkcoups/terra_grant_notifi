# Terra Grant Proposal Template

### **FINAL DOCUMENT MUST BE SUBMITTED IN THE FORM OF A GITHUB REPO FORMATTED IN MARKDOWN**

- **Project Name:** Notifi
- **Team Name:** Notifi Networks, Inc 
- **Payment Address:** terra175pxavlwh4a8fe7xllc6tzdk69euw2d9r3q3uv

## Project Overview

### Overview


**Notifi aims to be the customer engagement layer that bridges projects in web3 with users in the real world by providing a simple service to provide a straightforward messaging experience for users.**
 
Getting constant push notifications from your email, messages, social media platforms, and every other app can be overwhelming as it is. With the explosion of a new generation of blockchain projects and the eventual mass adoption by the public in the banking (Defi & Payments), NFTs, and the gaming industry, the average consumer will need a new web3 ready notification experience to track and manage all their critical activities. 

Notifi aims to provide a simple entry point to bring enhanced customer experince by providing projects an easy way to integrate. Developers will get worldwide connectivity by using Notifi SDK's and getting support for all consumer channels 

**Products and Solutions:** 

Notifi helps web3 projects of all sizes create meaningful moments with their users across the globe—from the simplest text messages to financially urgent communications. We intend to connect everyone to their world via our messaging service thats and to fuel the future of communications by bringing the world closer with these core product offerings:

1) **Notifi APIs**: Our focus will be to allow developers worldwide to use Notifi to unlock communications infrastructure through simple APIs that are simple enough for any developer to use yet robust enough to power the world's most demanding applications. We will provide APIs to dapps to provide their users with a first-class/native experience. 

2) **Notifi Center**: If users want to tailor their push notification experience, Notifi Center is a mobile and web application that will allow the consumer to have a single source of truth to view and manage all their messages in the web3 world.  

3) **Notifi Ad Manager**: With our messaging platform, we will provide marketers the ability to create cohesive, multichannel engagements that drive business growth and retention to the growing crypto user segments. Use Notifi segmentation data of wallets to select your audience and push your message or airdrops at scale! 



- An indication of how your project relates to / integrates into Terra.
    
    - Our focus is to be **the** messaging layer for the Terra Ecosystem of Projects and Users.  

- An indication of why your team is interested in creating this project.
    
    - We are a team of builders who have spent considerable time in the messaging & observability space and have had the opportunity to launch these services for cloud providers such as Oracle Cloud and AWS. We see an exciting opportunity to build out the next layer service for web3 and help accelerate the adoption of the general public to projects.  


### Project Details

We expect the teams to already have a solid idea about your project's expected final state. Therefore, we ask the teams to submit (where relevant):

- Mockups/designs of any UI components
  - https://www.figma.com/file/4S9U3WRO7z1JzNP9xIoAyH/MVP-Designs 
- Data models / API specifications of the core functionality
  - https://docs.notifi.network/ 
- An overview of the technology stack to be used
  - Backend is composed of 2 separate planes. 
    - The first is the control plane where users create/manage their accounts along with their alerts and contact information.
    - The second is the dataplane where the Notifi systems pick up configuration changes the users made in the control plane, and run the commands in a highly available system. This is the plane that will listen via RPC API nodes, aggregate and ETL relevant blockchain events and changes. According to filter rules, associated messages will be sent from here (email, SMS, Telegram, voice call, etc).
  - All backend components are written in .net core for off-chain logic. On-chain logic will depend on the particular L1.
  - Frontend is a React/Typescript application that interfaces directly with our public API.
- Documentation of core components, protocols, architecture, etc. to be deployed
  - https://lucid.app/lucidchart/aac4d2bd-d495-4a1b-b84a-7a9a874dba6e/edit?invitationId=inv_8380077a-fd13-41cd-a7f5-93c08ee43dda
- PoC/MVP or other relevant prior work or research on the topic
  - https://www.notifi.network/ 

### Ecosystem Fit

Help us locate your project in the Terra landscape and what problems it tries to solve by answering each of these questions:

- Where and how does your project fit into the ecosystem?
  - Defi 
  - Gaming
  - Governance 
- Who is your target audience (parachain/dapp/wallet/UI developers, designers, your own user base, some dapp's userbase, yourself)?
  - Dapp builders and developers 
  - Users/Customers of Dapps
  - Wallets (Metamask/Phantom etc..) 
- What need(s) does your project meet?
  - Community Support (ecosystem for go to market + developer support for troubleshooting and guidance) + Funding   
- Are there any other projects similar to yours in the Terra ecosystem?
  - Valkryie (Terra): Primiarily focused with on chain wallet transactions. Wallets are targetted and then an air drop of a specific token is done. Notifi provides distinction in two fundemental ways: 
    - Dapps own the Communication Experience Natively. We provide First Class Native Customer Experiences in the Dapps via our SDK/APIs that empower developers to manage and maintain a relationship with their users indefinetly and not just a one time air drop. Using our tools, dapps can focus on an intimiate rentention and engagement with their customers with continual messaging on governance, events, announcements.  
    - We provide web2 bridges that allow users to be notified of alerts/messages from the web3 world to web2 via SMS/Phone/Third Party Messaging Platform like discord/telegram. At the heart of it we are excelling in one area, deliver notifications through your preferred channel where there is a high confidence that the message will be read and actioned upon.
    
  - EPNS (ETH). The majority of their strategy is focused on their mobile app/dapp to subscribe to wallets to recieve notifications in app about transactions that occur. They designate this as a decentral solution but it is just a webhook that listens for events that happen from other aggregators. Where we differ tremendously is it that we think that a developer toolkit to natively provide these notifications to the customers is the key for pursuing adoption and scale of customers as well as recruiting dapps to enhance the customer experience. EPNS is focusing on having dapps and contracts kick off events to send customers to their app, we believe this is important to have but, also to bridge a better customer experience inside the dapp itself.
  
    Another area that we differ is in our foundation of monitoring nodes and wallets on the layer 1 itself. We plan to fully index and store changes so that we can pro-actively trigger alerts and provide the notification, but to go full end to end to also allow users to create a function or execution command. A common use case will be, if my alert of liqudiation notification is triggered, then execute my comand to add colleteral and sign the transactions automatically. 
    
  - XMTP. These folks are focusing on more cross chain messaging where we are specifically focused on allowing any dapps to message their users and customers to converge their notifications from all projects they currently subscribe to. 
   
  - Dialect (SOL) Mostly focused on wallet to wallet communication with a large emphasis on how do I send wallet owners messages such as wanting to bid on an NFT in their ownership. But not super different in terms of our product direction, just a matter of priortization and use case adoption. 

## Team

### Team members

 - Paul Kim : CEO 
 - Nimesh Amin : CTO 
 -
### Contact

- **Contact Name:** Paul Kim 
- **Contact Email:** Paul.Kim@notifi.network

### Legal Structure

- **Registered Address:** 3815 S Othello Street STE 100 PMB 360 Seattle Washington 98118 United States
- **Registered Legal Entity:** Notifi Networks, Inc 
- 
### Team's experience

Paul Kim : Director of Product at Circle (New Circle Account Platform + Circle Yield (CEFI), Director of Product at Oracle Cloud Infrastructure (Developer Tools + Messaging and Observability. Launched Oracle Notification Service + Oracle Critical Engineering Alert and Notifications aka PagerDuty replacement), GPM at Grab (Launched GrabPay for 6 Countries for P2M and Product Lead and Architecht of the merchant platform), Apevera (co founder for identity management and security profiling) 

Nimesh Amin : Senior engineering leader at OfferUp Inc (owned Search and Inventory systems). Architect at Oracle Cloud Infrastructure (Architect for organization that owns Streaming/Messaging/Email/Inter-service Connectors). Principal engineer at Microsoft on Xbox (owned E2E video/tv passthrough pipelines on Xbox, along with video streaming). Architect at iStreamPlanet, now acquired by Turner Broadcasting (designed and built foundational components such as segment pub/sub for reliable, distributed transcoding of video assets for VoD and live video).

### Team Code Repos

- [https://github.com/nimesh-irisio/notify/](https://github.com/nimesh-irisio/notify/)
- [https://github.com/nimesh-irisio/notify-client/](https://github.com/nimesh-irisio/notify-client/)


### Team LinkedIn Profiles (if available)
- [https://www.linkedin.com/in/1paulkim/](https://www.linkedin.com/in/1paulkim/) 
- [https://www.linkedin.com/in/nimeshamin-seattle/](https://www.linkedin.com/in/nimeshamin-seattle/)
- [https://www.linkedin.com/in/hyungjoon-kim-a69b0573/](https://www.linkedin.com/in/hyungjoon-kim-a69b0573/)
- [https://www.linkedin.com/in/shuyu5100/](https://www.linkedin.com/in/shuyu5100/)
- [https://www.linkedin.com/in/hellonathanchung/](https://www.linkedin.com/in/hellonathanchung/)
- [https://www.linkedin.com/in/hoil-chung-abb15755/](https://www.linkedin.com/in/hoil-chung-abb15755/)
- [https://www.linkedin.com/in/kimothywu/](https://www.linkedin.com/in/kimothywu/)


## Development Status

If you've already started implementing your project or it is part of a larger repository, please provide a link and a description of the code here. In any case, please provide some documentation on the research and other work you have conducted before applying. This could be:

- references to conversations you might have had related to this project with anyone from Terra
- previous interface iterations, such as mock-ups and wireframes.

## Development Roadmap

This section should break the development roadmap down into milestones and deliverables. Since these will be part of the agreement, it helps to describe *the functionality we should expect in as much detail as possible*, plus how we can verify and test that functionality. Whenever milestones are delivered, we refer to this document to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions, it should be clear how your project is related to Terra. We *recommend* that the scope of the work can fit within a three-month period and that teams structure their roadmap as 1 milestone ≈ 1 month.

For each milestone,

- make sure to include a specification of your software. *Treat it as a contract*; the level of detail must be enough to later verify that the software meets the specification.
- include the amount of funding requested *per milestone*.
- include documentation (tutorials, API specifications, architecture diagrams, whatever is appropriate) in each milestone. This ensures that the code can be widely used by the community.
- provide a test suite, comprising unit and integration tests, along with a guide on how to set up and run them.
- commit to providing Dockerfiles for the delivery of your project.
- indicate milestone duration as well as number of full-time employees working on each milestone.
- **Deliverables 0a-0d are mandatory for all milestones**, and deliverable 0e at least for the last one. If you do not intend to deliver one of these, please state a reason in its specification (e.g. Milestone X is research oriented and as such there is no code to test).
 

### Overview

- **Total Estimated Duration:** 1.5 months
- **Full-Time Equivalent (FTE):** 2 FTE
- **Total Costs:** 30,000 USD

### Milestone 1 — Implement Terra Alerts Pipeline with Messaging. Users, via our API or Notif web app, should be able to create Alerts on Terra. The messaging endpoints should have full verification implemented to prevent spam, along with allowing users to create not only 1:1 alert:endpoint, but also 1:many alert:endpoints.

- **Estimated duration:** 1.5 month
- **FTE:** 2 (1 Dev + 1 UX) 
- **Costs:** 30,000 USD

## Future Plans

Please include here

- how you intend to use, enhance, promote and support your project in the short term, and
- the team's long-term plans and intentions in relation to it.

## Additional Information

**How did you hear about the Grants Program?** Hashed 
