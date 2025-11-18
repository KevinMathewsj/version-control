# DevOps Java Project – Git Workflow Documentation

## 1. Initialize Repo
Commands used:
- git init
- git add .
- git commit -m "chore: initial Java project"

## 2. Branching Strategy
- main (production)
- dev (integration)
- feature/* (feature development)

## 3. Pull Requests
- Feature → Dev
- Dev → Main

## 4. CI Pipeline
- Runs Maven build
- Runs on push & PR

## 5. Tags
- v1.0.0 — first stable release
