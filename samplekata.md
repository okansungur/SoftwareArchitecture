## KATA Sample
Requirements are kept minimal.
### Requirements
Web and Mobile-Based with back-end processing and reporting and analytics that track kids when they are in  school
Location Tracking is a Hard Requirement
The ability push notifications is a hard requirement

### Technical Constraints
Lack of existing infrastructure
### Business Constraints
Initial funding for the project comes from parents and sponsorships
### Assumptions
Children should have a smartwatch or smartphone
### Identified Key Architectural Characteristics
Description is better



<p align="center">
  <img  src="https://github.com/okansungur/SoftwareArchitecture/blob/main/images/kata1.png"><br/>
   
</p>






<p align="center">
  <img  src="https://github.com/okansungur/SoftwareArchitecture/blob/main/images/kata2.png"><br/>
   
</p>


#### Overall Architecture Style Analysis
####  Microservices
…
####  Event Driven
…
####  Space-Based
…
####  Conclusion
All options have trade-offs …
####  Decision
We will use event-driven architecture. Because of poor performance criteria, we did not choose microservices. We have prepared the ADR-1 event-driven architecture.
We will keep our architectural framework agnostic.
####  Diagrams
…
####  Components 
####  IAM, Reporting and Analytics (ETL), Notification, …
####  Deployment
…
####  Cost Analysis
…
####  Evaluation, Risks, and Architecture Fitness
…
####  ADRs
…
