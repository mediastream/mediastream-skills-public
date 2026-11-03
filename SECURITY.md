# Security Policy

This repository distributes AI agent skills and Claude Code plugins for the Mediastream platform. Skills are text that an agent executes on your behalf, so we treat their integrity as a security concern.

## What we guarantee

- Every release is built and published by GitHub Actions from a tagged commit on `main`; nothing is published from a developer machine.
- npm packages are published with provenance attestations.
- Every change passes secret scanning, a context-leak scanner (no internal hostnames, customer data or private endpoints) and human review before merge.
- Skills only reference public Mediastream endpoints and documentation.

## Reporting a vulnerability

If you find a skill that leaks internal information, contains instructions outside the scope of the Mediastream product, or could be used to attack an agent that installs it, please report it privately:

- Use GitHub's private vulnerability reporting on this repository, or
- Email sistemas@mediastre.am

Please do not open a public issue for security reports. We aim to acknowledge reports within 2 business days.

## Supported versions

Only the latest release of each plugin is supported. Older versions may reference deprecated API behavior.
