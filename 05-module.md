# Module 5 - Understanding the Value of DevOps for Teams and Organizations

## Objectives

* Describe "How are DevOps organizations structured across Business System teams and Platform teams?".
* Explain the need for DevOps organizations to be product-centric.
* Discuss the need for autonomous teams.
* Explain the need for scaling and its mitigation.


---

## Topic 1 - Organizational Models

### **Organizational Model**

The organizational model describes how the business or organization is structured in departments, units and teams. It provides an outline of how the various activities are directed to achieve a specific goal.

The model determines how information flows between the different levels within a company.


### **DevOps Impact on the Organizational Model**

In a traditional environment, people work in technically-oriented silos or teams. For example, the Operations department for running the applications and the Development departments for developing the applications.

DevOps focuses on one team doing the work, hence, reducing communication and coordination issues.

In a traditional environment, multiple teams share different priorities, goals, time frames, and cultures. This makes successful communications and cooperation difficult.

The DevOps team shares the same goal of providing a valuable customer experience.

Many traditional organizations are not aligned with the way the IT service are structured and organized, with multiple or distributed teams working on producing and delivering the same IT service.

DevOps focuses on an operational model that facilitates collaboration within and between the teams to provide a valuable customer experience.


### **Organizational Model and Conway's Law**

Any piece of software reflects the organizational structure. Organizations that design systems are constrained to produce design, which are copies of the communication structures of these organizations.

In other words, means that complex organizations end up with complicated and convoluted systems. The complicated organizational structure and the design do not allow teams to perform:

* Experiments, especially with larger services.
* Fast and reliable changes, resulting in less happy customers.

The law is difficult to break, meaning, complex organizations are bound to create complex architectures. If an organization wants a simple architecture, it first needs to organize itself simply.

This is the reason many organizations organize themselves around multiple small teams responsible for services. These teams are autonomous, independent, and end-to-end responsible for the entire lifecycle of the services they create.

> http://www.melconway.com/research/committees.html

> https://www.thoughtworks.com/insights/blog/demystifying-conways-law


### **The DevOps Approach to Organizational Model**

Organizations usually end up creating Business Systems teams to create independent and autonomous teams keeping the platform structure intact. These teams have all the required knowledge and skills, and might help in creating a better setup. However, reusability is zero.

Such a setup requires many dependencies due to which various Business System teams cannot operate completely independently from each other. They need centralized capabilities that lead to waste. Therefore, taking DevOps literally is no solution.

In a traditional organization, each department works for specific functionality and has a string dependency on other departments. In such a dependency, if there is a new requirement or a change in the existing feature of an application, what will happen?

You have to connect with each department to discuss the requirements and raise the required request. Moreover, you have to wait when the request moves form one department to another for processing. Sometimes, such a wait can lead to even more than 90% of the entire turnaround time.

In a DevOps environment, Business Systems teams are structured around a self-service platform.

The self-service platform is a product in itself and is maintained by eh Platform team. This platform offers a comprehensive set fo standardized self-service capabilities to Business System teams, such as monitoring and security. Such a setup enables Business System teams to operate autonomously by placing their application and infrastructure code on the self-service platform and completely managing their products.

On the other hand, the Platform team manages and monitors the system qualities of tis products independently from the associated application products. Such an organizational model enables teams to take end-to-end responsibility, for their products or services.

Therefor, both the teams, Business System teams and Platform teams, are responsible for the qualities of their products, such as availability and performance.

As the Business System teams use the platform products or services and are the customers of the Platform team, it is essential for both the teams to interact with each other. This is where APIs help them to interact with each other. It is a piece of software that allows two applications to talk with each other. Such an infrastructure setup in a DevOps organization results in various reusability benefits, such as Microsoft Azure, AWS and GCP.


### **Business System Teams and Platform Teams**

Business System teams and Platform teams need to work closely to ensure the correctness of the service. It requires the separation of roles and responsibilities between the teams to prevent unauthorized transactions that can be performed through the platform.

The key differences between the responsibilities of two teams.

**Business System Teams**

* Manage end users, services, and products.
* Take end-to-end responsibility for the products or services with the required support from the Platform teams.


**Platform Teams**

* Manage platform products used by Business System teams.
* Support Business System teams to work more effectively by providing platform (or Infrastructure) services through self-service and automation.


### **Product-Focused Approach - The Benefits**

By introducing Business Systems teams, organizations move away from the siloed activity focused approach and move towards a product focused approach.


Activity Focused organizations (Silo approach):

* **Embrace specialism**: each individual performs a specific activity or task at a time, such as creating the user interface.

* **Organized functionally**: people are added to specific resource pools basis their specialization, such as a pool of programmers.

* **Focus on projects**: the team is created for a specific project. Once the project completes, individuals are assigned different projects. They can also be assigned multiple projects at a time.

* **Optimize for resource utilization**.

* **Have limited responsibility**: the team is responsible and accountable for the working product throughout the project lifecycle.


Product Focused organizations (Team approach):

* **Embrace multiple skills**: people are oriented on delivering work requiring multiple skills, such as, a programmer who writes code also knows how to automate a delivery process.

* **Organized in teams**: people are organized in teams and are end-ot-end responsible for a product that it delivers and/or maintains.

* **Focus on products**: the team works for delivering or maintaining the products or services with the customer-centric approach.

* **Optimized for speed**: organizations are optimized for lowering the cycle time for a product.

* **Have end-to-end responsibility**: the team is solely responsible and accountable for the overall quality of the working product throughout its entire lifecycle, including the production environment.


Some of the process throughput related issues seen in siloed organizations are suboptimal flow chain of events, low process throughput, buildup of work in progress, low responsibility for the end-result, time-consuming task switching, and difficult for resources.


### **Activity: Organizing Service Teams**

Considering your current organization, how would you organize the service teams?

Create at least two variants and list their pros and cons.

| Aspect         | Pros           | Cons           |
|----------------|----------------|----------------|
| Communication  |                |                |
| Responsibility |                |                |
| Autonomy       |                |                |
| Initiative     |                |                |


### **Topic Summary**

The organizational model describes how the business organization is structured in departments, units, and teams. DevOps focuses on one team doing the work, hence, reducing communication and coordination issues.

Organizations which design systems are constrained to produce designs which are copies of the communication structures of these organizations (Conway's Law).

In a DevOps environment, Business Systems teams are structured around a self-service platform. By introducing Business Systems teams, organizations move away from the siloed, activity-focused approach and move towards a product-focused approach.

Business System teams and Platform teams need to work closely to ensure the correctness of services.


---

## Topic 2 - Team Autonomy

### **Autonomy**

* Autonomy is the independence that result in self-directed actions.
* Autonomy is the ability that enables people to make decisions independently about what to do without being influenced by someone else.
* Autonomy is the freedom from external control that allows people to govern themselves and organize their activities.


### **Autonomy for DevOps Teams - The Need**

Autonomy is essential for DevOps Teams as it strongly supports the three DASA DevOps principles:

* **End-to-End Responsibility**: the power and freedom bring with it more responsibility. Being self-directed means more accountability and responsibility for the products or services.

* **Customer-Centric Action**: autonomy allow you to consider the customer's needs and deliver the maximum value.

* **Cross-Functional Autonomous Teams**: these teams are problem solvers, and they cannot work without having the required freedom.


### **Achieving Autonomy Through DevOps**

In a DevOps environment, autonomy is primarily achieved by structuring the teams around distinct services and products, and making them independent.

* How does team structure enable autonomy?
* How do independent teams help achieve autonomy?


**How does team structure enable autonomy?**

In a DevOps environment, the Business System teams are structured around automated self-services, which are maintained by the Platform team. These services enable Business System teams to manage their products or services almost autonomously.

In the same way, the Platform teams monitor and manage their products independently from the availability of the application products, which use the platform products.

Both, the Platform teams and the Business System teams are responsible for the qualities of their own products.


**How do independent teams help achieve autonomy?**

The focus on Continuous Delivery helps independent teams to become autonomous. With this ultimate aim, they work almost independently from other teams to deliver continuous value to the customers. It is possible only when they are free to make their own decisions and can solve the problems.

Being independent, these teams are end-to-end responsible for the quality of the product or service throughout the entire product lifecycle, thus removing the need for any methodical handover.


### **Determining the Autonomy of Teams**

The three-step design criteria help organizations to determine the autonomy of teams.


**<ins>Customer</ins>**

Customers use the products or services, therefore, it is essential to know your customer, understand their requirements, and determine the type of services they are looking for. Such an analysis of your customer makes it easy to determine customer value.

**Aspects to Consider**

* Who is your customer?
* What are their requirements?
* What services are they looking for?


**<ins>Technology Stack</ins>**

Considering the customer's requirements and the types of services, the technology stack is created for the team. The team is, therefor, majorly dependant on the technology for the successful delivery of customer value. It means the deeper the technology stack, the more knowledge and skills the team requires. Cloud technology helps minimize the team's dependency on the underlying technology.

**Aspects to Consider**

* What type of application does the team need to build?
* What is the development cost and time to market?
* Is the application secure and scalable?


**<ins>Knowledge</ins>**

Considering the customer and the technology stack, the required skills and knowledge are identified for the team. This step ensures whether the team has the identified skills and knowledge required to deliver the value to the customer. It also determines the number of people required within the team by estimating units-of-work, such as service requests, customer demand, incidents, changes, and problems.

**Aspects to Consider**

* What skills do the team require to deliver the product/service.
* What are the units-of-work, the team will be processing?
* What is de Definition of Done (DoD) for the units-of-work?


> https://www.quintgroup.com/en-in/insights/white-paper-how-to-improve-it-performance-based-on-customer-experience/


### **Intrinsically Motivated Teams**

DevOps teams are intrinsically motivated and care about what they do. According to Daniel Pink, three primary aspects of intrinsic motivation are:

* Autonomy.
* Mastery.
* Purpose.


**Autonomy**

Autonomy means being self-directed. People should be able to direct or control their life and work. Self-direction keeps people fully motivated by enabling them to control what they do, when they do it, and how they do it. Such control motivates them to think creatively and build trust.

Organizations that focus on autonomy free their people from the additional pressure of following the traditional workplace rules, such as regular office hours, dress code, and numerical targets.


**Mastery**

Mastery is people's desire to improve their skills in specific areas. It requires dedication, hard work, and space to learn and practice. The desire of mindset to become masters enables people to see their potential as being unlimited. People want to attain mastery for their benefits, and organizations utilize those master skills for business benefits.


**Purpose**

Purpose enables people to understand the bigger picture and the reason (often an altruistic-selflessness reason) behind any work they are doing. The absence of a purpose leads to disengaged and unmotivated people at the workplace, as they do not know where they are investing in the bigger organizational goals. People who know they are working toward something larger and more important than themselves are often the most hardworking, productive, and engaged.


> RSA ANIMATE. Drive - The surprising truth about what motivates us: https://www.youtube.com/watch?v=u6XAPnuFjJc

> https://www.mindtools.com/pages/article/autonomy-mastery-purpose.htm


### **Intrinsically Motivated Teams - The DevOps Context**

Daniel Pink's model of motivation throws away the idea of motivating people through reward and punishment. It aims at making people care about what they do.


**<ins>Autonomy</ins>**

DevOps teams are made independent to the maximum extent by setting these up organizationally and technologically. Independence helps teams obtain significant autonomy to act on behalf of their customers.

**Example:** Most of the software organizations practice motivating their people through autonomy. They allow their engineers to work in their development projects by providing sufficient time. An organization does this to enable its engineers to try out and test new ideas that can deliver organizational benefits, such as improved processes or innovative solutions.


**<ins>Purpose</ins>**

DevOps teams work closely with their customers. As a result, their sense of purpose triggers on a day-to-day basis.

**Example:** organizations should look for ways to encourage their workforce by supporting them in finding their work purposes, such as by connecting their personal goals to organizational targets. The way helps organizations to win their people's minds and hearts.


**<ins>Mastery</ins>**

The independent nature of a DevOps team encourages its members to practice mastery to act more timely and effectively. Engineers usually get several opportunities in this direction to develop the required skills. However, they need to work equally on their generalized skills (or broader knowledge) to be an efficient DevOps team member.

**Example:** a developer who is an expert in core Java programming motivated by mastery might want to become an expert in Java mobile applications. Any appreciation, reward, or medals are less important for mastery motivated people than continuous improvement.


### **Importance of a Decoupling Point within the Technology Stack**

A decoupling point is essential to establish autonomy for the various Business System teams of a DevOps organization.

The decoupling point defines the point within the technology stack where the responsibility is transferred between the Business System team and the Platform team.

In a DevOps organization, the Platform team provides a platform in the form of a self-service product that requires maintenance, innovation, and ownership. Such a model offers the following benefits to the Business Systems teams:

* **Infrastructure Reuse**: Business System team can reuse the infrastructure without impeding their speed an autonomy.

* **End-to-End Responsibility**: Business System teams take full responsibility for their service during its complete lifecycle.


### **Spotify: an example for Autonomous Team**

A good example of an organization that is using autonomous teams is Spotify. Spotify uses autonomous teams to achieve collaboration between these teams and ensure sharing and reuse of skills and knowledge.

With the establishment of autonomous teams focused on specific (set of) services, Spotify is able to embrace DevOps principles to become truly customer-centric, end-to-end responsible, and experimenting and innovate in nature. As a result, a proper feedback loops is established, enabling these teams to learn faster and better.

Spotify has organized its employees in teams called _Squads_. These teams are small, multidisciplinary, and autonomous. Each squad is similar to the Business System team and focus on specific services. They incorporate every component necessary to support a service through its entire lifecycle, from idea to production. Squads decide their own way of collaborating and are stimulated to apply Lean Startup principles, such as Minimal Viable Product and Validated Learning.

Squads that work in related areas or use similar skills and knowledge are organized as _Tribes_. The tribes function as a sort of a startup company and have a fair degree of freedom and autonomy. A _Tribe Lead_ heads a tribe who is responsible for providing the best possible habitat for the squads within that tribe.

The squads in a tribe are all physically present in the same office, normally right next to each other, and the lounge areas nearby to promote collaboration between the squads. Tribes hold gatherings regularly. Such a get together includes live demos of working software, new tools and techniques, and other.

You have identified the benefits of autonomous squads and tribes, but full autonomy has its downside too. A potential downside to autonomy is the lack of communication and sharing of knowledge among people with similar skills. That's why Spotify includes _Chapters_ and _Guilds_.

A chapter is a small family of people having similar skills who work within the same general competency area and the same tribe. These people come together to ensure their way of working can be discussed and improved, or at least standardized, with colleagues learning best practices from one another. The chapter is all about maintaining, developing, and improving standards in a particular area of expertise.

Guild act as a community of people who share knowledge, tools, code, and practices. Unlike chapters that are always located in the same tribe, guilds spread across the entire organization. Some of the examples of guilds are Developer, Tester, and Agile Coach.

With many teams, it becomes really challenging for Spotify to enhance the skills and performance on a continuous basis. To aid in this, there are quarterly surveys for all the squads. The given figure shows the result of one such survey for five squads grouped together within a tribe.


> https://www.youtube.com/watch?v=Yvfz4HGtoPc

> https://www.sogeti.com/explore/reports/design-to-disrupt-3/

> https://www.sogeti.com/explore/newsroom/how-companies-survive-by-mastering-digital-disruption-with-devops-featured-in-new-report-from-vint/


1. What are multidisciplinary and autonomous teams called at Spotify?
2. What are the characteristic fo squads as autonomous teams?
3. What are tribes at Spotify?
4. What purpose do chapters fulfill at Spotify?


### **Activity: Autonomy and Decoupling Points**

What is the level of autonomy and decoupling points in your organization?

* Are the responsibilities clear?
* Are the boundaries clear?
* What kind of overlap exists in responsibilities?
* What are the various gaps in responsibilities?


### **Topic Summary**

Autonomy is essential for DevOps teams as it supports three DASA DevOps principles:

1. End-to-End Responsibility.
2. Customer-Centric Action.
3. Cross-Functional Autonomous Teams.

In a DevOps environment, autonomy is primarily achieved by structuring the teams around distinct services and products and making them independent.

Organizations can determine the autonomy of teams using the three-step design criteria:

* Customer.
* Technology Stack.
* Knowledge.

The three primary aspects of intrinsic motivation are:

1. Autonomy.
2. Mastery.
3. Purpose.

A decoupling point defines the point within the technology stack where the responsibility is transferred between the Business System team and the Platform team.


---

## Topic 3 - DevOps at Scale

### **The First Rule of Scaling**

The first rule of scaling is **"Don't Scale"**.

A larger team (or organization) takes a long time for its work to flow through the system. In other words, the work takes a long time to produce the desired value for the customer.

Lean and Agile, the practices that DevOps support, also aim at improving workflow by reducing batch size, avoiding huge amounts of work, and employing small teams with small work items. However, under certain conditions, scaling becomes necessary for the business.


### **Why is scaling inevitable?**

Scaling becomes inevitable or unavoidable for organizations as they need to often deal with complex dynamics.

Examples of Complex Dynamics:

* Turbulent markets and changing customers demands.
* Complex products and dependencies between products, systems, and teams.
* Formal and informal social structures and communication lines.
* Multi-vendor or cloud landscapes.
* Different combinations of skills, attitudes, and behaviors.
* Compliance and regulatory influences.

Some of the most popular ways or strategies that they can use to deal with complexity include:

* Experimentation.
* Constraints enablement.
* Continuous adoption of emergent practices.

To increase the effectiveness of the DevOps transformation, organizations are also practicing the following ways:

* Look for guidance, connect to learn from each other, and seek industry learning.
* Apply principles and practices from several scaling frameworks.

The best approach to deal with scaling issues is to utilize the **Cynefin** framework (complex domain). A Cynefin framework is a problem-solving tool to analyze situations more accurately and respond appropriately based on five "domains" defined by cause-and-effect relationships. These domains are *Complex, Complicated, Disorder, Chaotic** and **Obvious**.


### **Scaling Models and Frameworks**

Several frameworks or models are available that an organization can use to deal with the complexity associated with DevOps transformation. Some of the most popular scaling frameworks include:

* Nexus.
* Less.
* Spotify.
* SAFe.

These frameworks, more or less, follow the same principles of mitigating scaling. They differ in their approach, scope, and depth of guidance. All of the frameworks have not incorporated DevOps principles and practices explicitly. However, these do not exclude DevOps as well.


### **Principles of Mitigating Scaling**

You can mitigate scaling utilizing any of the several scaling frameworks, models, or practices. These frameworks share some common characteristics or principles:

* **Ensure alignment between teams**: joint events like planning or review, cadence, direct communication.

* **Create common goals and practices**: share practices and tools where desired.

* **Organize for optimal value delivery**: value streams, value measurements.

* **Maximize transparency**: visual management.

* **Facilitate leadership**: be a servant leader.


### **Considerations for Scaling**

Organizations should consider the following aspects when dealing with scaling (or Agility at scale):

* Create only one Product Backlog for one product regardless of the number of teams working on it.

* Segregate work between multiple self-directed, cross-functional teams.

* Ensure to keep the user stories independent in the Product Backlog to the maximum extent.

* Do not force different teams working on different products to have a goal Definition of done (DoD).

* Ensure compatibility between the various DoDs so that on combining their output, a potential releasable Increment will be produced.


### **Topic Summary**

The first rule of scaling is "Don't Scale".

Scaling becomes inevitable or unavoidable for organizations as they need to often deal with complex dynamics.

Several frameworks or models are available that an organization can use to deal with complexity associated with DevOps transformation.

Some of the standard characteristics or principles of mitigating scaling are:

* Ensure alignment between teams.
* Create common goals and practices.
* Organize for optimal value delivery.
* Maximize transparency.
* Facilitate leadership.


---

## Case Study - Easy Journey Airways - Exercise 4

**Adopting the Product-Focused Approach**

EJ Airways' internal IT department started to work the Agile way a few years ago. Currently, they are facing several issues, such as:

* Huge backlog.
* Low velocity.
* Many daily and weekly meetings between the teams.
* Low level of employee satisfaction.

Management is thinking of switching from an activity-focused approach to a product-focused approach and is expecting you to perform the following analysis:

* What activities are required to make this switch?
* What are the prerequisites?
* What impediments do you expect?
* Indicate each pint as organizational or technical.

Process-throughput related issues are a good start to create a sense of urgency. A Value Stream Map will provide insight. Can you convert a prerequisite into an activity or impediment?


---

## Module Summary

In this module, I have learned:

* ...
* ...
* ...

