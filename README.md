## SetUp Git Repo

## Setuo GitHubAction

## Add VM Runner

## CICD YAML Scratch

## Trivy , Sonar , Docker , K8s

#### In GitHub Action

1. No need vm to run the cicd
2. Only need to have the GitRepo
3. In inside the github action there is runner where application is build
   1. shared runner

      1. Completly free / but you don't have the access to backend config.
      2. On Ubuntu -> ubuntu:latest
      3.
   2. private runner

      1. We bring our own machine , completly access and completly isolated

### Phase 1 ->  Setup GitRepo

### Phase 2 -> VM as Runner

### Phase 3 -> CICD

1. Security Check
2. Test Cases
3. Build & publish
4. Build and Scan Docker image and pull
5. Deploy to K8s
