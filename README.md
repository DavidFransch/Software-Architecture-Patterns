# Software Architecture Patterns (LinkedIn Learning)

## Pattern Examples
- Repository
  - FindCustomers() -> Repository <-> DB
- Singleton
- Builder
- Factory

## Why software architecture patterns?
- Makes code recognizable to other developers
- Easy to find information
- Helps decision-making process

## Categories of patterns
1. Application Landscape (e.g. neighbourhood)
   - Single application to end user
   - Multiple applications behind the scenes possible
   - Types
     - Monolith
     - N-tier
     - Service-orientated
     - Microservices
     - Serverless
     - Peer-to-peer
2. Application Structure (e.g. individual houses in neighbourhood)
    - Single executable
    - Can be part of a larger application landscape
    - Types
      - Layered
      - Microkernel
      - Command Query Responsibility Segregation (CQRS)
      - Event sourcing
3. User Interface (e.g. how user gets into house)
   - Model-view-controller (MVC)
   - Model-view-presenter (MVP)
   - Model-view-viewmodel (MVVM)
