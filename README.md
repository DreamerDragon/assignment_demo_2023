# Progress

Sorry I only forked the repository but did not manage to set up properly even with the provided commands, and I did not make any changes to the files.

# assignment_demo_2023

![Tests](https://github.com/TikTokTechImmersion/assignment_demo_2023/actions/workflows/test.yml/badge.svg)

This is a demo and template for backend assignment of 2023 TikTok Tech Immersion.

## Installation

Requirement:

- golang 1.18+
- docker

To install dependency tools:

```bash
make pre
```

## Run

```bash
docker-compose up -d
```

Check if it's running:

```bash
curl localhost:8080/ping
```
