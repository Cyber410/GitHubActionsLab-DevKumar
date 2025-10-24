# GitHub Actions Lab - Dev Kumar

This lab demonstrates GitHub Actions workflows: job dependencies, environment variables, secrets, and multi-platform testing.

## Workflows

### 1️⃣ dependent-jobs.yml
- Job dependencies using `needs`  
- Order: build → test → deploy
- shows us how to run jobs in sequence

### 2️⃣ env-and-secrets.yml
- Workflow, job, step-level environment variables  
- Secure use of GitHub secrets
- it shows us how to secretly store all the credentials

### 3️⃣ multi-platform.yml
- Runs on Ubuntu, Windows, macOS  
- Demonstrates parallel job execution
- shows us how to run jobs in parllel

## Key Concepts
- **needs** → job dependencies  
- **env** → environment variable scopes  
- **runs-on** → OS selection  
- **workflow_dispatch** → manual trigger

## Challenges
- YAML indentation errors fixed using linter  
- Faced challenges to run jobs ... had to figure out that i forgot to run it and run it at end 
