# Title

## Context

What is the issue that we're seeing that is motivating this decision or change?

## Decision

What is the solution that we're proposing and/or doing?

## Rationale

Why do we choose this solution?

With the increase in demand, we face a diversity of problems, including network jams during peak financial seasons. In such cases, using monolithic architecture will cause all the systems confined within this application to break down at once. This will further cause security risk. Additionally, integrating a third party payment system will make the system complex and code managing more complicated.


## Consequences

Pros – What becomes easier? Cons – What becomes more difficult?

Markup: *Pros

*With microservices we are able to deal with increase in demand without impact on other parts of the system.
*It enables the increase in overall performance and efficiency.
*Able to perform modular maintenance. Meaning, even if a part of the system breaks down, operating team will be able to fix it without casuing harm to different part of the       system. 
*Different teams responsible for different parts of the system will be able to operate the system with their preffered style of programming.

Cons

*It is difficult to keep all the systems consistent at the same time.
*Development team  management becomes more difficult and cost of labor will increase.
*Moreover the additional expense for buying new infrastructures will be added to the cost.



## Sample code

Give some sample code related to this decision.

