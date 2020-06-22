# Application Credential Vending

Here's the general flow of resource creation that governs token vending for
applcations:

* Web identity roles are created in a application.
* Web identity roles are granted the correct set of policies/permissions.
* Web identity roles are exported as cloudfromation exports which can then be looked up name and used to create groups.
* Groups are then administered (by whom?!) to include the correct set of users.

Once a user is added to a group they will then be able to access sts tokens
based on the web identity role's permissions and policy.

## [Federated Access to Athena](https://docs.aws.amazon.com/athena/latest/ug/access-federation-saml.html)

Athena token acquisition ![architecture ](https://docs.aws.amazon.com/athena/latest/ug/images/athena-saml-based-federation.png)

## Specific Clients

* [athenacli](https://github.com/ucopacme/amazon-cognito-cdk-example-for-getting-aws-credentials/blob/dev/docs/athenacli.md)
* Cognos
* DbVisualiser
* Denodo
* Excel
* Quicksight
* Tableau
* Others TBD...