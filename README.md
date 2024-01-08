# Decision record template by Michael Nygard

This is the template in [Documenting architecture decisions - Michael Nygard](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions). 
https://github.com/joelparkerhenderson/architecture-decision-record/tree/main/locales/en/templates/decision-record-template-by-michael-nygard

# Title ADR-001 Decision Records

## Context

Decision records need to be created

## Decision

Out of two options presented, Michael Nygards template and a template made by Nat Pryce, Michael Nygards was chosen

## Consequences

We are left with a concise set of decisions that have enough information as opposed to a larger document with unecessary headings and such.

## Status
Accepted
------------------------------------------------------------------------------

# Title ADR-002 Personas

## Context

We have to make personas

## Decision

There are many ways to present personas such as paragraphs, pure images, pure sliders etc but the decision was made to follow the SHUDEV process. 

## Consequences

Makes it easier to link users needs such as accessibility requirements to user stories and looks cleaner when presented as it is visualised.

## Status
Accepted
------------------------------------------------------------------------------

# Title ADR-003 Architectural Styles

## Context

An architectural style must be chosen to develop this project in 

## Decision

There are a multitude of architectural styles available such as Microkernel, MVC, Event Driven, Domain Driven and layered, each with their benefits and drawbacks. The chosen style is Layered.

## Consequences

Layered architecture supports my functional and non functional requirements as it isolates aspects of the system which allows a separation of concerns. This makes it easier to upgrade and scale layers when necessary. This also makes it more SOLID. 

## Status
Accepted
------------------------------------------------------------------------------
# Title ADR-004 Wireframes

## Context

Wireframes need to be developed.

## Decision

The choice was from the following design software, Figma, Lucid Chart, Draw.io and Mockplus. I didnt choose Figma due to previous difficulties, Lucid Chart and Draw.io are great for diagrams and such which left me to use Mockplus. 

## Consequences

Mockplus provides great templates to start off with and also provides ratios for different views. It also provides useful icons and drag and dropable components. It also features interactions between components to mock sequences.

## Status
Accepted
------------------------------------------------------------------------------

# Title ADR-005 Database 

## Context

A choice between relational and non relational databases.

## Decision

A relational database is more relevant to this visa application.

## Consequences

A relational database will provide consistency in my application due to the structured data whereas a non relational one can cause issues due to how varied the data can be presented as. Relational databases also comply with ACID, this makes the data more secure and have integrity. Non relational databases are more lenient when complying with ACID which isnt a risk worth taking when dealing with sensitive data such as the data in a visa application. 

## Status
Accepted
------------------------------------------------------------------------------

# Title ADR-006 Data Model 

## Context

A choice between ERD and Class Diagram.

## Decision

A Class Diagram reflects my architectural style better, therefore Class Diagram is chosen.

## Consequences

A Class Diagram is the perfect way to demonstrate the plan to use Object Relational Mapping. 
Specifically LINQ which uses entities to manipulate database data. A class diagram can represent entities in this sense.

## Status
Accepted
------------------------------------------------------------------------------
