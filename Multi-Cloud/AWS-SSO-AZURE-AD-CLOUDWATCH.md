# Introduction

Do you Want to give your Azure Active Directory users quick access to AWS? This video explains the benefits, pricing and show how it looks in real life


 ## Business Problem Solved 

1. Using SAML to give Azure Active Directory users ability to sign-in to AWS Console and CLI (Users will be auto created, updated and deleted in AWS once done in Azure) | Helpful for BIG ENTERPRISES.

2. We need an AWS Account to monitor CloudWatch Dashboards but using AWS SSO and AWS COGNITO, we made AWS SSO Application users to see CloudWatch Dashboards WITHOUT ANY AWS ACCOUNT.


 ## Architecture Diagram 

![](https://raw.githubusercontent.com/Ananyojha/spare-images/f13100a39d1874fa5eabb33fd8a287dbe1c5178d/aws-sso.jpg)

 ## Benefits


 ## Pricing 

### FREE !! 
[CLOUDWATCH PRICING](https://aws.amazon.com/cloudwatch/pricing/)

[EC2 PRICING](https://aws.amazon.com/ec2/pricing/)

[Azure AD PRICING](https://azure.microsoft.com/en-in/pricing/details/active-directory/)

 ## Tech Used 


**Concepts** - 

### Aws --

- AWS Single Sign-On
Centrally manage access to multiple AWS accounts or applications
You can create user identities directly in AWS SSO, or you can bring them from your Microsoft Active Directory or a standards-based identity provider, such as Okta Universal Directory or Azure AD. With AWS SSO, you get a unified administration experience to define, customize, and assign fine-grained access



**SAML** : SAML is an acronym used to describe the Security Assertion Markup Language (SAML). Its primary role in online security is that it enables you to access multiple web applications using one set of login credentials

**Single sign-on** : (SSO) is a technology which combines several different application login screens into one. With SSO, a user only has to enter their login credentials (username, password, etc.) one time on a single page to access all of their SaaS applications

**SCIM** : System for Cross-domain Identity Management is a standard for automating the exchange of user identity information between identity domains, or IT systems
generally used with SAML SSO 

