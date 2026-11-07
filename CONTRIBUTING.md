# Contributing Guide

## 1. Create a Feature Branch

Create a new branch before making changes.

Example:
git switch -c feature/my-feature

## 2. Make Your Changes

Write readable code and keep changes focused.

## 3. Run Local Checks

Before pushing, run:

- python -m pytest -v
- python -m ruff check src tests

## 4. Open a Pull Request

Push your branch and create a PR targeting main.

## 5. Review and Merge

Review the changed files and verify CI passes
before merging.