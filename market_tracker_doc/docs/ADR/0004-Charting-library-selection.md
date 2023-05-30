# Charting library selection
Date: `2023-05-25`
## Status
Accepted
## Context
> As the application requires data visualization in the form of charts, it is necessary to select a suitable frontend 
> library that will meet the following requirements:

Business requirements:

>The selected library:
> 1. Should be easy to integrate with the existing application system.
> 2. Should support a wide range of ways to present data
> 3. Should be stable and reliable to ensure uninterrupted application functionality.
> 4. Should have good performance characteristics


Functional requirements:
> The library:
> 1. Should be easy to integrate with Django framework.
> 2. Should offer real-time chart updates, for example, in response to data changes or user actions.
> 3. Should support axis labels, chart titles, and other textual elements that facilitate data interpretation.
> 4. Should be lightweight and optimized for performance to allow for fast chart rendering.
> 5. Should support a wide range of chart types

## Decision
> The library that fulfills the project requirements is Chart.js (https://www.chartjs.org). It meets all the functional
> and business requirements and offers a wide range of visualization charts that are perfectly suited for this project.

## Consequences
> 1. Rich Visualization Capabilities: Chart.js provides a wide range of visualization options.
> 2. Ease of Integration: Chart.js is designed to be easy to integrate with any of website framework.
> 3. Customization Options: Chart.js offers extensive customization options.
> 4. Active Community and Support: benefits from a thriving community, providing abundant resources, tutorials, and support for users. 

## Keywords
- visualization
- chart library
- charting library
- chart