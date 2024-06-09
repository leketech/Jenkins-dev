FROM openjdk:17-jdk-slim

RUN apt-get update && apt-get install -y maven && rm -rf /var/lib/apt/lists/*

WORKDIR /var/lib/jenkins/workspace/auto-job

# Add any additional environment variables or setup here

CMD ["cat"]
