---
name: Request a New Package
about: Request that a new package be added to the meat-runner image.
title: "[New Package] - package_name"
labels: new package
assignees: ''

---

# Proposal: Add <package_name> to meat-runner

## Requirements

* **Package:** Briefly describe the package you'd like to add and its purpose (e.g., "Add `jq` for processing JSON data").
* **Implementation:** Outline how to add the package (version, configuration, potential conflicts). Include a code snippet if applicable.
  * Version:
  * Default Configuration:
  * Package Name (In apt repository): 
* **Alternatives:** Discuss other options considered and why this package is preferred.

## Example:

# Proposal: Add jq to Shared Dockerfile

## Requirements
We need the `jq` package as it's a common dependency across our organization.

* **Package:** Add `jq` (lightweight command-line JSON processor) to parse and manipulate JSON data within our applications.
* **Implementation:** Outline how to add the package (version, configuration, potential conflicts). Include a code snippet if applicable.
  * Version: 1.7.1
  * Default Configuration: N/A
  * Package Name (In apt repository): `jq`
* **Alternatives:** Discuss other options considered and why this package is preferred.
- `zq` - https://zed.brimdata.io/ - More robust than `jq`
