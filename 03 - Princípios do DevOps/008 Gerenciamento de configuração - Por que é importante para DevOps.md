# Summary of Configuration Management in DevOps

## General Ideas

- **Configuration Management**: Ensures consistency across all elements of a solution by versioning all components, including the final environment configuration. 
- **Version Control**: Applies to both the parts of the solution and the final configuration of the environment.
- **Environment Replication**: Create consistent intermediate environments similar to production.
- **Evolution from AIT**: While AIT involved representation for understanding impacts and changes, modern configuration management includes active control and automation of environment setup.
- **Infrastructure as Code**: Utilizes code to version each element and manage deployments, enabling remote, controlled, and automated configuration management.
- **Consistency and Quality**: Automates management to increase stability, control, and quality of deployments. Allows quick restoration of environments to desired states and reduces manual intervention.
- **Deployment Techniques**: Supports methods like Canary and Blue-Green deployments for real-time transitions and minimized impact during updates.

## Key Terms and Acronyms

- **AIT**: Refers to ITIL (Information Technology Infrastructure Library) practices related to configuration management.
- **Infrastructure as Code (IaC)**: Managing infrastructure through code to automate configuration and deployments.
- **Canary Deployment**: A technique where a new version is gradually rolled out to a small subset of users before full deployment.
- **Blue-Green Deployment**: A strategy involving two environments (blue and green) where the new version is deployed to one environment and traffic is switched from the old environment to the new one.
