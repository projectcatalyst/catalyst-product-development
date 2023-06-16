---
description: >-
  Analysing differences between having one or multiple products and one or
  multiple teams working on the Catalyst ecosystem.
---

# Product & Teams Structure Comparisons

Project Catalyst is made up of a number of [interconnected services](interconnected-services.md). Different working structures could emerge from Catalyst based on how funding is distributed and how the ecosystem is developed and maintained.



The [product development workflow](product-development-workflow.md) is a fundamental part of how a technical product evolves over time. The effectiveness of this workflow decides what problems are prioritised, what solutions are compared and what feedback is incorporated into deciding and implementing suitable solutions. It is worth understanding the implications of this process when thinking about what working structures will be most effective.



When comparing different working structures for Catalyst it is also important to note what the potential [costs of competition](costs-of-competition.md) are and how this impacts what approaches are sensible when iterating and improving the catalyst ecosystem.



**Context for wording we’ve used in this document**

* Product - We are talking about Catalyst overall as a governance product for the Cardano treasury.
* Service - Any tool or process used within Catalyst. A voting app, assessment tool or a proposal management tool are all example services within the overall product.



## Product & team structure factors

There are a number of factors that determine the effectiveness of different product and team structure approaches.



* **Governance speed** - How fast is the governance process for making decisions?
* **Governance effectiveness** - How many participants are involved in governance and what is the diversity of those participants to help ensure well informed decisions are made?
* **Governance robustness** - How robust is the governance structure? How many participants would need to be corrupt to break the governance process? Are there any ways or bad incentives that could cause the governance process to collapse under pressure?
* **Implementation security** - How effectively can the contributors involved ensure that technical implementations and processes are to a high standard in terms of security? Does the working structure support the creation of the right processes, guidelines and policies?
* **Execution cost** - How is the overall execution cost impacted due to the working structure?
* **Implementation and integration effort** - How much effort is required to implement the product and integrate each of the services into a single product? Are there any wasted or duplicated efforts?
* **Implementation consistency** - How consistent is the implementation, processes and experience between the different services that make up the ecosystem? Over time are these services converging or diverging in their approaches?
* **Product user experience** - How effective is the overall user experience that is produced from the combination of all the different services and processes within the ecosystem?
* **Product workflow process** - How effective does the product get improved using a product development workflow? Is there enough diversity of ideas, feedback, data and knowledge to guide good product decisions?
* **Organisation duplicated efforts and wasted resources** - Are there duplicated efforts across similar organisations that lead to wasted time and resources?
* **Knowledge sharing** - Can a contributor easily provide their knowledge to others within the ecosystem to help bring idea and perspective diversity that leads to better decisions?
* **Skill sharing** - How easily can a contributor share their skills with other teams to help each area of the ecosystem improve?
* **Contributor flexibility** - How easily can contributors move around to work on different parts of the ecosystem that would produce the most impact?
* **Implementation flexibility** - How easy is it for teams to change their implementation approach when there is a need to pivot or improve?
* **Funding competition** - What competition exists for attracting funding and resources to each part of the ecosystem? How does that impact the incentives and outcomes for those involved?



## Multiple **products**

A working structure for multiple products mean having completely separate treasury governance products that work independently. The community would be able to use them separately from one another to request funding from the Cardano treasury.

### Advantages

* **High governance effectiveness** - Providing each product team is large enough there should be enough diversity of ideas and knowledge for governance decisions.
* **Good Implementation security** - With enough contributors there can be sufficient security expertise that can move and work on the different services provided in each separate product team.
* **Low Implementation and integration effort** - Each product team maintains its own services so the integration and implementation effort should remain low.
* **Good implementation consistency** - The consistency of the separate products should remain high as each product team owns the full implementation. Each product however would have their own approach to implementation and processes.
* **Good product workflow process** - Each product team owns their entire product workflow. All contributors can provide ideas, insights and data into the process to help inform which services require the most attention and which ideas look the most promising.
* **Good governance robustness** - Providing there are enough contributors in a given product team the chances for corruption should start to reduce. The main governance risk revolves around having competing products - if one product begins to fail the governance process could collapse.
* **Moderate contributor flexibility** - Contributors would be able to move around easily within the given product team they are working in.

### Issues

* **Very high funding competition** - For two completely separate funding products to exist there would be a need for significant regular funding as both product teams would be constantly competing.
* **High execution cost** - Execution cost would be very high as separate products would be implemented. Competition also reduces the incentive for teams to collaborate on code and process reuse.
* **High organisation duplicated efforts and wasted resources** - Both projects will need to use significant resources for marketing and adoption of their product. These resources could have been spent on innovation and improving the products.
* **Weak knowledge and skill sharing** - As both products compete there is a smaller incentive for knowledge and skills to be effectively shared between the project teams.
* **Average implementation flexibility** - Implementation would take a moderate amount of time for making changes assuming both product teams and governance are a moderate size.
* **Average governance speed** - Providing both teams are a moderate size this could result in a slower overall governance speed.
* **Average product user experience** - The end user first needs to determine which product to use before getting involved with the ecosystem which adds complexity. By having two products that compete for the same amount of total funding there is the risk of a lower quality of user experience due to less resources being available for each product team.



## Single p**roject team per service**

Having single project teams per service means having one product but for each service only having one project team who works on that service such as a voting app or assessment tool. One project team could work on multiple services.

### Advantages

* **Very high governance speed** - Small teams can govern decisions quickly.
* **High implementation flexibility** - Easier for smaller team to make bigger implementation pivots.
* **Good execution cost** - Only one project team working on each main service.
* **Good implementation and integration effort** - Only one instance of each service within the product to integrate and implement.
* **Good product workflow process** - Each team focusses fully on solving one problem well. Small teams could however lack insights and feedback from other service teams without the right environment and incentives.
* **Low organisation duplicated efforts and wasted resources** - No competition to get adoption on multiple services so ensures resources are better used on improvements.
* **Moderate governance robustness** - Project team doesn’t compete for resources reducing risk of governance collapse. Smaller team increase how easy it becomes for governance to become corrupted.

### Issues

* **Moderate governance effectiveness** - Smaller siloed teams add risk of a lack of diversity of ideas and knowledge for effective governance.
* **Moderate funding competition** - Each service project team is competing for resources from the same funding pot which creates risk around the environment and incentives.
* **Average implementation security** - Smaller teams competing for funds may create risks in the implementation security due to lack of resources.
* **Average implementation consistency** - Small teams can approach implementation and processes differently and are not effectively incentivised to ensure there is alignment.
* **Average product user experience** - More risk of a poor user experience across different services if they are not incentivised to collaborate and provide strong integration alignment.
* **Average contributor flexibility** - Contributors would need to request to join other service project teams to move around.
* **Weak knowledge and skill sharing** - No incentive to bring knowledge or skills to other services if contributors incentivisation and sole focus is on their own specific service.



## **Multiple project teams per service**

Multiple project teams per service means having multiple implementations of the same given service. For instance there could be three project teams that each work on a separate voting app.

### Advantages

* **High governance speed** - Small teams can make decisions quickly.
* **High implementation flexibility** - Community has alternatives meaning fast and abrupt changes or pivots can be made to implementation.

### Issues

* **Very high execution cost** - Each service project team competes with the others and also must integrate the other services they depend on. Each of those teams still has the admin work of meetings, personal finances, tax etc impacting overall speed and cost.
* **Very high implementation and integration effort** - Multiple services that provide assessments would make any voting apps more complex as now they need to integrate multiple assessment sources. The more services there are under a single product ecosystem the more complex the implementation and integrations become.
* **Very low implementation consistency** - Each service in the ecosystem can be implemented differently meaning a risk of low consistency across the set of services.
* **Very high organisation duplicated efforts and wasted resources** **-** Every service competes for funding and must spend time on marketing and adoption efforts which wastes resources and creates duplicated efforts for the implementations.
* **Very high funding competition** - Multiple service project teams compete from same funding available.
* **Weak product user experience** - High risk of complex user flow due to multiple services for each part of the product process.
* **Weak governance robustness** **-** Smaller teams make it easier for a project team to become corrupt. High competition can also lead to governance instability due to the risk of potential collapse.
* **Weak governance effectiveness** - Governance of the overall product ecosystem becomes complex with many different project teams competing for resources.
* **Weak implementation security** - Constant competition between service projects adds risk of implementation efforts falling short on security due a need for fast progress and a lack of resources.
* **Low knowledge and skill sharing** - Multiple competing projects don’t incentivise knowledge and skill sharing.
* **Low contributor flexibility** - Difficult for contributors to easily move between separate competing project teams.
* **Average product workflow process** - Small competing teams risk having insufficient knowledge, data and feedback to make well informed product decisions.



## **Single project team**

A single project team means that the same team is working on each of the services that make up the Catalyst product. There is a single product and each service is maintained and iterated on by a single large project team.

### Advantages

* **Very high governance effectiveness** - All ecosystem contributors are incentivised to participate in governance.
* **Very high governance robustness** - The maximum amount of participants are included for oversight of the overall product and its services with little to no risk of failing due to competition.
* **Very high knowledge and skill sharing** - Contributors can provide their knowledge and skills anywhere across the different services within the ecosystem.
* **Very high contributor flexibility** - Contributors can move to anywhere they believe will add most impact without asking others.
* **High implementation security** - Any expertise on security can spend time on where it is needed most across the ecosystem.
* **High implementation consistency** - Shared governance and contributors helps align consistency between service implementations.
* **Low implementation and integration effort** - Single service for each part of the ecosystem with collective governance structures reduce the efforts around integration.
* **Low organisation duplicated efforts and wasted resources** - No effort is needed to market and onboard people to the product over competing ones. Any competition and marketing efforts are instead used for competing against other layer one smart contract chains.
* **Low funding competition** - No competition between projects and instead competition is between contributors based on skill and impact. Less competition on funding means more time spent on producing the highest impact possible.
* **Good execution cost** - Only an initial single set of services are implemented and improved. The team may add multiple variations of the same service in the future for testing.
* **Good product user experience** - Provides a single user experience, more resources can be focussed on a seamless experience rather than marketing or rushing implementations due to competition.
* **Good product workflow process** - Larger team provides maximum amount of capability to include strong data, feedback and oversight into product decisions made across each service.

### Issues

* **Very slow governance speed** - Risk of slow governance due to having the largest amount of people governing the whole product.
* **Low implementation flexibility** - The product being used will have no alternatives and would also likely have higher thresholds for governance decisions. This increases the risk in having less ability to quickly pivot implementations.



## Key outcomes

**Competition is expensive**

Competition between multiple project teams working on different products or services for the same ecosystem results in a far higher usage of resources. More resources end up being used implementing similar implementation features and processes rather than creating new innovation. Competition also leads to significant efforts around adoption and marketing that wouldn’t exist if collaboration was used instead.



**Competition is riskier**

Competition for creating services or products for the same ecosystem means there’s a constant chance one project team will fail and then not secure further funding. In those events there are risks around governance and what a failed project team is able to do in terms of data access, updates or access to any treasury funds. The higher the number of project teams the easier it is for governance processes to become unstable. Competition also drives the need to try and innovate faster than the alternatives. In this environment project teams are incentivised to cut corners and improve implementations at a faster rate than what may be safe to do so.



**Competition hinders collaboration**

Environments that encourage competing projects don’t foster the highest potential of human collaboration. If there are separate projects who compete for a fixed amount of funding available there is lower incentive to collaborate. One project team helping another could result in the other project being funded over themselves. This dynamic also means there is lower incentive to share skills and knowledge across the ecosystem which can reduce the speed of innovation.



**Separate project teams decrease alignment and flexibility**

Multiple project teams working independently with their own governance and product development flow increases the risk of less alignment of the implementation and processes used. This makes it more complex for contributors to get involved in the ecosystem and pushes them towards picking a single project team to join rather than supporting multiple. Lower alignment also decreases flexibility as contributors have to have the skills relevant to the different implementation and processes used by different project teams to easily move between teams.



**Importance of effective product development workflow**

For a larger team of contributors to work effectively under a single project the quality of the product development workflow is of paramount importance to maximise potential impact. The process will need to ensure the diversity of ideas and feedback are involved at each relevant stage and that the wider community are able to participate in that process. The competition of ideas and thought are an area where competition is important for more rapidly finding the optimum solution.



**Importance of good governance process**

The larger the amount of participants the more complex governance can become. If a single project team were to be used over a more competitive project based working environment the governance process would need to be effective and efficient. All participants involved in the governance would need exposure to all the relevant information to be well informed when making decisions and the process also needs to be efficient so that progress does not become stagnant.



**Multiple services or products under a single team**

Competition between project teams isn’t required to have multiple solutions for solving the same problem. Contributors under a single team can still create multiple services, or A/B test variations, to compare the result. If contributors have an objective to create the highest impact possible this can often mean exploring new approaches to test and improve the product and processes.



**Alternative implementations can be introduced anytime**

Any of the above work structures should not prevent people from making new proposals on ways to innovate the ecosystem. Any approach does not have a monopoly over execution as the wider community governance always has the final vote and will decide on where to distribute treasury funds.



## Summary

* A single project team that utilizes a good product development workflow and governance process should be the most collaborative, cost efficient and robust approach to innovate the Catalyst ecosystem.
* A single project team reduces wasted resources and duplicated efforts meaning more funds can be allocated to securing the best possible talent to help innovate and improve the ecosystem. The higher the quality of talent the ecosystem can attract the better the potential outcomes.
* Competition can be a failure to collaborate. Competition is better suited around ideas and solution options rather than entire project teams and organisations. Competition usually leads to increased cost and risks and lower levels of collaboration due to the environment it produces.
* Over time there may be clear benefits to providing alternative solutions to a given problem. In this event these alternatives can still be implemented by a single project team. However these changes can also still be implemented by new proposal project teams.
* Wider community governance on the ecosystem will help prevent any risks of stagnation. Contributors within the single project team can always be changed through governance.
