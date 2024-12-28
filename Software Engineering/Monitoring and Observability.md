## Context
When we use [[Microservices Architecture]] we have to handle with some issues like: 
- Control the user's traffic, ensuring that your services are capable to support all users. For this task we use [[Load Balancers]]
- Handle all addresses of microservices from our topology. For this issue we resolve with [[BFF]] or [[API Gateways]].
- Best practices in code like: [[Clean Code]], [[Clean Architecture]], [[SOLID]], [[Unit Tests and Integration Test]], etc. 
- Constantly monitoring and observing the apps if they are **up and healthy** to ensure the best user experience. And is about this that we will talk about.

**Monitoring** is a Manual process to find possible error or instabilities on our systems by entering in **/health** URIs, follow the deployment logs, look to indexes in a Container Manager or something like this.

**Observability** is about automations that follow all of this indicators, show us in graphs or something like and alert us about some things that **threats** our systems.

