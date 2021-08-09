# Todo:
Too much deep for project management, BA and SA, not there yet, already bored, pinned for later.

https://www.altexsoft.com/blog/business/technical-documentation-in-software-development-types-best-practices-and-tools/
https://blog.prototypr.io/software-documentation-types-and-best-practices-1726ca595c7f
https://gbksoft.com/blog/types-of-software-development-documentation/
https://www.toptal.com/freelance/why-design-documents-matter
https://www.geeksforgeeks.org/different-documentation-manuals-in-software-engineering/
https://forums.asp.net/t/1960960.aspx?What+are+the+Documents+involved+in+SDLC+from+start+to+end+
https://www.includehelp.com/basics/different-types-of-documentation-manuals-in-software-engineering.aspx
https://www.sdlcforms.com/UnderstandingSDLC.html

VVI

https://www.guru99.com/brs-vs-srs-the-myth-busted.html
https://www.geeksforgeeks.org/difference-between-brd-and-srs/
https://blog.qatestlab.com/2015/12/31/srs-frs-brs/
https://www.javatpoint.com/brs-vs-srs

https://www.learntek.org/blog/sdlc-phases/
https://www.softwaretestinghelp.com/software-development-life-cycle-sdlc/
https://www.learntek.org/blog/sdlc-phases/
https://www.softwaretestinghelp.com/software-development-life-cycle-sdlc/
https://www.includehelp.com/basics/different-types-of-documentation-manuals-in-software-engineering.aspx


# Specification Documents like -
They outline “how” the software will be created,  System Architect ideally, BA/SA if not

SRS - System Requirement Specifications
FRS - Functional Requirement Specifications
BRS - Business Requirement Specification
CRS- Compatibility Requirements Specifications
PRS - Performance Requirements Specifications
RRS- Reliability Requirements Specifications
CRS-Configurations Requirements Specification

Requirement Documents like -
BRD - Business Requirement Document
SRD - System Requirement Document

# Requirement Documents like -
Business Analyst 

They outline "what" the software must do

BRD - Business Requirement Document
SRD - System Requirement Document

# VVI  SDLC & Testing

https://www.youtube.com/watch?v=G-6qDY8UltU
https://www.youtube.com/watch?v=HylDB3bN6hQ
https://www.youtube.com/watch?v=EZGDyFPHFMw&t=123s
https://www.youtube.com/watch?v=DRDD7UWX2y4
* Bug lifecycle


Different type of testing

# SDLC basic flow
- Phase 1: Formation(Project initiation) 
    - Team : Project manager
    - Goal : 
        - Project roadmap(Rough order of magnitude) [Sort of a todo list]
        - Prject management plan charter
- Phase 2: Requirement gathering -> 
    - Team : 
        - Project manager(The goto guy),
        - Business analyst(To help understand debit/credit/leger in banking context/domain expert),
        - Architect(Technical feasibility)
        - Test Lead
        - stakeholders, users
    - Goal
        - Functional Requirement
        - Technical Requirement
        - Requirement review and approval
        - *SOW - Statement of work*
    - Documents
        - Formal specification
        - Context diagram
        - Mind map
        - Focus group
        - Inteview/Questioneere
        - Data flow diagram
        - BRD - Business Requirement Document
        - SRD - System Requirement Document
        - SOW - Statement of work
        - SRS - System Requirement Specifications
        - FRS - Functional Requirement Specifications
        - BRS - Business Requirement Specification
        - CRS- Compatibility Requirements Specifications
        - PRS - Performance Requirements Specifications
        - RRS- Reliability Requirements Specifications
        - CRS-Configurations Requirements Specification

- Phase 3: Design
    - Team : Architect, System analyst, UX lead, Team leads
    - Goal : 
        - System design document
            - Scalabiity
            - Security
        - HLD
            - Component diagram
            - Deployment diagram
        - LLD
            - Use case diagram
            - Activity diagram
            - Flow chart
            - ER diagram
            - Class diagram
            - Sequence diagram
            - State diagram
            - Data fow diagram
- Phase 4: Implementation
    - Team : Development team
    - Goal
        - Coding
        - Code review
        - Unit testing (LLD validation/verification) (example - one API)
        - Integration (HLD validation/verification)(example - one feature, multiple API, but one user)
- Phase 5: Testing
    - Team : Testing team
    - Goal : 
        - System testing (System design document vaidation,verification, scalabiity, security) (example - load test on one feature, but multiple user)
        - UAT/Acceptance testing(BRS,BRD validation and verification)
    - Documentation
        - Test plan
        - Test summary
        - Testing related documentation
        - Bug lifecycle, bug management
        - Cross referal listing
        - Source code listing
        - UAT documnets
- Phase 6 : Deployment
    - Team : Devops, Sysadmin
    - Goal : 
        - Going live
        - Prepare infra
    - Documentation
        - User manual
        - Change management
- Phase 7: Run and Maintain
    - Team : Maintainance team

*I am a big fan of V-shape approach as a developer, reminds me of stack push pop, very mathematical, theorical and practical looking concept*