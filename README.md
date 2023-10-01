# API Design Worksheets
## I. Define Business Objectives
### The Problem
Briefly define the problem and how it affects customers and the business
### The Impact
Define what success looks like for your API. What will the world be like after you've released your new API
### The User Stories
List several key user stories for your API with the following template

> As a [**user type**], I want [**action**] so that [**outcome**].
1.
2.
3.
4.
5. 

### Technology Architecture
Describe the technology architecture you've selected, along with the reasons behind your decision. You may wish to include charts or graphs showing the pros and cons of paradigms you've considered.
Here's an optional example table:

Table A-1. Technology architecture
| Pattern, paradigm, or protocol considered | Pros | Cons | Selected? |
| ---- | ---- | ---- | ---- |
|  |  |  |  |

## II. API Specification Template
### Title
### Authors
### Problem
### Solution
### Implementation
Give a high-level description of the implementation plan. You may wish to use additional tables or diagrams to describe your plan.
### Authentication
Describe how developers will gain access to the API
### Other Things We Considered
If you considered any other API paradigms, architectures, authentication strategies, protocols, etc., briefly mention what you considered 
### Inputs, Outputs (REST, RPC)
If you're designing a REST or RPC API, describe the endpoints, inputs, and outputs. You may wish to add columns or use a different table format to describe the requests and responses

Table A-2.Table_name
| URI | Inputs | Outputs |
| --- | --- | --- |
||||

### Events, Payloads (Event-Driven APIs)
If you're desiging an event-driven API, describe the events and their payloads. You may wish to add columns for additional information, such as OAuth scope

Table A-3.Table_name
| Events | Payload |
|---|---|
| | |

### Errors
Table A-4.Technology architecture
| HTTP status code | Error code | Verbose error | Description |
|---|---|---|---|
|||||
### Feedback Plan
Describe how you plan to gather feedback on your API design, including whether you plan to release to beta testers
### API Implemtation Checklist:
- [] Define specific developer problem to solve Write internal API specification
- [] Get internal feedback on API specification
- [] Build API
	- [] Authentication
	- [] Authorization
	- [] Error handling
	- [] Rate-limiting
	- [] Pagination
	- [] Monitoring and logging
- [] Write documentation
- [] Run beta test with partners on new API
- [] Gather feedback from beta partners and make changes
Create communication plan to norify developers of changes
- [] Release API changes
