# Application requirements
Date: `2023-05-23`
## Status
Accepted
## Context
Business requirements:

> 1. Users should be able to track selected market actions.
> 2. The application should provide an API for retrieving data from a chosen period.
> 3. Users should receive notifications on their phone or via email.
> 4. There should be an option for payment for API access and phone or email notifications.

Functional requirements:

> 1. Chart display: The application should have a separate panel to display a chart based on data retrieved from an external API that provides stock market indicators.
> 2. User registration: Users should be able to create an account in the application.
> 3. Account personalization: Logged-in users should have the ability to personalize their account, such as setting notification preferences.
> 4. Tracking market actions: Users should be able to add selected actions to their watchlist.
> 5. Forum: The application should provide a forum where registered users can create posts and comment on existing entries.
> 6. Live chat: Users should have the ability to communicate with each other through a live chat feature.
> 7. Notification system: The application should send notifications (via phone or email) to users about relevant information, such as changes in their tracked actions.
> 8. Payment options: The application should allow users to make payments for API access or other additional features.

## Decisions
> 1. Framework: The application will be developed using the Django framework.
> 2. API: Django REST Framework will be utilized to implement the API.
> 3. Payment System: Integration with an external payment system is required.
> 4. Notifications: Users will receive notifications on their phones via SMS and via email through an external SMTP server.
> 5. Live Chat: Django Channels will be utilized to provide live chat functionality.
> 6. External API Integration: The application will be integrated with an external API that provides stock market data and indicators.
> 7. Charting: Chart.js will be used to visualize the stock market data and indicators on charts.

## Consequences
> By choosing the Django framework, the application will benefit from its robust features, including built-in authentication,
> database management, and request handling. 

## Keywords
- business requirements
- functional requirements
- requirements