---
title: "GEI"
date: 2023-04-18T13:35:29+02:00
draft: true
tags: ["github"]
---

# GEI GHEC=>GHEC+EMU

## What is GitHub Enterprise Importer?

GitHub Enterprise Importer is a tool provided by GitHub that allows users to migrate their repositories from third-party version control systems like GitLab, Bitbucket, or SVN to GitHub Enterprise. It simplifies the process of migration by automating most of the work and reducing the amount of manual effort required.

With the GitHub Enterprise Importer, users can migrate their repositories, including their entire history of commits, issues, and pull requests, as well as any associated metadata. The tool also provides a user-friendly interface that allows users to monitor the progress of their migration and to view any errors or warnings that may have occurred during the process.

GitHub Enterprise Importer is designed specifically for enterprise users who need to migrate large repositories or multiple repositories from their current version control system to GitHub Enterprise. It is available as part of the GitHub Enterprise subscription, and users can access it through the GitHub Enterprise web interface.

## How does GitHub Enterprise Importer work?

GitHub Enterprise Importer works by connecting to the existing version control system where the repositories are currently stored and extracting all the necessary data such as commits, issues, pull requests, and associated metadata. It then transforms this data into a format that can be imported into GitHub Enterprise.

Here are the general steps involved in using GitHub Enterprise Importer:

1. Connect to the source repository: The user enters the credentials for the source repository, including the URL and authentication details.

1. Select repositories to migrate: The user selects the repositories they want to migrate to GitHub Enterprise.

1. Configure migration settings: The user configures various settings such as branch mapping, pull request handling, and label mapping.

1. Start migration: The user starts the migration process, and GitHub Enterprise Importer begins extracting the data from the source repository.

1. Monitor progress: The user can monitor the progress of the migration, including any errors or warnings that may occur during the process.

1. Complete migration: Once the migration is complete, the user can verify that all the data has been successfully transferred to GitHub Enterprise.

Overall, GitHub Enterprise Importer makes the process of migrating repositories from one version control system to another much simpler and more efficient. It automates many of the steps involved in the process, reducing the amount of manual effort required and helping to ensure that the migration is successful.

## References

- [Offering](https://docs.google.com/presentation/d/1ZbSTFBifaL0_1559uO5WmsNab06Kdfek/edit#slide=id.g176a8ede989_0_0)
- [Using GitHub Enterprise Importer](https://docs.github.com/en/migrations/using-github-enterprise-importer)
- [Migrate GHEC to GHEC+EMU](GHEC%20to%20GHEC%2BEMU.md)
