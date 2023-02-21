# paw – Tekton Task and Pipeline authoring helper

## Design

Goals:

- Ease creation of Tasks and Pipelines
  - From scratch
  - From a template
- Ease maintaining Tasks and Pipelines
  - versionning
    - using git based versionning
    - using directory based versionning
  - experimenting
- Provide easy way to tests Tasks and Pipelines
  - Convention (folder `test`, `fixtures`, …)
  - Provide a way to test parameters easily (without duplicating the
    yaml multiple times)
  - Validate results
    - State (success, failures, if failures, error messages, …)
    - Results field
  - Any other possible requirement
    - Filter based of platform…
    - … and platform specific things to create (SCC, …)
    - RBAC setup required for a task (deploy something, …)
    - Secret management (somehow)

- `paw` is also its own `Task` :)
  - will help experimenting with `paw` itself on managing versionning, …

