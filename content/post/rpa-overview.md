+++
authors = []
date = 2020-11-19T22:00:00Z
draft = true
excerpt = "What is this RPA thing?"
hero = "/images/screen-shot-2020-11-19-at-4-30-20-pm.png"
timeToRead = 20
title = "RPA Overview"

+++

# What is Robotics Process Automation (RPA)?

![](https://lh4.googleusercontent.com/66tSAlZRKO1WCPnUSW-UFAJDx2bVeKtrgRilp-nN8eBEuSyySU5akk1sEImK99eqxpzDT-qVASlNxYc0A_d4AwmAcuJV6xS8XpAUUEAAbWmtJt3kQrq4I_bVoifAVZoAWoJUXRKF =624x273)

Common Industry use cases;

![](https://lh5.googleusercontent.com/NmAWutRZoog16RdBmZ3V9yr7FqSreqns9oTbD37A3ys1tBJN8nLNUmVE-VnkHxVoQtY1i8P9YCkvgB5iXZk2M_IyydEwJi6s9qKzNr5_9rN_62s_M8vkQo6hM55Kd6iwQs1eYdLZ =624x264)

Other features that identify RPA are the following;

* Low-code features to build automation
* Integration with enterprise applications
* Enterprise features such as orchestration, and security

# Why RPA?

RPA has had a lot of hype surrounding it as most new technologies do, but there are real world scenarios that definitely are impacted by RPA and its ability to reduce manual tasks, save time, and money. [Gartner says](https://www.gartner.com/en/newsroom/press-releases/2019-10-02-gartner-says-robotic-process-automation-can-save-fina) RPA can save Finance Departments 25,000 hours of avoidable work annually. This is just an example of one vertical that can benefit from RPA. In this series, we will look at additional areas and ways other verticals are using RPA for the same benefits.

* Make decisions faster, with accurate data
* Automate manual activities & time-consuming tasks
* Reduce cycle time and capture additional revenue streams
* Provide better customer service and product interactions
* Build automations to business rules, ensuring compliance
* Collect/clean/organize data for use in AI solutions
* Improve employee experiences and automate repetition

# RPA vs. BPA

RPA and BPA are different but similar systems. Traditionally BPA solutions look at business processes from end-to-end and in some cases involve changing the process itself to optimize it. There can be great benefits from implementing these solutions and optimizing processes. An example of an end-to-end process would be a mortgage application processing with multiple approvals or rejections and workflows that can escalate to a human when there is an issue that needs attention as part of that process.

RPA has traditionally been task-oriented and focused on automating repetitive human tasks. A new edition of RPA Robots is the concept of Unattended Robots to handle long-running tasks and business workflows. A lot of customers want human intervention to handle the exceptions and escalations when Robots run into issues. Unattended Robots escalate tasks when human intervention is required, once help from the human is complete the Robots are notified and can resume the automation. The great thing about BPA & RPA is that they are complementary systems that can work well together and bring new capabilities to both platforms.

# What’s new with RPA?

## AI/ML

One of the newer things that have evolved in the RPA space is being able to integrate AI/ML into RPA. There are three areas in particular document understanding, visual understanding, and conversational understanding where a lot of work is being done to enhance RPA capabilities.

### Document understanding

Many industries such as Finance, Legal, and Banking have very document-intensive processes where employees have to manually extract and interpret data contained in multiple file formats and systems. One of the core features of RPA is the ability to understand the data trapped in these documents. RPA Robots can go beyond simple optical character recognition OCR and utilize pre-trained Machine Learning (ML) models to process structured and unstructured data and recognize various objects like handwriting, signatures, or checkboxes.

<Industry Document use cases>![](https://lh4.googleusercontent.com/L61SU_kRru0jWiXO02l6CgPXbNTqZUJGHwMqbPvuMjZBikzxWB_sOzvd9kHO77yT5uf930HQ0w2ZRulNYn9ytPwdxkvlNoPre2QW2Zhd3_pWCr_7HSY9NTS_50ze-Oy0NPZ1gZOZ =624x208)

### Visual Understanding

With the impact of COVID 19 forcing every industry to go remote, there has been a big demand for virtual desktop environments (Citrix, VMware, Windows Remote Desktop) for remote workers. Traditionally these virtual desktop environments have been difficult to reliably automate, this is due to several factors including changes in the user interface UI would break any existing automations. Now leading RPA Robots are using AI/ML algorithms to see the screen and visually match elements on the desktop just like a human would. This allows the Robots to reliably automate any application in a virtual environment even when there are changes to the UI.

### Conversational Understanding

Chatbots are programs you can interact with, through messaging apps, chat windows, or voice. These bots can be the first interaction that customers have with a business and can set the tone for how they feel and interact on future business transactions. Now RPA Robots can fulfill customer requests from end-to-end. RPA actions can be triggered from the chat process that interact with other systems such as ERPs, CRMs, or Databases. Natural language processing NLP can be used to interpret chats and provide information contextually. From a high-level Chatbots can reply to questions, send alerts, deliver reports, and route to humans when needed.

<Industry Conversational use cases>![](https://lh3.googleusercontent.com/HjNX_54QNpp7_OmF0XHAfzmtlUBVLZARk-O1EpgkGS49alh52cbTA_sCmueVV01d2Z4usC-RiTgo9JUPiYzXbrvO13zNweZVt5pMa-w1KY9JGq-5yOjkP1AYVGPS1ltps69JOhFE =624x317)

### Ecosystem

The use of AI/ML in RPA is growing, and you can find many prebuilt AI/ML models available to perform a multitude of tasks that can be easily dropped into RPA automations. Some end-to-end examples are industry-specific AI/ML models that have been solved for specific use cases such as entity extraction for policy numbers, policy tenure, and client names for document processing in the insurance industry. RPA end-users and developers can easily grab these from a marketplace and add them to an existing workflow.

## Automated Task & Process Discovery

Finding RPA items to automate has traditionally relied on consulting with an automation expert or crowdsource ideas from employees to help surface these items. RPA vendors have been using technology to scientifically discover automation opportunities using employee task data and back-end system info. The data that RPA captures is split into front-end tasks that employees perform and back-end data that IT systems produce. Agents are usually used to look at employees actions that they do every day on their desktops and then use AI/ML to analyze and prioritize actions that could be automated. On the back-end side, IT systems such as SAP, Salesforce, Oracle, ServiceNow, and Microsoft data and logs are analyzed and turned into graphs to be able to visualize processes and see where the bottlenecks are.

<Process Image>

![](https://lh6.googleusercontent.com/Jbn0kaC3QOgKGES18Y0uwg1-JtjSktc59F5u8H7vPTtAAGaAzn6MebHG6JQshOP6n9mhwXfhWchJN6HAnajsjT7_PlGSwhhgcFyfdQgqQYdLMLZUsdmuxX7FbZgA8k3aXOYucNw6 =624x333)

Task vs Process mining

![](https://lh3.googleusercontent.com/sf2pDbZQDpq1zNN5Uqc3dYvhv0SepJ7TdKbi6B3DGKBacwdUifOORl7tY7iC8JsA-yKSx-35vDpXmIdFz78wlxqk3UULxtXHOFeSn6t5zj7U1mSy8D3vyYiIk0lL4rlSeJgxsJs4 =624x328)

## Attended & Unattended Robots

RPA can typically be broken into two types of automation, attended and unattended.

Attended automation consists of a Robot that will assist a human during their tasks and providing information, context, or drive applications during a workflow or task. This is also what’s known as a digital assistant.

Unattended automations consist of workflows that can generally execute without any intervention from a human. These types of automations are able to fulfill the task from end-to-end. Sometimes though there is a need to have a human-in-the-loop to be able to hand off exceptions or decisions to a human to process and then it will continue on with the task. This type of capability is happening with newer RPA vendors. This ability to have a human-in-the-loop to handle exceptions and long-running tasks is helping RPA to handle more complex workflows.

## Integrations

Over time the ecosystem of integrations between applications, vendors, and systems has grown exponentially. Now instead of having to custom build a connector to integrate with say something like Salesforce, many RPA vendors have marketplaces where you can find community-contributed connectors and custom automations to link applications, clouds, and SaaS offerings together. Common categories of pre-built integrations are things like dashboards, workflows, code snippets, and complete solutions to solve domain and industry-specific business problems. Additionally, the line is becoming blurred between IT Automation (Such as Ansible, Terraform, and Chef) and RPA with many of these connectors are starting to bridge the gap between the two. More info to follow in later articles.

Part 2

Hyperautomation + AI/ML

Part 3

RPA & IT Automation