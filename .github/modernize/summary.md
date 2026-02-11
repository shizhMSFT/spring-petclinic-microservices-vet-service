# App Modernization Assessment Summary

**Target Azure Services**: Azure App Service, Azure Kubernetes Service, Azure Container Apps

## Overall Statistics

**Total Applications**: 1

**Name: Spring PetClinic Vets Service**
- Mandatory: 2 issues
- Potential: 2 issues
- Optional: 1 issues

> **Severity Levels Explained:**
> - **Mandatory**: The issue has to be resolved for the migration to be successful.
> - **Potential**: This issue may be blocking in some situations but not in others. These issues should be reviewed to determine whether a change is required or not.
> - **Optional**: The issue discovered is real issue fixing which could improve the app after migration, however it is not blocking.

## Applications Profile

### Name: Spring PetClinic Vets Service
- **JDK Version**: 17
- **Frameworks**: Spring Boot 3.4.1, Spring Cloud 2024.0.0, Spring Data JPA, Spring Cloud Config, Spring Cloud Netflix Eureka
- **Languages**: Java
- **Build Tools**: Maven

**Key Findings**:
- **Mandatory Issues (3 locations)**:
  - <!--ruleid=AZURE-001-->Migrate Spring Cloud Config to Azure App Configuration (1 location found)
  - <!--ruleid=AZURE-002-->Migrate Netflix Eureka to Azure Service Discovery (2 locations found)
- **Potential Issues (2 locations)**:
  - <!--ruleid=AZURE-004-->Consider Azure Cache for Redis for Distributed Caching (1 location found)
  - <!--ruleid=AZURE-003-->Configure Azure MySQL Connection (1 location found)
- **Optional Issues (1 locations)**:
  - <!--ruleid=AZURE-005-->Use Azure Monitor and Application Insights (1 location found)

## Next Steps

For comprehensive migration guidance and best practices, visit:
- [GitHub Copilot App Modernization](https://aka.ms/ghcp-appmod)

