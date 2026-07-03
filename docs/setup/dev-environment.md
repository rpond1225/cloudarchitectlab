Cloud Architect Lab Development Environment

Purpose

This document describes the local development environment used to build and maintain the Cloud Architect Lab website and portfolio projects.

Hardware

* Apple MacBook Air M4
* macOS (current version)

Project Workspace

~/Development/CloudArchitectLab/

Core Development Tools

Tool	Purpose
Git	Source control
GitHub	Remote repositories
Visual Studio Code	Primary IDE
Homebrew	Package manager
Node.js	JavaScript runtime
npm	Package management
Astro	Website framework

Cloud & Infrastructure Tools

Tool	Purpose
AWS CLI	AWS administration
Terraform	Infrastructure as Code
Mermaid CLI	Diagram rendering
Mermaid Chart	Architecture diagram authoring

VS Code Extensions

* AWS Toolkit
* GitLens
* Terraform
* Mermaid Chart
* Markdown All in One
* Markdown Mermaid
* Prettier
* Material Icon Theme

Git Configuration

Default branch:

main

Common workflow:

git status
git add .
git commit -m "Description"
git push

Documentation Standards

Every Cloud Architect Lab project should include, when appropriate:

* Architecture diagrams (Mermaid)
* Infrastructure as Code
* Technical documentation
* Validation/testing notes
* GitHub README
* Website article (for completed case studies)
* LinkedIn announcement (for completed case studies)

Repository Structure

docs/
├── diagrams/
├── setup/
└── architecture/

Environment Verification

Verify the following tools after a new installation:

git --version
node --version
npm --version
aws --version
terraform --version
mmdc --version
code --version

Notes

This environment is intended for learning, experimentation, and building clean-room portfolio projects. Production credentials, secrets, customer data, and employer-specific information must never be committed to Git repositories.