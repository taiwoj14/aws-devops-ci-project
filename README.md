
# AWS DevOps CI Pipeline Project

## Overview

This project demonstrates a continuous integration pipeline using AWS CodeCommit, AWS CodeBuild, and AWS CodePipeline.

## Application

A simple Python calculator with automated unit tests.

## Technologies

- AWS CodeCommit — source control
- AWS CodeBuild — build and test automation
- AWS CodePipeline — pipeline orchestration
- Python 3.12
- pytest — automated testing

## Build Process

1. Code is pushed to the CodeCommit repository.
2. CodePipeline detects the source change.
3. CodeBuild installs pytest and runs the unit tests.
4. If the tests pass, CodeBuild produces a ZIP artifact.

## IAM Roles

The CodeBuild and CodePipeline service roles will be documented after they are configured.

## Verification Evidence

Screenshots of the successful pipeline and build artifact will be added after deployment.
