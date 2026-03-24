# Enterprise CI/CD Verified

This repository includes fully verified CI/CD workflows:

- CI build and test (Node.js 20)
- Docker build & push (Docker Hub)
- Release automation with automatic zip upload

## Usage

1. Push code to main branch -> CI runs automatically
2. Create tag v1.0.0 -> Release workflow runs automatically
3. Configure Docker secrets for Docker workflow
