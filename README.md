# Title: Adopting Microservice Architecture for Budget Management System

## Context

What is the issue that we're seeing that is motivating this decision or change?

Many organizations are turning to microservices architecture by breaking down complex applications into smaller, more manageable services. In that case, we are not using a microservices architecture. So the number of users increment can lead to slow and lag servers. There is also an issue with the third-party payment system. We need to take care of those related servers so that users will find it much easier to use.


## Decision

What is the solution that we're proposing and/or doing?

We will design the budget management application using a microservices architecture. Each functional component of the application will be implemented as a separate microservice, responsible for specific aspect of the budget management process, such as user authentication,transaction tracking, budget planning, and reporting.

## Rationale

Why do we choose this solution?

With the increase in demand, we face a diversity of problems, including network jams during peak financial seasons. In such cases, using monolithic architecture will cause all the systems confined within this application to break down at once. This will further cause security risk. Additionally, integrating a third party payment system will make the system complex and code managing more complicated.


## Consequences

Pros – What becomes easier? 
     
- Pros

  * With microservices we are able to deal with increase in demand.
  * It enables the increase in overall performance and efficiency.
  * Able to perform modular maintenance. Meaning, even if a part of the system breaks down, operating team will be able to fix it without casuing harm to different part of the       system. 
  * Different teams responsible for different parts of the system will be able to operate the system with their preferred style of programming.

Cons – What becomes more difficult?

- Cons

  * It is difficult to keep all the systems consistent at the same time.
  * Development team  management becomes more difficult and cost of labor will increase.
  * Moreover the additional expense for buying new infrastructures will be added to the cost.



## Sample code

Give some sample code related to this decision.

