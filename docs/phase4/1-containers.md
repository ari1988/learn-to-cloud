# Topic 1: Containerization

Containerization is a modern approach to deploying and managing applications and services across various environments. It allows you to package software, tools, and their dependencies into lightweight, portable units called containers.

**Key benefits include:**

- Consistency across development, testing, and production environments
- Efficient resource utilization compared to virtual machines
- Simplified deployment and scaling
- Isolation between applications

There are many containerization tools available like Docker, Podman, Containerd, etc.
In this topic, you'll learn how to use tools like Docker to create these isolated environments and explore how cloud platforms like AWS, Azure, and GCP support containerized workloads.

## Study

### Core Concepts

- What is [Containerization](https://github.com/resources/articles/devops/containerization)
- What is [Docker](https://youtu.be/3c-iBn73dDE)
- Difference between [Containerization and Virtualization](https://kodekloud.com/blog/virtualization-vs-containerization/)

### Container Registries

- What is a [Container Registry?](https://docs.docker.com/get-started/docker-concepts/the-basics/what-is-a-registry/)
- How to containerize an application and deploy on different container registries:
  - [DockerHub](https://docs.docker.com/get-started/workshop/04_sharing_app/)
  - [AWS ECR](https://docs.aws.amazon.com/AmazonECR/latest/userguide/docker-push-ecr-image.html)
  - [Azure Container Registry](https://learn.microsoft.com/en-us/training/modules/deploy-use-azure-container-registry/)
  - [Google Container Registry](https://www.youtube.com/watch?v=D1_FC6pGutQ)

## Test your knowledge

Use an AI assistant to test your understanding of containerization. Here's how:

1. Start a new conversation with ChatGPT, Claude, or Google Gemini
2. Use this initial prompt:

   ```txt
   I'm learning about containers and Docker. I'd like you to act as an interviewer:
   - Ask me questions one at a time about containerization concepts
   - Don't provide the answers immediately
   - Give me feedback on my responses
   - If I'm incorrect, guide me toward the right answer
   - Share relevant real-world examples after each answer
   Can we start?
   ```

3. Try to answer each question the AI asks. Key topics you should be ready to discuss:
   - Containers vs Virtual Machines
   - Docker architecture and components
   - Dockerfile structure and best practices
   - Container registries and image management
   - Container networking and storage
   - Security considerations

4. After each response:
   - Ask for feedback on your answer
   - Request real-world examples
   - Ask for clarification if needed

Pro tip: Share your specific context: "I'm working with a Node.js application that I want to containerize using Docker. Please focus your questions around that scenario."

Remember: The goal is to test your understanding, not to get perfect answers immediately.

## Hands-on Tasks

### Basic Containerization Project

1. Create a simple application (or use an existing one)
2. Write a Dockerfile for the application
3. Build the Docker image
4. Run the container locally and test functionality
5. Create an account on DockerHub or another container registry
6. Tag and push your image to the registry
7. Pull and run your image on a different machine to verify portability

### Common Issues & Troubleshooting

- [Docker Common Issues & Solutions](https://docs.docker.com/engine/reference/troubleshoot/)
- [Best Practices for Writing Dockerfiles](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/)
