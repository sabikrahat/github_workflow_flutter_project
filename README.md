# github_workflow_check

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

## Steps

- Create a new Flutter project
- Copy the full .github folder from this repo into the new project
- Create a new repo on GitHub
- Generate a new personal access token with the repo scope
- Replace your credentials in the .github/workflows/main.yml file (see below)

```
    my_repo: "sabikrahat/github_workflow_flutter_project.git"
    my_secret: "${{secrets.WORKFLOW_TOKEN}}"
    my_email: "sabikrahat72428@gmail.com"
    my_name: "Md. Sabik Alam Rahat"
    my_tag: "v1.0.${{github.run_number}}"
```
   
