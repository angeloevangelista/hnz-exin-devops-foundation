# Class Summary

## General Ideas

1. **Value Stream and Automation**
   - Automating the value stream is crucial for improving efficiency.
   - The focus is on integrating automation into the process to enhance delivery.

2. **Pipeline de Implantação**
   - **Importance:** 5% for the exam.
   - **Definition:** A pipeline for automated deployment from code development to production.
   - **Origins:** Emerged alongside DevOps, with significant contributions from the book by Juvia Ambre on continuous delivery.

3. **Integration of LEAN and Continuous Delivery**
   - **LEAN:** Focuses on mapping and improving the value stream to deliver customer value.
   - **Continuous Delivery:** Involves automating the process from code repository to production.

4. **Stages of the Deployment Pipeline**
   - **Stage 1: Commitment or Confirmation**
     - **Goal:** Regular integration of code, ensuring it compiles and passes initial automated tests.
     - **Activities:** Code integration, automated unit tests, code analysis for standards and security.
   - **Stage 2: Automated Acceptance Testing**
     - **Goal:** Test the code in an environment that mimics production to verify functionality and non-functionality.
     - **Activities:** Functional and non-functional acceptance tests.
   - **Stage 3: Manual Testing (Optional)**
     - **Goal:** Perform occasional usability and other manual tests.
     - **Activities:** Visual and usability checks, often less frequent compared to automated tests.
   - **Stage 4: Production Deployment**
     - **Goal:** Deploy code to production in a stable and consistent manner.
     - **Activities:** Automated deployment, environment consistency checks.

5. **Challenges and Solutions**
   - **Integration Challenges:** Ensuring consistent code integration and avoiding conflicts.
   - **Testing Challenges:** Creating and maintaining stable test environments.
   - **Solutions:** Automation of integration, use of infrastructure as code, and frequent, stable environment provisioning.

## Acronyms and Terms

- **LEAN:** A methodology focused on improving value streams.
- **DevOps:** A set of practices that combines software development (Dev) and IT operations (Ops).
- **Continuous Delivery:** The practice of automating the deployment process from development to production.
- **Pipeline de Implantação:** The automated pipeline for deploying code.
- **MERGE:** The process of integrating code from multiple contributors.
- **Infrastructure as Code:** Techniques for managing and provisioning computing infrastructure through code.

