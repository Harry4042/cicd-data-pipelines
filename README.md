# Overview

A Simple CI/CD Data Engineering Project.

# File Structure

| Directory/File | Description |
| --- | --- |
| **.github/** | Holds github configuration e.g. CI/CD workflows. |
| **airflow/** | Apache Airflow DAGs for data pipeline orchestration. |
| **dbt_project/** | Data build tool project with SQL objects. |
| **scripts/** | Helper scripts. |
| **terraform/** | Infra As Code definitions. |
| .gitignore | Files to ignore in local git repos |
| pyproject.toml | Python project tooling. |
| README.md | Repo readme file for documentation |
| requirements.txt | Python dependencies. |

# Features

| Feature | Description |
| --- | --- |
| Pre-commits | Runs checks on the commit of a file. Definition in `.pre-commit-config.yaml` |