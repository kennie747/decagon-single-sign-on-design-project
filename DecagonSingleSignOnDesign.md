# Decagon Single SingOn (SSO) Network Design

Please go through the project [README](README.md) for the full information about this project.

The Decagon single sign-on (SSO) network allows Decagon customers to add authentication and authorization functions to their applications with just a few clicks.

Users can configure callback URL on the Decagon SSO dashboard and configure the login/registration methods and 2FA.

## The Decagon SSO Features:

1. Customers can sign up on the SSO network to configure their applications.
2. Each customer application is entitled to a user management dashboard to see all its users.
3. The customer can configure the supported authentication method. We can support basic auth (username/email & password) and OAuth 2. This is the method their users would use to login/sign up when they click on sign up or login on their website.
4. The customer can create different customer groups per application and add permissions to each group.

## Entities within the Decagon SSO Network 

1. Decagon SSO Customer
2. Customer Application
3. Application User
4. Authentication Method
5. Application User Group
6. User Group Permissions

The Decagon SSO Block Diagram is shown below:

![The Decagon SSO Block Diagram](images/DecagonSSOBlockDiagram.jpg)

The Decagon SSO Hierarchical Data Model is shown below:

![The Decagon SSO Hierarchical Diagram](images/DecagonSSOHierarchicalDiagram.jpg)

The Decagon SSO Use Case Diagram is shown below:

![The Decagon SSO Use Case Diagram](images/DecagonSSOUseCaseDiagram.jpg)

The Decagon SSO Entity Relationship Diagram is shown below:

![The Decagon SSO Entity Relationship Diagram](images/DecagonSSOEntityRelationshipDiagram.jpg)

The Decagon SSO Relational Model is shown below:

![The Decagon SSO Entity Relationship Diagram](images/DecagonSSORelationalModel.jpg)

