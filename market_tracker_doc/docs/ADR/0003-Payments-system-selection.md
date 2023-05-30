# Payment system selection
Date: `2023-05-25`
## Status
Accepted
## Context
> As it was mentioned in application requirements there is a need for suitable payment system, that will handle the payment
> process for API access or other additional features.

Business requirements:

> 1. Free initial integration: The payment system should offer free initial integration, allowing the setup of payment processing within the commerce platform without additional charges. For subscription-based models, the system should also allow free usage of the payment system, with the possibility of potential buyers partially covering costs in exchange for specific functionalities
> 2. Refund handling: The system should support the process of payment refunds.
> 3. Support for multiple payment methods: The system should provide support for various payment methods
> 4. Transaction security: The system should ensure a high level of transaction security

Functional requirements:

> 1. Integration with Django: The payment system should be easily integratable with the Django platform, facilitating seamless payment integration within Django applications and simplifying the integration process.
> 2. Real-time payment processing: The system should enable real-time payment processing, allowing customers to make payments without unnecessary delays.
> 3. Documentation for Django integration: The payment system should provide comprehensive documentation, including integration instructions and examples for integrating with the Django platform

## Decision
> Payment system that satisfies the project requirements: 
> https://stripe.com/en-pl
> 1. Stripe offers a payment system that is free of setup fees, monthly fees, or hidden charges. The cost associated with the payment system is fully covered by the potential buyer, in the form of a percentage of the purchase amount.
> 2. The integration documentation for Stripe can be found at: https://stripe.com/docs/payments
> 3. Stripe allows for the refund of a charge that has previously been created but not yet refunded.
> 4. Stripe provides a variety of payment options, including cards, wallets, bank debits, transfers, etc. 
> 5. Stripe is certified PCI Service Provider Level 1
> 6. According to documentation Stripe ensures real-time payment processing

## Consequences
> Choosing Stripe as the payment system for the programmed application will allow meeting the specified requirements. Stripe offers free integration, support for various payment methods, refund capabilities, transaction security, and real-time payment processing. Additionally, Stripe provides well-documented APIs, facilitating integration with the application. Selecting Stripe will ensure efficient and reliable payment processing, contributing to positive customer interactions and enhancing the overall user experience.
## Keywords
- payment
- payment system
- stripe
- stripe.com