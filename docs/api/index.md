---
icon: lucide/code
---

# API Reference

This page is a placeholder for generated API documentation. The most useful next step is to connect Zensical/MkDocs to `mkdocstrings` once the documentation repository has access to the `infretis` source package.

## Suggested Structure

| Area | Description |
|------|-------------|
| Engine interfaces | Wrappers around GROMACS, LAMMPS, ASE, CP2K, or AMS |
| Path objects | Path storage, order-parameter traces, and metadata |
| Ensembles | TIS and RETIS ensemble definitions |
| Moves | Shooting, Stone Skipping, Wire Fencing, and related trial moves |
| Exchange | Finite RE, infinite swapping, permanent calculation, and async exchange |
| Analysis | Crossing probabilities, WHAM, rates, and diagnostics |

## mkdocstrings Example

When the package is available in the docs environment, add the plugin and reference objects directly:

```toml
[project.plugins.mkdocstrings]
```

```markdown
::: infretis
```
