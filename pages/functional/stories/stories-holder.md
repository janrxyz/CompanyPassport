---
layout: page
title: User Stories - Holder
hero_height: is-fullwidth
---

| User Story                                                                                                                                   |
| -------------------------------------------------------------------------------------------------------------------------------------------- |
| [H.1 Receive Attestation](#h1-receive-attestation)                                                                                           |
| [H.2 Request Attestation](#h2-request-attestation)                                                                                           |
| [H.3 View Attestation in Organizational Wallet](#h3-view-attestation-in-organizational-wallet)                                               |
| [H.4 Renew Attestion in Organizational Wallet](#h4-renew-attestion-in-organizational-wallet)                                                 |
| [H.5 Delete Attestation in Organizational Wallet](#h5-delete-attestation-in-organizational-wallet)                                           |
| [H.6 Auto Renew Attestion in Organizational Wallet](#h6-auto-renew-attestion-in-organizational-wallet)                                       |
| [H.7 Present Attestations to Relying Party](#h7-present-attestations-to-relying-party)                                                       |
| [H.8 Configure Trust Frameworks](#h8-configure-trust-frameworks)                                                                             |
| [H.9 Verify Trust Framework of Attenstation Provider or Relying Party](#h9-verify-trust-framework-of-attenstation-provider-or-relying-party) |


## User Stories

### H.1 Receive Attestation

As an authorized representative I want to receive an Attestation from an Attestion Provider in the Organizational Wallet, so that the Legal Entity and any of it's representatives can use the Attestation in the future.

### H.2 Request Attestation

As an Authorized Representative I want to request issuance of an Attestion to the Organizational Wallet from an Attestation Provider.

### H.3 View Attestation in Organizational Wallet

As an Authorized Representative I want to view the Attributes of an Attestation stored in the Organizational Wallet, so that I can check certain details of the Attestation such as the issuance date, the expiration date, the revocation state, and other attributes.

### H.4 Renew Attestion in Organizational Wallet

As an Authorized Representative I want to renew an Attestation stored in the Organizational Wallet, so that Attestations that are revoked, expired, or otherwise invalid can be renewed.

### H.5 Delete Attestation in Organizational Wallet

As an Authorized Representative I want to be able to delete an Attestation stored in the Organizational Wallet, so that Attestations that are no longer needed can be deleted.

### H.6 Auto Renew Attestion in Organizational Wallet

As an Organizational Wallet I want to auto-renew an Attestation stored in the Organizationl Wallet that are configured to auto-renew and about to expire, so that Attestations in the Organizational Wallet are valid when they need to be used.

### H.7 Present Attestations to Relying Party

As an Authorized Representative I want to present one or more Attestions stored in the Organizational Wallet in response to a request from a Relying Party to present Attestions, so that the Relying Party can verify certain Attributes about the Legal Entity or it's Authorized Representatives.

### H.8 Configure Trust Frameworks

As an Authorized Representative I want to configure a list of trusted Trust Frameworks within the Organizational Wallet, so that an Attestations issued by an Attestation Provider, or a presentation request from a Relying Party can be verified against the trusted Trust Frameworks. 

### H.9 Verify Trust Framework of Attenstation Provider or Relying Party

As an Authorized Representative I want to verify the Trust Framework an Attestation Provider or Relying Party the Legal Entity interacts with through the Organizational Wallet, so that the Legal Entity can be sure it interacts with ...? 

## Use Case Specific User Stories

This section lists user stories that are specific to the use case of founding a new "Besloten Vennootschap" (BV), a Dutch private limited liability company (Ltd.). Most of these user stories can be handled by the general user stories defined above, but are to show the general requirements cover the use case specific requirements as well.

1. As an Authorized Representative I want to receive an OprichtingsAkte Attestation from a notary on behalf of the Legal Entity in the Organizational Wallet, so that the Legal Entity and any of it's representatives can use the OprichtingsAkte Attestation in the future.
2. As an Authorized Representative I want to present an OprichtingsAkte Attestation in the Organizational Wallet on behalf of the Legal Entity to the Dutch Chamber of Commerce (KvK), so that the Dutch Chamber of Commerce can verify that the Legal Entity ...?
4. As an Authorized Representative I want to receive an Uitreksel Attestation from the Dutch Chamber of Commerce (KvK) on behalf of the Legal Entity in the Organizational Wallet, so that the Legal Entity and any of it's representatives can use the Uitreksel Attestation in the future.
5. As an Authorized Representative I want to receive an RSIN Attestation from the Dutch Chamber of Commerce (KvK) on behalf of the Legal Entity in the Organizational Wallet, so that the Legal Entity and any of it's representatives can use the Uitreksel Attestation in the future.
  - RSIN attributes may also be part of Uitreksel Attestation
6. As an Authorized Representative I want to present an Uitreksel Attestation in the Organizational Wallet on behalf of the Legal Entity to the Dutch Tax Authority, so that the Dutch Tax Authority can verify that the Legal Entity is registered at the Dutch Chamber of Commerce (KvK).
6. As an Authorized Representative I want to receive an "VAT ID" Attestation from the Dutch Tax Authority (Belastingdienst) on behalf of the Legal Entity in the Organizational Wallet, so that the Legal Entity and any of it's representatives can use the "VAT ID" (Belastingdienst) Attestation in the future.
7. As an Authorized Representative I want to present an Uitreksel Attestation in the Organizational Wallet on behalf of the Legal Entity to an accredited Dutch bank, so that the accredited dutch bank can verify that the Legal Entity is registered at the Dutch Chamber of Commerce (KvK).
8. As an Authorized Representative I want to receive an "Bank Account" Attestation from a accredited Dutch bank on behalf of the Legal Entity in the Organizational Wallet, so that the Legal Entity and any of it's representatives can use the "Bank Account" Attestation in the future.
