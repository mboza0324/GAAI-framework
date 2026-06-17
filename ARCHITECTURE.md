# ARCHITECTURE.md

## Overview

GAAI Framework stores governance and agent-operating contracts in `.gaai/`, supporting documentation in `docs/`, and repository automation in `.github/workflows/`.

## Trust boundaries

Pull-request content is untrusted. GitHub Actions must use least privilege. External AI services must not receive repository content automatically. Any architecture-changing automation requires human approval, validation, and rollback documentation.
