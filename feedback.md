# Feedback

* Using README as starting point to define project, requirements, risks, stack and excluded technologies
* Installed dotnet 8 (was already installed)
* Read  https://azure.microsoft.com/en-us/pricing/details/app-service/windows/
* It read the README at end of command after agents
* Created project plan

Plan issues:
* Database-first design preventing refactoring needs as you scale
* Interface-driven provider switching (IMemoryCache → Redis, JWT → Azure AD B2C)
* Time estimates off: 6-8 weeks
* Added SQL schema not needed for stateless
* Correctly excluded in early phases:
    - **Advanced Caching (Redis)**: Postponed to Phase 2 - MVP uses IMemoryCache with interface for easy provider switching
    - **Advanced Monitoring & Alerting**: Postponed to Phase 2 - MVP includes basic Application Insights
    - **Microservices Architecture**: Postponed to Phase 3 - MVP is Enhanced Monolith with modular preparation
    - **Advanced Security Compliance**: Postponed to Phase 3 - MVP includes basic security, enterprise compliance added later
    - **Performance Optimization**: Postponed to Phase 2 - MVP focused on functionality, optimization in next phase
* Explicitly told not to but added in future phases:
    * Multi tenant
    * Blob
    * App Insights
    * SQL
    * Auth
    * Redis
    * Frontend
    * Containerization

> MAJOR ISSUES
Over Engineering and adding scope in future phases never needed. SQL first when none needed.
