## Architecture

```mermaid
flowchart LR
    Developer["Developer"] --> GitHub["GitHub Repository"]
    GitHub --> Jenkins["Jenkins Server on EC2"]

    subgraph AWS["AWS Cloud - us-east-1"]
        Jenkins --> Build["Docker Build and Health Test"]
        Build --> ECR["Amazon ECR"]
        Jenkins --> SSM["AWS Systems Manager"]
        SSM --> AppEC2["WellSpring Application EC2"]
        ECR --> AppEC2
    end

    User["Application User"] --> AppEC2
