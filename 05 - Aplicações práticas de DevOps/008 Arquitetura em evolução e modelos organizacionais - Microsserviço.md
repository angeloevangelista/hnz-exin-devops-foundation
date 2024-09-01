# Class Summary

## General Ideas

1. **Microservices Architecture**
   - Microservices embed their own storage, allowing for scalable, independent services.
   - This approach avoids bottlenecks associated with a single, centralized database.
   - Each microservice has its own database, which facilitates scaling and reduces centralization issues.

2. **Challenges in Microservices**
   - **Domain Definition**: Defining clear boundaries and efficient structures for each microservice can be complex.
   - **Database Management**: Integrating versioning and managing databases across microservices requires careful planning.
   - **Monitoring and Scaling**: Each service must be monitored for demand and performance, which adds to the complexity.

3. **Migration Approaches**
   - **Greenfield vs. Brownfield**:
     - **Greenfield**: Starting from scratch, akin to building on a new, undeveloped site. Allows for complete freedom but may have hidden challenges.
     - **Brownfield**: Upgrading or replacing an existing system, similar to renovating an old building. Requires dealing with existing issues and ongoing changes.
   - Migration from an old system to a new one can be challenging due to evolving requirements and the need for updated documentation.

4. **Incremental Transformation**
   - Gradual transformation, rather than a complete overhaul, is often recommended. This involves evolving the system incrementally while maintaining both old and new components.
   - Techniques like "strangulation" can be used to gradually replace old components with new ones without disrupting the overall system.

## Acronyms and Terms

- **Microservices**: Architectural style where services are independently deployable and scalable, each with its own database.
- **Greenfield**: Starting a new project from scratch, with no constraints from existing systems.
- **Brownfield**: Upgrading or modifying an existing system, which involves dealing with pre-existing conditions and constraints.
- **Strangulation**: A technique for incrementally replacing legacy systems with new ones by slowly migrating functionality and components.
- **Domain Definition**: The process of specifying boundaries and responsibilities for each microservice within the architecture.
