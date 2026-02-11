# App Modernization Assessment Summary

**Target Azure Services**: Azure App Service, Azure Kubernetes Service, Azure Container Apps

## Overall Statistics

**Total Applications**: 1

**Name: vets-service**
- Mandatory: 0 issues
- Potential: 2 issues
- Optional: 1 issue

> **Severity Levels Explained:**
> - **Mandatory**: The issue has to be resolved for the migration to be successful.
> - **Potential**: This issue may be blocking in some situations but not in others. These issues should be reviewed to determine whether a change is required or not.
> - **Optional**: The issue discovered is real issue fixing which could improve the app after migration, however it is not blocking.

## Applications Profile

### Name: vets-service
- **JDK Version**: 17
- **Frameworks**: Spring Boot 3.4.1, Spring Cloud 2024.0.0, Spring Data JPA
- **Languages**: Java
- **Build Tools**: Maven

**Key Findings**:
- **Potential Issues (2 locations)**:
  - <!--ruleid=config-server-001-->Spring Cloud Config Server dependency (1 location found)
  - <!--ruleid=discovery-001-->Spring Cloud Netflix Eureka service discovery (1 location found)
- **Optional Issues (1 location)**:
  - <!--ruleid=database-mysql-001-->MySQL database connection (1 location found)

## Next Steps

For comprehensive migration guidance and best practices, visit:
- [GitHub Copilot App Modernization](https://aka.ms/ghcp-appmod)

