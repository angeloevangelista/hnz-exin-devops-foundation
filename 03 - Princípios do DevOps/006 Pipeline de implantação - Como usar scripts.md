# Summary of Deployment Pipeline Class

## Key Ideas

1. **Script Creation for Each Pipeline Stage**
   - Create a script for every stage of the deployment pipeline.
   - Separate stages by specialties, ensuring that each step is handled distinctly.

2. **Use of Consistent Scripts Across Environments**
   - Apply the same scripts for deploying in different environments (test, staging, production).
   - This avoids inconsistencies and ensures that updates to scripts are uniformly applied.

3. **Idempotent Processes**
   - Ensure that processes are idempotent, meaning they produce the same result regardless of how many times they are run.
   - This helps maintain consistency and stability across environments.

4. **Incremental Process Evolution**
   - Evolve deployment processes incrementally rather than adopting new tools without understanding their fit.
   - Start by automating manual processes to gain insights and optimize before selecting tools.

## Specific Acronyms and Terms

- **Idempotent**: A process that produces the same result no matter how many times it is executed.
- **Pipeline**: A sequence of stages or steps used to deploy code through different environments.
- **Script**: Automation code used to perform tasks such as compilation, testing, and deployment.
