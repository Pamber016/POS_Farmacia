# Contributing Guide

## Language and Style

- All documentation and code comments should be in **English** to avoid mixed languages.
- All code should follow the conventions outlined in this guide, including naming conventions, code structure, and formatting.
- All commit messages should follow the **Conventional Commits** format, including a reference to the relevant user story (HU) or task ID.
- All pull requests should include a clear description of the changes made, how to test them, and any relevant context or links to documentation.

## Versioning Strategy (GitHub Flow)

- `main`: always stable. Protected: no direct push is made; only merge by PR with at least **1 approval** from the other team member and CI in green.
- Work branches, one per story or task:
  - `feature/HU-01-register-product`
  - `feature/HU-04-start-sale`
  - `fix/<short-description>`
  - `docs/<short-description>`
  - `chore/<short-description>`
- Commits following **Conventional Commits**, citing the HU:
  - `feat(HU-01): validar codigo unico al registrar producto`
  - `test(HU-04): agregar caso de producto inexistente`
  - `docs: actualizar casos de prueba`
- Versiones con **SemVer** mediante tags en `main`: `v0.1.0` (HU-01), `v0.2.0` (HU-04), etc.
- Merge with *squash* or *merge commit* (acordar uno y mantenerlo).

## Workflow

1. Take the issue from the HU and move it to "In progress".
2. Create the branch from the updated `main`.
3. **TODO : Define the development process and how to integrate the tests.**
4. Make frequent and descriptive commits.
5. Open a PR to `main` when the functionality is ready, with a description of the changes and tests.

## Code Conventions

- **TODO : Define code conventions and static analysis tools.**

## Definition of Done per User Story

- [ ] Acceptance criteria met
- [ ] Code is readable and follows the conventions of CONTRIBUTING_GUIDE.md
- [ ] Test cases implemented and passing (2-3 per user story, covering normal, boundary, and error cases)
- [ ] Total coverage >= 90 %
- [ ] Static analysis without errors or warnings
- [ ] Documentation updated
