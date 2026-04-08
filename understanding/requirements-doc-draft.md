# Architectural Requirements

## Business Goals

## Constraints

EX:

| Constraint                                         | Context                                                                |
| -------------------------------------------------- | ---------------------------------------------------------------------- |
| [Technical] Must be deployed on AWS infrastructure | Our DevOps team only provides support and monitoring for AWS services. |

## Quality Attributes

EX:

| Quality Attribute | Scenario                                                                                                      | Priority |
| ----------------- | ------------------------------------------------------------------------------------------------------------- | -------- |
| Performance       | A user on a mobile device with a 4G connection can load the app in 5 seconds or less.                         | High     |
| Scalability       | The codebase should be modularized to allow and increasing number of frontend developers to work in parallel. | High     |

## Influential Functional Requirements

EX:

- Customers can browse the app without being authenticated.
- Customers can add food items to a shopping cart (with or without authentication).
