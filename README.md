# PHP2Shell — Vulnerability Research Lab

A personal cybersecurity research project exploring PHP2Shell, PHP memory-management concepts, security implications, and defensive considerations.

## Research Objectives

- Understand the PHP mechanisms involved in the reported vulnerabilities.
- Study Out-of-Memory (OOM) and Use-After-Free (UAF) concepts.
- Examine memory corruption risks in PHP applications.
- Document an isolated research environment.
- Study defensive measures and security mitigations.

## Repository Structure

php2shell-lab-research/
├── evidence/
├── lab/
│   └── lab-architecture.md
├── research/
│   └── research-overview.md
├── README.md
├── REFERENCES.md
└── .gitignore

## Research Methodology

1. Review technical references.
2. Study relevant PHP memory-management concepts.
3. Document the research environment.
4. Record experimental observations.
5. Analyze security implications.
6. Document defensive recommendations.

## Evidence and Observations

Screenshots and experiment records are maintained in `evidence/`.

Technical analysis and research notes are maintained in `research/`.

## Security and Scope

- Research is limited to authorized environments.
- Keep vulnerable services isolated and bound to localhost.
- Do not expose vulnerable services to public networks.
- Use patched software in production environments.
- Treat experimental results as observations from the specific test environment.

## References

See [REFERENCES.md](REFERENCES.md) for research sources and attribution.

## Author

Independent cybersecurity learning and vulnerability research project.
