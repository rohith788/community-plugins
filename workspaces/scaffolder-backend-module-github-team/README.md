# GitHub Team Scaffolder Backend Module

A Backstage scaffolder backend module for creating GitHub teams with comprehensive member management.

This workspace contains the GitHub Team scaffolder action that enables teams to create GitHub teams through Backstage's Software Templates.

## Plugins

- `@backstage-community/plugin-scaffolder-backend-module-github-team` - The main plugin that provides the `github:team:create` action

## Features

- Organization-level GitHub operations without requiring repository access
- Comprehensive team member management with role assignment
- Support for both GitHub Apps and personal access tokens
- Detailed success/failure tracking for member additions
- Privacy control (closed/secret teams)
- Robust error handling

## Getting Started

See the [plugin README](./plugins/github-team/README.md) for installation and usage instructions.

## Community

This plugin is part of the [Backstage Community Plugins](https://github.com/backstage/community-plugins) project.