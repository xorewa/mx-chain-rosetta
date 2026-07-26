# Disabled upstream network workflows

These workflows are intentionally kept outside `.github/workflows/` so GitHub
Actions cannot execute them. They use MultiversX public networks, upstream
Mesh tooling, or external network credentials.

Xorewa runs only local build, test, coverage, and lint workflows on the
`NewArc` branch. Network integration is performed only against explicitly
approved Xorewa environments outside these inherited workflows.
