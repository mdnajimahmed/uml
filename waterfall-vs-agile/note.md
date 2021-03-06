## An application has three main layers 
- Interface
- Logic
- Data storage
## Project delivery methodology 
- A project is a change to the orgnization operation that should have a positive impact by removing risks or constraints on the organizations 
operations.
- Three hard constrains of a project 
    - Scope
    - Schedule
    - Cost
- Change in any of the hard constraints will cause change in the other two.

# Life Lesson
- Try not to be creative with the requirement after the requirement is signed off by the stakeholders, try to be creative implementing them. That's why BA should have amazing techical skill so that he both udnerstands the functional and non functional requirements very well. May be it won't be the worst idea to deploy architects and senior engineers in the requirement engineering process.

## Waterfall approach
- Planing
    - Collect and analyze requirements(most important phase)
- Analysis
    - Document scope an requirements
    - Wireframes and mockups
- Design
    - Document the architecture
- Implenetation
- Verification/Testing (Can be used as tag in bugs in azure devops!)
    - Functional
    - Performance
    - Security
    - Usabiity 
- Run & Maintain

Current step needs to finish first before we can begin the next step, hence the term waterfall, we can not start implementation until we finish design. 

#### Current step depends on the completion of the previous step. Hence the term waterfall.

*Important Note:*
- Used in the domain where change is not expected, the domain is well known. E.G - Medical systems, life control, military.
- Are you a startup with an idea, or a ecommerce site? Waterfall is not for you, to be ahead in the market you need to adopt change frequently and implement features that helps your end customers. So, go with agile instead of waterfall!
- Requirements are clear and won't change over time.

## Agile approach

Agile relies on 4 values - 
- Individuals and interactions over processes and tools.
- Working software over comprehensive documentation. Create documentation where it provides value.
- Customer collaboration over contract negociation.
- Responding to change.

*Agile is not a methodology but a way of thinking,Scrum and Kanban are example of the descrete methodologies that implements the agie approach* 

# Steps
- Collect requirements and document it BRS,BDS etc (study requriement engineering methods in details, BA) <https://www.youtube.com/watch?v=-psusaPKLg0> is an excellent video to understand what BA does. execute the UML process for functional diagrams.
    - identify input and output.
    - How the system behaves upon getting users inputs
    - How the users behave 
- Describe the software, Validate ideas, perform feasibiity anlysis (mockup)
- write user stories.
- convert user stories to use cases.
- execute the UML process for creating technical diagrams from the usecase diagram.
- start sprint when minimum 2-3 sprints contents are ready. Implementation and testing, Go for an MVP first and then add new feature on that!
- Release support
    - marketing
    - packeging
    - distribution

# Agile phases
- 1. Envisioning - Requirement engineering, team building, wireframing etc (Planning and analysis phase of waterfall but with less documentation)
- 2. Speculate*SPRINT - Feature based delivery plan, what feature to do in the sprint. Prepare board, user stories etc.
- 3. Explore*SPRINT - actual planned work, review developed feature, build new feature
- 4. Adapt*SPRINT- bug fix, retro, collect feedback
- 5. Close - All the features are delivered, lesson learned from the entire project.
steps 2-4 is repeating in a sprint.

# Devops
- Engineers participating together in the entire service lifecycle, development + operation + qa
- Devops is also a way of thinking (CAMS - culture,automation,measurement,sharing)
- System thinking,continuous learning an experimentation

# Devops methodologies 
- People over process over tool (define who will do the the job first, define the process around them, define the tool they will use).Adapt organization change and team building activity in this specific methodology.
- Lean management (work in small batches, amplify feedback loops, do a lot of visualization) -- this is a process optimization
- Change control - 
- CD (reduce the cycle time - time between development and deployment, reduce the lead time - getting the request from the user to the deployment)
allows more experimentation and fine tune the system. - automatic acceptance testing is a must
- IAC


# *Mapping requirements to technical description*
- Use case
    - Title : Short,descriptive use case title
    - Actor : User
    - Scenario: expains how the software works in that scenario.
    - Avoid technical term
- User story
    - Usually shorter than use case
    - As a <type of user> I want to <some goal> so that <some reason>
- Epic is a large user story? can be broken into smaller user story.
- User stories serves as discussion starter, they don't contain feature details.

# Agile keywords
- THEME
    - EPIC
        - User Story/ Backlog
            - Task
                - Subtask

- Agile is a thought process that defines values and outcomes. 
- Scrum and Kanban implements agile.
- Simplyfying agile -
    - Product owner presents user stories. BA can help writing user stories.
    - User stories are decomposed into a Backlog, each Backlog is completable in a sprint.
    - We can break Backlog into task.
    - Nice to have a dependency graph of tasks using UML.
    - Allocate buffer for bugfix and unplanned issues.
    - manage line of commitment for each sprint.
    - Team formation (Amazon 2 pizza principle - not more than 12 members)
        - A product owner
        - A BA
        - A Scrum master
        - Development team
            - Data engineer
            - API developer
            - Front end developer
            - Full stack deveopers 
        - Devops
        - QA 
    - Product owner declares requirement, leads UAT, memeber of the business team.
    - Product owner spend 60/120 minutes to explain user stories depending on 1/2 weeks sprint.
    - Rest of the team will spend 60/120 minute to finalize estimation depending on 1/2 weeks sprint.
    - Daily stanup 15 minutes
        - What did you do yesterday
        - What will you do today.
        - Do you have ny blocker.
    - Sprint review UAT : PO leads the meeting, PO collects findings and creates backlog.
    - Sprint retrospective
        - Goal is to improive the performance of the team
        - What went wel
        - What could go well
        - What can be improved
    - How does the burndown chart look like? 
    