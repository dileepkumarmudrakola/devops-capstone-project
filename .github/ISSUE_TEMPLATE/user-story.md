
---

### 📌 Story 7: Deploy to Kubernetes
**Title:** `[User Story] Deploy Docker image to Kubernetes`

```markdown
**As a** DevOps engineer  
**I need** to deploy the Docker container  
**So that** the service is accessible in a Kubernetes cluster  

### Details and Assumptions
* Uses OpenShift or IBM Cloud Kubernetes

### Acceptance Criteria     
```gherkin
Given a Docker image is available  
When I apply the Kubernetes manifests  
Then the service is deployed and reachable
