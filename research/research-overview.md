# PHP2Shell — Research Overview

## 1. Research Background

This project investigates PHP2Shell and the security implications of PHP memory-management vulnerabilities.

The research focuses on understanding the underlying concepts, reviewing available technical references, and documenting observations from an isolated research environment.

## 2. Vulnerability Concepts

### 2.1 Out-of-Memory (OOM)

Out-of-Memory conditions occur when a program cannot allocate the memory required to continue an operation.

Research areas:
- PHP memory allocation and limits
- Memory exhaustion
- Error handling during allocation failures
- Potential security implications

### 2.2 Use-After-Free (UAF)

A Use-After-Free condition occurs when software accesses memory after that memory has been released.

Research areas:
- Memory allocation and deallocation
- Pointer and reference management
- Stale references
- Potential memory corruption

## 3. Reported PHP2Shell Vulnerabilities

The project examines the following reported vulnerability identifiers:

- CVE-2026-109618
- CVE-2026-109619

Their technical details, affected versions, and security impact must be documented against authoritative references before being treated as confirmed findings.

## 4. Research Methodology

1. Review the original research and technical references.
2. Understand the relevant PHP memory-management concepts.
3. Document the isolated lab architecture.
4. Record observations from authorized experiments.
5. Analyze security implications.
6. Document defensive recommendations.

## 5. Evidence

Screenshots, logs, and experiment notes will be stored in the `evidence/` directory.

## 6. Research Limitations

Findings from a specific test environment should not automatically be generalized to all PHP versions or deployments.

All observations must be distinguished from independently verified vulnerability facts.
