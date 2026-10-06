# Trivy Secret Scanning

Follow the decisions documented in:

- [ADR 01: Use Trivy to Scan Projects for Secrets](docs/adr/01-use-trivy-to-scan-projects-for-secrets.md): scan projects we work on with `trivy fs --scanners secret --exit-code 1 .`.
- [ADR 02: Use Trivy to Scan Published Images for Secrets](docs/adr/02-use-trivy-to-scan-published-images-for-secrets.md): scan the exact built image before publication with `trivy image --scanners secret --exit-code 1 IMAGE_REFERENCE`.

Read the relevant ADR before applying or changing its workflow. The reusable
[Trivy skill](SKILL.md) provides instructions for applying these decisions.
