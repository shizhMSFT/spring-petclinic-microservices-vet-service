# Upgrade Plan

## Overview
Upgrade to latest LTS versions (Java 21 and Spring Boot 3.4).

## Tasks
See `tasks.json` for detailed task breakdown.

### Task Summary
1. **001-upgrade-java-spring-boot**: Upgrade to Java 21 and Spring Boot 3.4
   - Upgrade JDK to version 21 (current LTS)
   - Upgrade Spring Boot to 3.4
   - Upgrade Spring Framework to 6.x
   - Migrate javax.* to jakarta.* namespace if needed
   - Update dependencies to compatible versions

## Success Criteria
- Project must build successfully
- All unit tests must pass
