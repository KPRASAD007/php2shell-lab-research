# PHP2Shell — Lab Architecture

## 1. Purpose

This document describes the isolated environment used for PHP2Shell research.

## 2. Host Environment

| Component | Details |
|---|---|
| Operating System | Kali Linux Rolling |
| Virtualization | VirtualBox |
| Containerization | Docker |
| Web Server | Apache |
| PHP Version Previously Examined | 8.4.26 |
| Host Binding Previously Used | 127.0.0.1:8088 |

## 3. Architecture

The research environment uses Docker to isolate the PHP web application from the host operating system.

Conceptual flow:

Research Host (Kali Linux)
        |
        v
Docker Container
        |
        v
Apache Web Server
        |
        v
PHP Application

## 4. Isolation and Safety

- Keep the research environment isolated.
- Bind lab services to localhost.
- Do not expose vulnerable services to public networks.
- Do not test systems without explicit authorization.
- Use patched software for production deployments.

## 5. Configuration Status

The PHP 8.4.26 environment and localhost binding listed above describe a previously examined setup.

The configuration for this new repository will be independently documented. Reference implementation files are not being redistributed without permission.

## 6. Observations

Detailed experimental observations and supporting evidence will be documented separately in the `research/` and `evidence/` directories.
