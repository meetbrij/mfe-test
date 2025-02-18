Demo URL:
https://d2hxa7791oqyti.cloudfront.net


### What is MFE?

Micro frontends are an architectural approach where a web application's frontend is broken down into smaller, independent, and loosely coupled modules, similar to the microservices approach in the backend. Each module can be developed, tested, and deployed independently, often by different teams, and then composed together to form a cohesive user experience.

Key Concepts of Micro Frontends:

1. **Independent Deployment** – Each micro frontend can be deployed separately without affecting others.
2. **Technology Agnostic** – Different micro frontends can use different frameworks (e.g., React, Angular, Vue).
3. **Encapsulation** – Each micro frontend owns its code, styles, and dependencies to avoid conflicts.
4. **Team Autonomy** – Different teams can work on different micro frontends, improving scalability.
5. **Composable UI** – A shell or container application assembles the micro frontends dynamically.

# Microfrontends using React and Vue
Microfrontends are used to divide a large app into a series of smaller apps. This provides a set of unique benefits to any frontend:

- Using micro frontends we divide a large monolithic app into multiple smaller apps. Each smaller app is responsible for a distinct feature of the product.
- Multiple engineering team can own a specific feature of the app and can work in isolation - such as product list, shopping cart, payment integration. Thus allowing each of your engineering teams to work independently
- Each smaller app is easier to understand and make changes to. It also enables us to use a different set of libraries for each sub-app - bring the best tool for the job!
- Container MFE app is responsible for loading the other micro frontends and deciding when and where to show the different MFE’s of the app
- Integration is about how and when does the container get access to the source code of different MFE
- Deploy each portion separately - limit the chance of interrupting your users
