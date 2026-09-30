# AI DLP Diploma Project

AI DLP Diploma Project is a sanitized public version of a diploma project for an AI-assisted Data Loss Prevention prototype. The project demonstrates how sensitive data can be detected in files, browser activity, and endpoint events, then analyzed through a web interface and supporting agent tools.

This repository is prepared for public GitHub upload. It does not include private credentials, personal files, local logs, trained model checkpoints, raw datasets, virtual environments, or user uploads.

## Features

- Web dashboard for reviewing DLP events and risk indicators.
- DLP scanner for detecting sensitive text patterns and policy violations.
- Behavioral risk engine for evaluating user activity signals.
- Endpoint agent prototypes for collecting local activity events.
- Browser extension prototype for inspecting browser-side data flows.
- Training, evaluation, and regression scripts for experimentation.
- Unit and integration tests for the main application components.
- Sanitized presentation and analysis assets for explaining the project.

## Project Structure

```text
app/                       Flask web application, DLP engine, storage, templates, static UI
agent/                     Endpoint agent prototypes and local simulator
browser_extension/         Browser-side DLP inspection extension
scripts/                   Dataset preparation, training, evaluation, and utility scripts
tests/                     Unit and integration tests
analysis/                  Chart generation and sanitized analysis assets
presentation_package_max/  Presentation materials and architecture assets
