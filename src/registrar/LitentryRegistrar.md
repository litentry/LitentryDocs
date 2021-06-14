# Registrar Background

Decentralised Identity (DID) consists of a triangle of Trust. The atester (registrar), the credential holder and the verifier. The atester (verifies/atests/judges) that the credentials for the identity are correct. Credentials could be email address, twitter account or any other data that could be used as identity credentials.
The credential holder is the person, business or IOT device that controls the credentials.
The verifier is the entity to whom the credentials are being presented.

As an example if you are wanting to use a dapp or service and they would like to verify that you are identified by your email address and/or twitter account. They could ask for these credentials. As a user wanting to use this service you could choose to hand these credentials over to them. Because the credentials are atested by a trusted attester the verify will accept the presented credentials and allow you to use the Dapp or service.

Litentry is a registrar in polkadot parlance (an atester in self sovereign identity parlance). This means that Litentry to atest to (issue a judgement) of the validity of your email address, twitter account and your element account. This section covers How to verify your identity with Litentry and the implementation details of Litentry.

## Litentry and Polkadot

Polkadot provides a service that allows participants to add personal information such as email addresses and twitter accounts to their on-chain accounts. The user can then ask for verification of this information by a registrar. Litentry is a registrar. A user can request a registrar to make a judgment on their claims. The user can select a fee that they are willing to pay. Registars are accepted via submitting proposals to the democracy process in Polkadot.

Litentry has been accepted as a Registrar for Kusama.
