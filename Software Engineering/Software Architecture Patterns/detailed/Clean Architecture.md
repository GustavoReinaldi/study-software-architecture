It is one of the most **widely** used [[Architecture Patterns]], and its concepts can be easily found in others [[Architecture Patterns]] like [[Hexagonal Architecture (Ports and Adapters)]] and [[Layered Architecture (n-Tier Architecture)]]. 

This architecture was designed to **separate concerns and dependencies** of the business core logic from outer layers, such as user interfaces. This pattern **focuses** on creating solutions where the **core business logic is completely detached** and independent from other parts of the software. This results in greater flexibility, maintainability, and testability in the long run.

### Main principles
- **Framework independence** - Your core logic have to be totally independent of external tools like Frameworks.
- **Layered Design** - Design your system with layers. Each layer has its own responsibility.
- **Dependency Rules** - Outer Layers depends of inner Layers, but inner layers didn't depends of outer layers.
- **Testability** - The core business logic have to be testable in isolation without depends of something. 

### Typical layers in Clean Architecture
1. **Entities**: Core business rules and objects that represent the domain.
2. **Use Cases**: Application-specific business logic coordinating workflows.
3. **Interface Adapters**: Translate data between the core logic and external systems like UI or databases.
4. **Frameworks and Drivers**: External tools and systems, such as databases, web frameworks, or APIs.

### Advantage
Using this patterns you'll be able to switch frameworks, user interfaces, adapters, swap databases, etc., without impacts in your core Business Logic.