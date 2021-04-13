---
description: by Matthew Skelton and Manuel Pais
---

# Team Topologies

## Pitch

Effective software teams are essential for any organization to deliver value continuously and sustainably. 

But how do you build the best team organization for your specific goals, culture, and needs? 

Team Topologies is a practical, step-by-step, adaptive model for organizational design and team interaction based on four fundamental team types and three team interaction patterns. 

It is a model that treats teams as the fundamental means of delivery, where team structures and communication pathways are able to evolve with technological and organizational maturity. 

In Team Topologies, IT consultants Matthew Skelton and Manuel Pais share secrets of successful team patterns and interactions to help readers choose and evolve the right team patterns for their organization, making sure to keep the software healthy and optimize value streams. 

Team Topologies is a major step forward in organizational design for software, presenting a well-defined way for teams to interact and interrelate that helps make the resulting software architecture clearer and more sustainable, turning inter-team problems into valuable signals for the self-steering organization.

![](../../../.gitbook/assets/image%20%28608%29.png)

## Book notes

### Preface

* A functional book
* Part I - explores Conway’s law
  * The way organizational interrelationships constrain the design of systems we build
  * And how we can use this tendency to our advantage
* Part II - set of static team patterns
  * Have been proven in the industry and the implications of choosing one pattern over another 
  * with Conway’s law and organizational context in mind
* Part III - ways to evolve the organization design 
  * To provide powerful capabilities for innovation and rapid delivery i
  * How to use the Team Topologies approach to create a sensing organization that responds to the market and user demands,
  * And accounts for the implications this has for hiring and skills

![](../../../.gitbook/assets/image%20%28610%29.png)

### Part 1 - Team As The Means of Delivery

* The Problem with Org Charts
  * Must shift our thinking from treating teams as collections of interchangeable individuals that will succeed as long as they follow the “right” process and use the “right” tools
  * TO treating people and technology as a single human/computer carbon/silicon sociotechnical ecosystem
  * We need to ensure that teams are intrinsically motivated and are given a real chance of doing their best work within such a system
* Team Topologies focuses on 
  * how to set up dynamic team structures
  * interaction modes that can help teams adapt quickly to new conditions
* Org chart is always out os sync with reality

![](../../../.gitbook/assets/image%20%28612%29.png)

* By empowering teams, and treating them as fundamental building blocks
  * Individuals inside those teams move closer together to act as a team rather than just a group of people
* Explicitly agree on interaction modes with other teams
  * Expectations on behaviors become clearer and inter-team trust grows

{% hint style="info" %}
_**Team structures must match the required software architecture or risk producing unintended software**_
{% endhint %}

#### Cognitive Load and Bottlenecks

{% hint style="info" %}
_When cognitive load isn’t considered, teams are spread thin trying to cover an excessive amount of responsibilities and domains. Such a team lacks bandwidth to pursue mastery of their trade and struggles with the costs of switching contexts.”_
{% endhint %}

![](../../../.gitbook/assets/image%20%28609%29.png)

#### Conway's law

* An organization that is arranged in functional silos
  * Where teams specialize in a particular function, such as QA, DBA, or security
  * Is unlikely to ever produce software systems that are well-architected for end-to-end flow
* The Reverse Conway Maneuver
  * Accelerate: The Science of Dev Ops 
    * "Our research lends support to what is sometimes called the “inverse Conway maneuver,” which states that organizations should evolve their team and organizational structure to achieve the desired architecture. The goal is for your architecture to support the ability of teams to get their work done—from design through to deployment—without requiring high-bandwidth communication between teams."

> “Team assignments are the first draft of the architecture." - Michael Nygard

* The fundamental _**means of delivery is the team**_
  * The system architecture needs to 
    * Enable 
    * Encourage fast flow within each team
  * In practice, this means that we can follow proven software-architecture good practices:
    * Loose coupling—components do not hold strong dependencies on other components
    * High cohesion—components have clearly bounded responsibilities, and their internal elements are strongly related 
    * _Clear and appropriate version compatibility_
    * Clear and appropriate cross-team testing

**Organization Design Requires Technical Expertise**

> “if we have managers deciding . . . which services will be built, by which teams, we implicitly have managers deciding on the system architecture.” - Ruth Malan

* How much awareness does the HR department have about software systems? 
* Does the group of department leaders deciding how to allocate budget across teams know of the likely effects of their choices on the viability of the software architecture?

{% hint style="info" %}
Allan Kelly’s view of a software architect’s : 

"More than ever I believe that someone who claims to be an **Architect needs both technical and social skills**, they need to understand people and work within the social framework. They also need a remit that is broader than pure technology—they need to **have a say in organizational structures and personnel issues**, i.e. they need to be a **manager too**."
{% endhint %}

* Restrict Unnecessary Communication
  * Not all communication and collaboration is good
  * _**We need focused communication between specific teams**_
* 2 rules
  * The organization’s design limits the number of possible solutions for a given system’s architecture
  * The speed of software delivery is strongly affected by how many team dependencies the organization design instills
* _**Fast flow requires restricting communication between teams**_
  * Team collaboration is important for gray areas of development
  * Where discovery and expertise is needed to make progress

{% hint style="success" %}
“_Disbanding high-performing teams is worse than vandalism: it is corporate psychopathy._" — Allan Kelly, Project Myopia
{% endhint %}

#### Team first-thinking

* Research by Google on their own teams 
  * Who is on the team matters less than the team dynamics
  * _**When it comes to measuring performance, teams matter more than individuals**_

#### Use Small, Long-Lived Teams as the Standard

* “team” = stable grouping of five to nine people who work toward a shared goal as a unit
* > _An organization should never assign work to individuals; only to teams_
* Allowing teams to grow beyond the _**magic seven-to-nine size**_ imperils the viability of the software being built by that team \(Dunbar’s number\)
  * Trust will begin to break down
  * Unsuitable decisions might ensue
* Organizations need to maximize **trust between people on a team**
  * That means limiting the number of team members

#### Smaller Size Fosters Trust

* Anthropological research shows that the type and depth of relationship we can have with people has clear limits :
  * Around five people—limit of people with whom we can hold close personal relationships and working memory 
  * Around fifteen people—limit of people with whom we can experience deep trust
  * Around fifty people—limit of people with whom we can have mutual trust
  * Around 150 people—limit of people whose capabilities we can remember

#### The Team Owns the Software

* With small, long-lived teams in place
  * We can begin to improve the ownership of software
* Team ownership helps to provide the vital “continuity of care”
* The danger of allowing multiple teams to change the same system or subsystem 
  * No one owns the changes made or the resulting mess
* There should be no shared ownership of components, libraries, or code

#### Team Members Need a Team-First Mindset

* Put the needs of the team above their own

#### Embrace Diversity in Teams

* Find Novel and creative ways
* Produce more creative solutions

#### Reward the Whole Team not individuals

#### Good Boundaries Minimize Cognitive Load

* Organizations need to _**ensure**_ that the _**cognitive load on a team is not too high**_
* Restrict Team Responsibilities to Match Team Cognitive Load
* **Cognitive load** 
  * Characterized in 1988 
  * By psychologist John Sweller 
  * “_**the total amount of mental effort being used in the working memory.**_”
  * 3 types of cognitive load
    * **Intrinsic** —relates to aspects of the task fundamental to the problem space 
      * What is the structure of a Java class?
      * How do I create a new method?
    * **Extraneous** —relates to the environment in which the task is being done 
      * How do I deploy this component again?
      * How do I configure this service?
    * **Germane** —relates to aspects of the task that need special attention for learning or high performance 
      * How should this service interact with the ABC service?

{% hint style="info" %}
_**With a team-first approach, the team’s responsibilities are matched to the cognitive load that the team can handle**_
{% endhint %}

#### Measure the Cognitive Load Using Relative Domain Complexity

* Ask the team : 
  * “Do you feel like you’re effective and able to respond in a timely fashion to the work you are asked to do?”
* Trying to determine the cognitive load of software using simple measures such as lines of code, number of modules, classes, or methods is misguided
* When measuring cognitive load
  * what we really care about = domain complexity
  * how complex is the problem that we’re trying to solve with software? 
  * A domain = a more largely applicable concept than software size

#### 3 heuristics

1. Assign each domain to a single team
   * Instead of splitting responsibilities of a single domain to multiple teams
   * Split the domain into subdomains 
     * Then assign each new subdomain to a single team
2. A single team should be able to accommodate two to three “simple” domains”
3. A team responsible for a complex domain should not have any more domains assigned to them—not even a simple one

#### Design “Team APIs” and Facilitate Team Interactions

* Team API = an API surrounding each team
* It includes :
  * Code: runtime endpoints, libraries, clients, UI, etc. produced by the team 
  * Versioning: how the team communicates changes to its code and services 
  * Wiki and documentation: especially how-to guides for the software owned by the team 
  * Practices and principles: the team’s preferred ways of working 
  * Communication: the team’s approach to remote communication tools, such as chat tools and video conferencing 
  * Work information: what the team is working on now, what’s coming next, and overall priorities in the short to medium term 
  * Other: anything else that other teams need to use to interact with the team
* Team API should consider usability by other teams

### Part 2 - Team Topologies that Work for Flow

![](../../../.gitbook/assets/image%20%28611%29.png)

#### Stream-Aligned teams

* “stream” : the continuous flow of work aligned to a business domain or organizational capability
  * Requires clarity of purpose and responsibility
* Team aligned to a single, valuable stream of work
  * Might be 
    * A single product or service
    * A single set of features
    * A single user journey
    * or a single user persona
* Work on the full spectrum of delivery
* **Primary team type in an organization**

{% hint style="info" %}
_**Purpose of the other fundamental team topologies is to reduce the burden on the stream-aligned teams**_
{% endhint %}

**Capabilities**

* Application security
* Commercial and operational viability analysis 
* Design and architecture 
* Development and coding 
* Infrastructure and operability 
* Metrics and monitoring 
* Product management and ownership 
* Testing and quality assurance User experience \(UX\)

> critical not to assume each capability maps to an individual role in the team

* Be able, as a team, to 
  * understand and act upon the above capabilities
* Have a mix of generalists and a few specialists

**Expected Behaviors**

* Aims to produce a steady flow of feature delivery
* Correct based on feedback from the latest changes
* Uses an experimental approach to product evolution
  * Expecting to constantly learn and adapt
* Team has minimal \(ideally zero\) hand-offs of work to other teams
* Must have time and space to address code quality changes \(sometimes called “tech debt”\) to ensure that changing the code remains safe and easy to do. 
* Proactively and regularly reaches out to the supporting fundamental-topologies teams \(complicated subsystem, enabling, and platform\)
* Feel they have achieved or are in the path to achieving “autonomy, mastery, and purpose,” the three key components of engaged knowledge workers, according to Daniel Pink

#### **Enabling Teams**

* In Accelerate High-performing teams are continuously improving their capabilities in order to stay ahead
  * But how can a stream-aligned team with end-to-end ownership find the space for researching, reading about, learning, and practicing new skills?”
* Enabling team is composed of specialists in a given technical \(or product\) domain
  * They help bridge this capability gap
* Have a strongly collaborative nature
* Avoid becoming “ivory towers” of knowledge
* Increase the autonomy of stream-aligned teams by growing their capabilities 
  * With a focus on their problems first
  * Not the solutions per se
* Should not be a permanent dependency

**Expected Behaviors**

{% hint style="info" %}
_The mission of enabling teams is to help stream-aligned teams acquire missing capabilities, usually around a specific technical or product management area_
{% endhint %}

* Seeks to understand the needs of stream-aligned teams
  * Establishing regular checkpoints
  * Jointly agreeing when more collaboration is needed
* Stays ahead of the curve in keeping abreast of new approaches, tooling, and practices in their area of expertise
* Act as a proxy for external \(or internal\) services that are currently too difficult for stream-aligned teams to use directly
* Promotes learning not only inside the enabling team but across stream-aligned teams
  * Acting as a curator that facilitates appropriate knowledge sharing inside the organization

{% hint style="info" %}
_**Enabling teams do not exist to fix problems that arise from poor practices, poor prioritization choices, or poor code quality within stream-aligned teams**_
{% endhint %}


