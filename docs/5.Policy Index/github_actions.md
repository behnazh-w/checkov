---
layout: default
title: github_actions resource scans
nav_order: 1
---

# github_actions resource scans (auto generated)

|    | Id        | Type   | Entity         | Policy                                                                                                                                                                            | IaC            |
|----|-----------|--------|----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|
|  0 | CKV_GHA_1 | jobs   | jobs           | Ensure ACTIONS_ALLOW_UNSECURE_COMMANDS isn't true on environment variables                                                                                                        | github_actions |
|  1 | CKV_GHA_1 | jobs   | jobs.*.steps[] | Ensure ACTIONS_ALLOW_UNSECURE_COMMANDS isn't true on environment variables                                                                                                        | github_actions |
|  2 | CKV_GHA_2 | jobs   | jobs           | Ensure run commands are not vulnerable to shell injection                                                                                                                         | github_actions |
|  3 | CKV_GHA_2 | jobs   | jobs.*.steps[] | Ensure run commands are not vulnerable to shell injection                                                                                                                         | github_actions |
|  4 | CKV_GHA_3 | jobs   | jobs           | Suspicious use of curl with secrets                                                                                                                                               | github_actions |
|  5 | CKV_GHA_3 | jobs   | jobs.*.steps[] | Suspicious use of curl with secrets                                                                                                                                               | github_actions |
|  6 | CKV_GHA_4 | jobs   | jobs           | Suspicious use of netcat with IP address                                                                                                                                          | github_actions |
|  7 | CKV_GHA_4 | jobs   | jobs.*.steps[] | Suspicious use of netcat with IP address                                                                                                                                          | github_actions |
|  8 | CKV_GHA_5 | jobs   | jobs           | Found artifact build without evidence of cosign sign execution in pipeline                                                                                                        | github_actions |
|  9 | CKV_GHA_6 | jobs   | jobs           | Found artifact build without evidence of cosign sbom attestation in pipeline                                                                                                      | github_actions |
| 10 | CKV_GHA_7 | jobs   | on             | The build output cannot be affected by user parameters other than the build entry point and the top-level source location. GitHub Actions workflow_dispatch inputs MUST be empty. | github_actions |


---


